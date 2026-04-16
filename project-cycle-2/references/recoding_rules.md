# Recoding Rules for Behavior Variable

**Variable:** `CurrentAlcoholUse`
* Original Code `1` (0 days of use) -> Recoded as `0` (Failure)
* Original Codes `2` to `7` (1 or more days of use) -> Recoded as `1` (Success)
* Missing or other invalid codes -> Dropped (NaN)
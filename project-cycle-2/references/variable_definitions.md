# Variable Definitions and Benchmarks

### 1. Behavior Variable
* **Name:** `CurrentAlcoholUse`
* **Measurement:** Whether the student currently uses alcohol.
* **Valid Codes:** `1`, `2`, `3`, `4`, `5`, `6`, `7`
* **Missing Values:** Blank or invalid codes are dropped (NaN).
* **Benchmark Proportion (p0):** `0.35`

### 2. Continuous Variable
* **Name:** `BMIPCT`
* **Measurement:** The student's BMI percentile.
* **Valid Codes:** Numeric values (typically between 0 and 100).
* **Missing Values:** Blank or invalid values are dropped (NaN).
* **Benchmark Mean (mu0):** `65.0`
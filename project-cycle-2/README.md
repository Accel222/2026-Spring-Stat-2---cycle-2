# Project Cycle 2: Confidence Intervals and One-Sample Inference

**Group Number:** 18
**Member Names:**
周朝賢_112310326
楊玉如_113440033
方立謙_113370202

### 1. Dataset Used
* **Dataset:** `YRBS_2007.csv`

### 2. Selected Variables & Benchmarks
* **Behavior Variable (Proportion Analysis):** `CurrentAlcoholUse`
  * **Benchmark:** p₀ = 0.35
* **Continuous Variable (Mean Analysis):** `BMIPCT`
  * **Benchmark:** μ₀ = 65.0

### 3. Project Questions
* **Proportion Analysis:** Is the proportion of students who currently use alcohol different from 0.35?
* **Mean Analysis:** Is the mean BMI percentile (BMIPCT) of students different from 65.0?

### 4. Final Conclusion
* **Alcohol Use:** We strongly reject the null hypothesis (p-value < 0.05). The true proportion of students currently using alcohol is significantly higher than 0.35 (Sample proportion: ~45.17%, 95% CI: 0.443 to 0.460).
* **BMI Percentile:** We fail to reject the null hypothesis (p-value = 0.4816). There is no significant difference between the students' mean BMI percentile and the benchmark of 65.0.

This project demonstrates how to apply statistical hypothesis testing using IBM SPSS, Excel, Manual Calculations, and Python (SciPy).
It includes two real-world case studies that use paired sample t-tests and independent two-sample t-tests to evaluate performance improvement.

📁 Project Overview

This project contains:

Case Study 1: Effect of a speed & agility camp on player sprint performance

Case Study 2: Effectiveness of a new textbook on student test scores

Manual Calculations (means, standard deviations, t-statistic, p-value)

Excel Results

SPSS Output

Python Implementation

📝 Case Study 1 — Paired Sample t-Test
Does a training camp improve players' 30-yard dash speed?
🔹 Hypotheses

H₀: Mean speed before = Mean speed after

H₁: Mean speed before ≠ Mean speed after

🔹 Summary

n = 15 players

Mean Before = 5.062

Mean After = 4.969

Mean Difference = 0.093

SD of Differences = 0.336

🔹 Results

t-Statistic: 1.075

p-value: 0.3005 (two-tailed)

🔹 Conclusion

❌ No statistically significant improvement after the camp.
The p-value > 0.05, so we fail to reject the null hypothesis.

📝 Case Study 2 — Independent Two-Sample t-Test
Does the new textbook improve student test scores?
🔹 Hypotheses

H₀: Mean_old = Mean_new

H₁: Mean_new > Mean_old

🔹 Summary

n₁ = 15 (old book), n₂ = 15 (new book)

SD_old = 13.346

SD_new = 10.112

df = 28

🔹 Results

t-Statistic: 2.159

p-value: 0.0198 (one-tailed)

🔹 Conclusion

✅ Significant improvement with the new textbook.
The p-value < 0.05, so we reject the null hypothesis.

🛠 Tools & Technologies Used
Statistical Techniques

Paired Sample t-Test

Two-Sample Independent t-Test

Hypothesis Formulation

p-value Interpretation

Software

IBM SPSS

Microsoft Excel

Python (SciPy)

Manual Statistical Computation

Python Example
from scipy import stats

# Paired t-test
stats.ttest_rel(before_camp, after_camp)

# Independent two-sample t-test
stats.ttest_ind(old_book, new_book)

📌 Key Learnings

How to compute test statistics manually

How to validate results using Excel, SPSS, and Python

How to interpret hypothesis testing outcomes

How to compare paired vs independent samples

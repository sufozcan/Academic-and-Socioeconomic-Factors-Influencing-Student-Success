# Academic and Socioeconomic Factors Influencing Student Success

This project investigates the key factors that drive academic performance in high school students, focusing on both Mathematics and Language (Portuguese) courses.

## Project Overview
Using a dataset of 382 high school students, this research applies rigorous statistical methods to determine how personal habits, socioeconomic status, and motivation impact academic outcomes. The study aims to provide data-driven insights for educators and policymakers.

## Statistical Toolkit & Tools
* **Language:** **R** (R-Studio)
* **Techniques Applied:**
    * **Descriptive Statistics:** Summary tables and exploratory data analysis.
    * **Hypothesis Testing:** Shapiro-Wilk (Normality), Levene’s Test (Homogeneity of Variance), Mann-Whitney U, and Kruskal-Wallis tests.
    * **Regression Analysis:** Multiple Linear Regression (MLR) with model selection, log-transformations, and assumption checking (VIF, Durbin-Watson, Q-Q plots).
    * **Analysis of Variance:** One-Way ANOVA and Welch's t-test.

## Key Research Findings
* **Study Time & Grades:** Weekly study time has a **highly significant positive impact** on Language grades ($p \approx 0$), whereas its effect on Math is marginally non-significant ($p = 0.053$).
* **Alcohol Consumption:** Weekend alcohol consumption has a **significant negative impact** on Language performance, while no notable effect was found for Mathematics.
* **Motivation for Higher Education:** Students aiming for higher education performed significantly better in both subjects, highlighting the importance of long-term academic goals.
* **Academic Support Paradox:** Students receiving school support had **significantly lower Math grades** ($\beta = -1.42$, $p = 0.013$), suggesting that this support is primarily utilized by students who are already struggling.
* **Family Background:** **Mother's education level (Medu)** and **family size** emerged as significant predictors for Math performance.

## Visual Insights
The analysis is supported by various statistical plots generated in R:
* **Boxplots:** Used for categorical comparisons (e.g., romantic status vs. grades).
* **Violin Plots:** Visualizing the distribution of grades by type of academic support.
* **Diagnostic Plots:** Residual vs Fitted and Q-Q plots to validate regression model assumptions.




## Conclusion & Future Work
Academic success is a multifaceted outcome influenced by personal habits, family background, and intrinsic motivation. Future research could incorporate psychological variables such as anxiety levels and learning strategies to build even more robust predictive models.

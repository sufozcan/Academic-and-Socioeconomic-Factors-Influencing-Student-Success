# Academic and Socioeconomic Factors Influencing Student Success

[cite_start]This project investigates the key factors that drive academic performance in high school students, focusing on both Mathematics and Language (Portuguese) courses. [cite: 350, 353]

## Project Overview
[cite_start]Using a dataset of 382 high school students, this research applies rigorous statistical methods to determine how personal habits, socioeconomic status, and motivation impact academic outcomes. [cite: 350, 353] [cite_start]The study aims to provide data-driven insights for educators and policymakers. [cite: 365]

## Statistical Toolkit & Tools
* [cite_start]**Language:** **R** (R-Studio) [cite: 354]
* **Techniques Applied:**
    * [cite_start]**Descriptive Statistics:** Summary tables and exploratory data analysis. [cite: 355, 379]
    * [cite_start]**Hypothesis Testing:** Shapiro-Wilk (Normality), Levene’s Test (Homogeneity of Variance), Mann-Whitney U, and Kruskal-Wallis tests. [cite: 651, 652, 677, 725]
    * [cite_start]**Regression Analysis:** Multiple Linear Regression (MLR) with model selection, log-transformations, and assumption checking (VIF, Durbin-Watson, Q-Q plots). [cite: 806, 807, 861, 862, 884, 904]
    * [cite_start]**Analysis of Variance:** One-Way ANOVA and Welch's t-test. [cite: 673, 775]

##  Key Research Findings
* [cite_start]**Study Time & Grades:** Weekly study time has a **highly significant positive impact** on Language grades ($p \approx 0$), [cite: 683, 684] [cite_start]whereas its effect on Math is marginally non-significant ($p = 0.053$). [cite: 680, 681]
* [cite_start]**Alcohol Consumption:** Weekend alcohol consumption has a **significant negative impact** on Language performance, [cite: 739, 740] [cite_start]while no notable effect was found for Mathematics. [cite: 741]
* [cite_start]**Motivation for Higher Education:** Students aiming for higher education performed significantly better in both subjects, highlighting the importance of long-term academic goals. [cite: 781, 782, 783]
* [cite_start]**Academic Support Paradox:** Students receiving school support had **significantly lower Math grades** ($\beta = -1.42$, $p = 0.013$), [cite: 825, 826] [cite_start]suggesting that this support is primarily utilized by students who are already struggling. [cite: 827]
* [cite_start]**Family Background:** **Mother's education level (Medu)** and **family size** emerged as significant predictors for Math performance. [cite: 880, 1029]

## Visual Insights
The analysis is supported by various statistical plots generated in R:
* [cite_start]**Boxplots:** Used for categorical comparisons (e.g., romantic status vs. grades). [cite: 638]
* [cite_start]**Violin Plots:** Visualizing the distribution of grades by type of academic support. [cite: 801]
* [cite_start]**Diagnostic Plots:** Residual vs Fitted and Q-Q plots to validate regression model assumptions. [cite: 842, 849, 905, 922]




##  Conclusion & Future Work
[cite_start]Academic success is a multifaceted outcome influenced by personal habits, family background, and intrinsic motivation. [cite: 1030] [cite_start]Future research could incorporate psychological variables such as anxiety levels and learning strategies to build even more robust predictive models. [cite: 1036]

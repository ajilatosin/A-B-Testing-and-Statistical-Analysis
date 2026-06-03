# Marketing A/B Testing Conversion Analysis

## Project Overview

This project analyzes the effectiveness of a digital advertising campaign using A/B testing and statistical hypothesis testing. The objective was to determine whether users exposed to advertisements converted at a higher rate than users shown a Public Service Announcement (PSA) control group.

Using exploratory data analysis (EDA), statistical testing, and behavioral analysis, the study evaluates campaign performance across **588,101 users** and provides actionable recommendations for improving conversion rates and marketing ROI.

---

## Business Problem

Marketing teams need to determine whether advertising campaigns generate meaningful business impact or whether observed improvements are due to random variation.

This analysis answers:

* Do advertisements significantly increase conversion rates?
* How large is the conversion uplift?
* What user behaviors influence conversion?
* How can campaign performance be optimized?

---

## Dataset Summary

| Metric            | Value   |
| ----------------- | ------- |
| Total Users       | 588,101 |
| Ad Group Users    | 564,577 |
| PSA Control Users | 23,524  |
| Ad Conversions    | 14,423  |
| PSA Conversions   | 420     |

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels
* Jupyter Notebook

---

## Methodology

### 1. Exploratory Data Analysis (EDA)

Performed analysis on:

* Conversion distribution
* Ad exposure frequency
* Hourly conversion trends
* Day-of-week conversion patterns
* User engagement behavior

### 2. Statistical Hypothesis Testing

To validate campaign effectiveness, multiple statistical tests were conducted:

* Two-Proportion Z-Test
* Chi-Square Test of Independence
* Confidence Interval Estimation
* Effect Size Analysis (Cohen's h)

---

## Key Results

| Metric           | Ad Group                | PSA Group |
| ---------------- | ----------------------- | --------- |
| Conversion Rate  | 2.55%                   | 1.79%     |
| Absolute Lift    | +0.77 percentage points |           |
| Relative Lift    | +43.1%                  |           |
| Z-Statistic      | 7.37                    |           |
| P-Value          | < 0.0000000001          |           |
| Confidence Level | >99.99%                 |           |

### Statistical Conclusion

The advertising campaign produced a statistically significant increase in conversions.

The probability that this improvement occurred by chance is effectively zero, providing strong evidence that ad exposure positively impacts user conversion.

---

## Behavioral Insights

### Ad Frequency

Conversion rates increased as users were exposed to more advertisements, peaking between approximately 4–20 ad impressions.

Beyond this range, conversion gains diminished, suggesting ad fatigue and diminishing returns.

### Time of Day

Highest conversion performance occurred during:

* 10 AM – 4 PM
* 7 PM – 9 PM

Off-peak hours consistently underperformed.

### Day-of-Week Effects

Conversion rates varied across weekdays, indicating opportunities to improve campaign efficiency through optimized scheduling.

---

## Business Recommendations

### 1. Implement Frequency Caps

Limit exposure to approximately 15–20 ads per user to prevent oversaturation and improve advertising efficiency.

### 2. Optimize Ad Scheduling

Allocate more budget to high-converting time windows:

* Primary: 10 AM – 4 PM
* Secondary: 7 PM – 9 PM

### 3. Improve Day-Level Budget Allocation

Shift campaign spend toward the highest-performing weekdays to maximize conversions without increasing budget.

### 4. Improve Future Experiment Design

Use a more balanced test structure (e.g., 85–90% Ad Group, 10–15% Control Group) to improve statistical precision.

### 5. Build Predictive Models

Develop machine learning models to predict conversion propensity and enable precision targeting.

---

## Business Impact

Key findings indicate that advertising exposure generated:

* 43.1% higher conversion rates
* Approximately 8 additional conversions per 1,000 users reached
* Thousands of incremental conversions at scale

The analysis demonstrates that the campaign should be continued and optimized through improved targeting, scheduling, and exposure management.

---

## Project Deliverables

* Marketing A/B Testing Analysis Notebook
* Executive Insight Report
* Statistical Testing Results
* Behavioral Conversion Analysis

---

## Final Recommendation

**Scale the Campaign**

The campaign delivered a statistically significant uplift in conversions across more than half a million users. Combined with clear optimization opportunities in ad frequency and scheduling, the results support continued investment and campaign expansion.

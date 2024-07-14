# A/B Testing Analysis of Online Shoppers Intention Dataset

## Overview
This project conducts an A/B testing analysis to evaluate the impact of a new marketing strategy on the revenue of online shoppers. The analysis uses the "online_shoppers_intention" dataset from Kaggle.

## Dataset
The dataset contains various features related to online shopping sessions, including:

- Administrative
- Administrative Duration
- Informational
- Informational Duration
- Product Related
- Product Related Duration
- Bounce Rates
- Exit Rates
- Page Values
- Special Day
- Month
- Operating Systems
- Browser
- Region
- Traffic Type
- Visitor Type
- Weekend
- Revenue

## Hypothesis
- *Null Hypothesis (H0)*: The new marketing strategy has no effect on the revenue.
- *Alternative Hypothesis (H1)*: The new marketing strategy increases the revenue.

## Methodology
1. *Data Preprocessing*: Cleaned and prepared the dataset for analysis.
2. *Randomly Split the Data*: Divided the dataset into control and test groups.
3. *Perform the A/B Test*: Conducted a t-test to compare the revenue between the control and test groups.
4. *Analyze Results*: Interpreted the p-value to draw conclusions.

## Results
The t-test resulted in:
- T-statistic: X.XX
- P-value: X.XX

Based on the p-value, we concluded that (accept/reject) the null hypothesis and determined that the new marketing strategy (does/does not) have a significant impact on the revenue.

## Conclusion
This analysis provided insights into the effectiveness of the new marketing strategy. Further investigations and potential adjustments to the strategy can be explored to enhance its impact.

## How to Use
1. Clone this repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/henrysue/online-shoppers-intention).
3. Run the analysis script to reproduce the results.

## License
This project is licensed under the MIT License.

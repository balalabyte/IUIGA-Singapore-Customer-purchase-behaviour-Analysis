# IUIGA Singapore Case Study Analysis

![image](https://github.com/balalabyte/IUIGA-Singapore-Customer-purchase-behaviour-Analysis/assets/60688697/a5f446cd-17e0-4f84-9cc4-baae03acd970)


## Overview

This case study focuses on analyzing customer purchase behaviors, device usage, and purchase frequencies using the IUIGA dataset. By examining transaction data, we aim to uncover patterns that could inform business decisions, enhance customer engagement strategies, and optimize the user experience across different platforms.

## Dataset Description
The dataset contains transaction records for 103,315 entries, detailing customer IDs, transaction dates, purchase channels, basket sizes (both in units and dollars), and devices used for the transactions. The data spans various purchase channels, including online and pop-up/offline stores.

## Analysis Summary

### Device Usage Analysis
- **Objective**: To understand the daily device usage (PC vs. Mobile) among online customers.
- **Methodology**: Data was filtered for online purchases, and customers were counted based on the device used (PC or Mobile) on a daily basis. A pivot table was created to visualize daily customer counts by device category.
- **Findings**: The analysis revealed a shift in device preference over time, with mobile device usage increasing post-November 2018. Seasonal trends suggested higher mobile engagement during promotional periods.

### Purchase Frequency Analysis
- **Objective**: To analyze the frequency of purchases made by customers and identify patterns across different purchase channels.
- **Methodology**: The dataset was grouped by customer ID to calculate the number of purchases per customer. Additionally, a statistical test (two-sample t-test) was conducted to compare the average number of purchases across online and offline channels.
- **Findings**: Approximately 26.7% of customers returned for a second purchase. The statistical analysis suggested a significant difference in the average number of purchases between online and offline channels, with offline purchases being slightly higher on average.

### Hypotheses Testing
1. **Device Usage Equality**: Tested the null hypothesis that the mean number of daily online purchases is equal for PC and mobile users. The analysis led to rejecting the null hypothesis, indicating a significant difference in purchase behaviors between the two device types.
2. **Impact of Pop-Up Store Opening**: Evaluated the average number of PC and mobile users before and after the opening of the first pop-up store. The analysis showed no significant change for PC users but a significant difference for mobile users, indicating an increase in mobile engagement post-opening.

## Recommendations
- **Enhance Mobile Experience**: Given the increasing trend of mobile usage, IUIGA should focus on optimizing the mobile shopping experience to capture and retain this growing segment.
- **Promotional Strategies**: Seasonal promotions seem to resonate well with mobile users. Tailored promotions targeting mobile users could boost engagement and sales.
- **Customer Retention**: With a high churn rate observed, implementing loyalty programs or personalized marketing strategies could encourage repeat purchases and reduce churn.

## Tools and Technologies Used
- Python libraries: **Pandas** for data manipulation, **Matplotlib** for visualization, and **SciPy** for statistical testing.
- Google Colab Notebooks for interactive analysis and documentation.

## Conclusion
The case study provided valuable insights into customer purchase patterns and device usage at IUIGA. By leveraging these insights, IUIGA can better tailor its marketing strategies and technological enhancements to meet the evolving needs of its customer base, ultimately driving growth and customer satisfaction.


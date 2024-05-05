# Market-Campaign-Analysis

This project aims to analyze the effectiveness of two marketing campaigns, Facebook and AdWords, in terms of clicks, conversions, and cost. The analysis involves data cleaning, exploratory data analysis, hypothesis testing, regression analysis, and recommendations for optimizing advertising strategies.

## Objective

As a marketing agency, our primary goal is to maximize the return on investment (ROI) for our clients' advertising campaigns. We've conducted two ad campaigns—one on Facebook and the other on AdWords. Our aim is to determine which platform delivers superior results in terms of clicks, conversions, and overall cost-effectiveness. Identifying the most effective platform will enable us to allocate resources more efficiently and optimize our advertising strategies to achieve better outcomes for our clients.

## Key Features

The dataset comprises performance data for two separate advertising campaigns conducted throughout 2019. It includes the following key features:

- **Date:** The date corresponding to each campaign data row, ranging from January 1st to December 31st, 2019.
- **Ad Views:** The number of times the ad was viewed.
- **Ad Clicks:** The number of clicks received on the ad.
- **Ad Conversions:** The number of conversions resulting from the ad.
- **Cost per Ad:** The cost associated with running the Facebook ad campaign.
- **Click-Through Rate (CTR):** The ratio of clicks to views, indicating the ad's effectiveness in generating clicks.
- **Conversion Rate:** The ratio of conversions to clicks, reflecting the ad's effectiveness in driving desired actions.
- **Cost per Click (CPC):** The average cost incurred per click on the ad.

## Analysis Overview

The analysis includes the following steps:

1. **Data Cleaning:** Preprocessing the dataset to handle missing values and ensure data consistency.
2. **Exploratory Data Analysis (EDA):** Analyzing the distribution of clicks, conversions, and other metrics to understand campaign performance.
3. **Hypothesis Testing:** Testing whether Facebook advertising generates more conversions than AdWords advertising.
4. **Regression Analysis:** Establishing a predictive relationship between ad clicks and conversions to forecast expected conversion rates.
5. **Analyzing Campaign Metrics Over Time:** Examining monthly and weekly trends in conversions and Cost Per Conversion (CPC).
6. **Recommendations:** Providing actionable recommendations for optimizing advertising strategies based on the analysis results.

## Recommendations

Based on the analysis, the following recommendations are provided for optimizing advertising strategies:

1. Allocate More Resources to Facebook Advertising.
2. Optimize Facebook Ad Performance.
3. Consider Seasonal Trends and Timing.
4. Review AdWords Strategy.
5. Utilize Predictive Models for Planning.
6. Monitor CPC Trends and Adjust Spending.
7. Maintain Consistency in Engagement.
8. Long-term Strategy Based on Cost-Conversion Relationship.

## Conclusion

By implementing these recommendations, businesses can improve the overall effectiveness of their advertising campaigns, maximize conversions, and achieve better returns on investment.

## Dependencies

The project relies on the following Python libraries:
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn
- statsmodels

## How to Run

To replicate the analysis, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies using pip: `pip install -r requirements.txt`.
3. Run the Jupyter notebook `marketing_campaign_analysis.ipynb`.


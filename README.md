# A/B Testing Marketing Campaign: Facebook vs Google AdWords

## **Project Overview**

This project aims to compare the performance of two advertising channels, **Facebook Ads** and **Google AdWords**, to determine the more effective platform for our marketing strategy. Using data collected from both platforms over a year (2019), we analyze key performance indicators (KPIs) such as Ad Views, Clicks, Conversions, and Cost metrics to evaluate the **Return on Investment (ROI)** for each platform. The main approach employed is **A/B testing** to evaluate the advertising effectiveness.

## **Data Description**

The dataset used in this analysis includes daily records of the advertising campaigns conducted on Facebook and Google AdWords throughout 2019. The data comprises 365 rows, one for each day of the year, and includes the following features:

- **Date**: Date of the ad performance data (January 1st, 2019 - December 31st, 2019)
- **Ad Views**: The number of times the ad was viewed on the platform
- **Ad Clicks**: The number of clicks received on the ad
- **Ad Conversions**: The number of conversions resulting from the ad
- **Cost per Ad**: The cost of running the ad campaign
- **Click-Through Rate (CTR)**: The ratio of clicks to views, representing the ad’s effectiveness in generating clicks
- **Conversion Rate**: The ratio of conversions to clicks, reflecting the ad’s ability to drive desired actions
- **Cost per Click (CPC)**: The average cost incurred per click

## **Libraries Used**

This project utilizes various Python libraries for data analysis, visualization, and statistical testing:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `scipy.stats` for statistical testing
- `sklearn.linear_model` for regression analysis
- `statsmodels` for time series analysis and statistical modeling

## **Key Analysis Steps**

1. **Exploratory Data Analysis (EDA)**:
   - Visualizing ad performance metrics (Ad Views, Clicks, Conversions) over time.
   - Comparing the distribution of key metrics between the two platforms.

2. **Statistical Tests**:
   - Conducting **A/B testing** to compare the effectiveness of Facebook Ads vs Google AdWords using KPIs like Click-Through Rate (CTR), Conversion Rate, and Cost per Click (CPC).
   - Applying hypothesis testing (e.g., t-tests) to determine if the differences in performance are statistically significant.

3. **Regression Analysis**:
   - Performing regression analysis to understand the relationship between ad spending and conversion metrics.

4. **Time Series Analysis**:
   - Analyzing seasonal patterns in ad performance using time series decomposition.


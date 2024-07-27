# Ecommerce Linear Regression Project

## Overview
This project involves a linear regression analysis for an e-commerce company based in New York City. The company sells clothing online and offers in-store style advice sessions[^1^][1]. The goal is to determine whether to focus on improving the mobile app experience or the website based on customer data[^2^][2].

## Dataset
The dataset includes the following columns:
- **Email**: Customer's email address
- **Address**: Customer's physical address
- **Avatar**: Customer's avatar color
- **Avg. Session Length**: Average session length of in-store style advice sessions[^3^][3]
- **Time on App**: Average time spent on the mobile app in minutes[^4^][4]
- **Time on Website**: Average time spent on the website in minutes
- **Length of Membership**: Number of years the customer has been a member
- **Yearly Amount Spent**: Total amount spent by the customer in a year

## Analysis
The analysis includes:
1. **Exploratory Data Analysis (EDA)**: Visualizing relationships between features using seaborn plots.
2. **Linear Regression Model**: Training and testing a linear regression model to predict yearly amount spent based on other features.
3. **Model Evaluation**: Evaluating the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Results
- **Coefficients**:
  - Avg. Session Length: 25.98
  - Time on App: 38.59
  - Time on Website: 0.19
  - Length of Membership: 61.27

## Conclusion
Based on the coefficients, the company should focus more on improving the mobile app experience as it has a higher impact on the yearly amount spent compared to the website.

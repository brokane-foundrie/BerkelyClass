This project analyzes coupon acceptance rates based on driver behavior and passenger characteristics. Using a dataset that contains driver attributes, destinations, and coupon types, the project aims to understand which groups of drivers are more likely to accept certain types of coupons, specifically bar and restaurant-related coupons.

The analysis includes:
- Calculating acceptance rates for specific groups of drivers.
- Exploring factors such as age, driving destination, income, marital status, and bar visit frequency.
- Visualizing acceptance trends and patterns.
  
Dataset:
The dataset used in this project contains information about drivers, their destinations, and coupon offers. Some key attributes include:

- User Attributes: Age, gender, marital status, income, education, occupation, and the number of children.
- Contextual Attributes: Driving destination (home, work, or no urgent destination), weather, and passengers.
- Coupon Attributes: Time until expiration and coupon type (Bar, Restaurant, Takeaway, etc.).

Analysis Approach:
The primary goal of this analysis was to explore the acceptance of bar coupons and other types of coupons by analyzing user demographics and driving behavior. The following steps were taken:

Data Preprocessing:
- Handle missing values and prepare the data for analysis.
- Categorize drivers based on their coupon acceptance behavior.
  
Exploratory Data Analysis:
- Calculate acceptance rates for various demographic groups (age, income, marital status).
- Compare the acceptance rates of different coupon types.

Grouping and Filtering:
- Group drivers based on bar visit frequency, age, passenger type, and occupation.
- Calculate and compare acceptance rates across these groups.

Visualization:
- Visualize the acceptance rates using bar plots and count plots.

Key Findings

- Frequent Bar-Goers: Drivers who visit bars more than once a month are more likely to accept bar coupons.
- Age Factor: Younger drivers, especially those under 30, are more receptive to coupons.
- Passenger Impact: Drivers with passengers who are not children are more likely to accept coupons.
- Income Sensitivity: Drivers with incomes below $50,000 are more likely to accept certain coupons.
- Driving Destination: Drivers with no urgent destination show a higher tendency to accept coupons, compared to those heading to work or home.

This project requires the following Python libraries:

- pandas
- matplotlib
- seaborn
- numpy
- upyter

# Conclusion and insights

## Data Overview
* The dataset encompasses user behavior related to mobile phones, including attributes such as device model, operating system, app usage time, screen on time, battery drain, number of apps installed, data usage, age, and gender.

* The dataset consists of 700 rows and 9 columns after dropping unnecessary columns like 'User ID' and 'User Behavior Class'.

## Data Types and Composition

* The dataset contains three data types: float64, int64, and object.

* The data shows 3 continuous features with more than 90 unique values.

## Gender Distribution
* Gender Count: The majority of the dataset consists of male users (364) compared to female users (336).
## Operating System Distribution
* Operating System Count: A significant number of users are on Android (554), while the remaining are on iOS.
## Device Model Distribution
* Device Model Count: The most commonly used devices are Xiaomi Mi 11 and iPhone 12, each with 146 users.
## Visualizations

## Count Plots
* Gender: The count plot indicates a nearly even distribution between male and female users, with a slight male majority.

* Operating System: The majority of the users are using Android devices.

* Device Model: Xiaomi Mi 11 and iPhone 12 are the most popular devices among the users.

## Scatter Plots
* App Usage Time vs. Screen On Time: A positive correlation is observed. As the screen on time increases, app usage time also increases.

* App Usage Time vs. Battery Drain: Another positive correlation where increased app usage time results in higher battery drain.

* App Usage Time vs. Number of Apps Installed: There is a positive correlation indicating that higher app usage time correlates with a higher number of installed apps.

* App Usage Time vs. Data Usage: The data shows a positive correlation, with increased app usage time leading to higher data consumption.

## Histograms
* The histograms for continuous features show that:

* App usage time is right-skewed, indicating most users spend less time on apps daily.

* Screen on time is also right-skewed, reflecting similar usage patterns as app usage time.

* Battery drain distribution appears symmetric, suggesting uniform battery consumption across users.

* Data usage is right-skewed, indicating that most users consume less data daily.

## Box Plots
* App Usage Time: Right-skewed distribution with no outliers.

* Screen On Time: Right-skewed distribution with no outliers.

* Battery Drain: Symmetrical distribution with no outliers.

* Data Usage: Right-skewed distribution with no outliers.

## Heatmap
* The heatmap indicates that age does not correlate significantly with any of the other attributes.
Positive correlations are observed between:

* App usage time and screen on time.

* App usage time and battery drain.

*App usage time and data usage.

# 📱 Mobile App User Engagement Analysis

## 📌 Project Overview

This project analyzes user behavior from a mobile application dataset containing
20,000 users and 15 user-level attributes.

The objective is to understand how users interact with the application,
identify engagement patterns, examine churn risk, and generate
business-oriented insights that can support product, marketing and
customer-retention decisions.

---

## 🎯 Business Questions

The analysis answers the following questions:

1. What is the average session duration by device type?
2. Which app versions have the highest number of users?
3. Which countries have the highest user engagement?
4. How does churn risk vary across subscription types?
5. Which age groups are the most active?
6. What percentage of users are Free, Trial and Premium?
7. How frequently do users interact with push notifications?
8. How does user login activity change over time?

---

## 📊 Dataset

The dataset contains 20,000 users and 15 original columns.

Key attributes include:

- User ID
- Gender
- Age
- Country
- Device Type
- App Version
- Sessions Per Day
- Average Session Duration
- Screens Viewed
- Push Notifications Clicked
- In-App Purchases
- Subscription Status
- Churn Risk Score
- Last Login Date
- User Rating

---

## 🧮 Feature Engineering

A custom Engagement Score was created:

Engagement Score =
    Sessions Per Day × Avg Session Duration
    + Screens Viewed × 0.5
    + In-App Purchases × 2

This score combines multiple behavioral indicators into a single
engagement metric.

---

## 🔎 Analysis Performed

### 1. Device Analysis
Compared average session duration between Android and iOS users.

### 2. App Version Analysis
Measured user adoption across application versions.

### 3. Geographic Analysis
Compared average sessions per day across countries.

### 4. Churn Analysis
Examined churn-risk-score distributions across Free, Trial and Premium users.

### 5. Age Analysis
Created age groups and compared their average sessions per day.

### 6. Subscription Analysis
Measured the distribution of Free, Trial and Premium users.

### 7. Push Notification Analysis
Analyzed the distribution of notification clicks.

### 8. Time-Series Analysis
Converted login dates into monthly periods and analyzed login activity.

---

## 📈 Key Findings

- Android average session duration: ~30.57 minutes
- iOS average session duration: ~30.33 minutes
- USA has the highest average sessions per day: ~7.53
- 35–44 age group has the highest average sessions per day: ~7.60
- Premium users represent ~33.84% of the user base
- Free users represent ~33.26%
- Trial users represent ~32.90%
- App Version 1.2 has the highest user count
- Churn risk distributions are broadly similar across subscription types
- Average user rating is approximately 3/5

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Visualizations

The project includes visualizations for:

- Key User Engagement Metrics
- Average Session Duration by Device
- User Count by App Version
- Average Sessions Per Day by Country
- Churn Risk by Subscription Type
- Average Sessions Per Day by Age Group
- Subscription Distribution
- Push Notification Interactions
- Monthly User Logins

---

## 💡 Business Recommendations

- Develop behavior-based user segmentation.
- Improve Free-to-Premium conversion strategies.
- Use targeted retention campaigns for high-risk users.
- A/B test push notification strategies.
- Investigate low user-rating segments.
- Monitor app-version adoption and migration.
- Use engagement metrics to prioritize product improvements.

---

## 👨‍💻 Author

**Durgesh Yadav**

Data Analyst | Python | SQL | Power BI | Excel | Data Analytics

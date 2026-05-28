# Customer Retention & Churn Analysis (Subscription Business)

## 📌 Project Overview
This project focuses on analyzing customer data for a subscription-based business to discover churn patterns, lifecycle trends, and key drivers behind customer drop-offs. Using cohort analysis, we track user groups over time to evaluate long-term retention dynamics.

### 📊 Key Metrics Tracked
* **Overall Churn Rate**: The percentage of customers who discontinued their subscriptions within the timeframe.
* **Retention Rate Matrix**: Chronological tracking of cohort performance over a 12-month tenure cycle.
* **High-Risk Segment Tracking**: Analyzing churn trends mapped against specific subscription tier structures.

---

## 🛠️ Tech Stack & Libraries
* **Language**: Python 3.x
* **Data Manipulation**: `pandas`, `numpy`
* **Visualization Matrix**: `seaborn`, `matplotlib`

---

## 🚀 Implementation Workflow

### 1. Data Preparation
* Simulated a realistic 500+ subscriber dataset tracking `Signup_Date`, `Subscription_Type`, `Monthly_Charges`, and `Tenure_Months`.
* Structured user metrics to isolate active accounts from churned accounts based on historical milestones.

### 2. Analytical Code Implementation
The underlying analysis runs systematically inside python notebooks using the following execution loops:
* Aggregating global churn rates dynamically.
* Re-pivoting transactional tables into a dedicated monthly lifecycle cohort matrix.
* Generating a color-coded retention heatmap visualization.

---

## 📈 Key Insights & Strategic Recommendations
* **The 3rd Month Drop**: The generated retention cohort heatmap highlights a massive user drop-off exactly at month 3. This points directly to onboarding friction or trial expiration barriers.
* **Tier Variation**: Basic Tier plan subscribers exhibit significantly higher churn rates compared to Premium tier alternatives.
* **Action Plan**:
  1. Trigger structured automated email re-engagement flows at Day 60 to buffer the Month 3 drop.
  2. Redesign the value proposition of the Basic Plan to extend the customer lifetime loop.

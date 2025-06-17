# 🎯 Lead Conversion Prediction - ExtraaLearn

## 📘 Project Overview

This project involves building a **machine learning model** to predict lead conversion for an EdTech startup, **ExtraaLearn**. The company aims to identify leads most likely to convert into paying customers so they can allocate sales and marketing resources more efficiently.

## 🌐 Context

The global EdTech market has been growing rapidly, forecasted to reach **$286.62B by 2023**, with a **CAGR of 10.26%** from 2018–2023. This growth has been further accelerated by the COVID-19 pandemic, which pushed educational institutions and learners toward online platforms. As new EdTech players emerge and leverage digital marketing, efficient **lead qualification and conversion prediction** become essential.

Leads can come from:
- Social media or online ads
- Website/app visits and brochure downloads
- Email or referral interactions

The challenge is to **predict which leads are likely to convert**, allowing ExtraaLearn to optimize resource allocation and conversion strategies.

## 🎯 Objective

As a data scientist at ExtraaLearn, you are tasked to:
- Build a model to predict the likelihood of lead conversion
- Analyze key drivers behind successful lead conversions
- Develop actionable recommendations to improve business performance

## 🧾 Dataset Description

The dataset contains information on user demographics, engagement behavior, and marketing interaction channels.

### Key Features:
- `age`: Age of the lead
- `current_occupation`: Professional, Student, or Unemployed
- `first_interaction`: Channel of first contact (Website or Mobile App)
- `profile_completed`: Percentage of profile completion (Low, Medium, High)
- `website_visits`, `time_spent_on_website`, `page_views_per_visit`
- `last_activity`: Type of last interaction (Email, Phone, Website)
- `print_media_type1/2`, `digital_media`, `referral`, `educational_channels`: Marketing exposure
- `status`: Target variable (Converted or Not)

## 🔍 Insights & Analysis

### 🧑‍💼 Lead Demographics
- **Professionals** form the largest group and have the **highest conversion rate**
- **Unemployed leads** show a strong conversion rate despite fewer leads
- **Students** are the most common but convert the least

### 💻 Engagement & Behavior
- **Website users** convert significantly more than **mobile app** users
- **High profile completion** leads have the best conversion probability
- **Website activity** as the last interaction performs best; phone activity underperforms

### 📈 Marketing Channel Insights
- **Referrals** generate the **highest conversion rate**
- **Digital and print media** show promise despite lower reach
- **Educational channels** underperform

### 🔢 Numerical Variables
- More **website visits** and **time spent** correlate strongly with conversion
- **Page views per visit** is less predictive

## 🤖 Machine Learning Models

Built and compared multiple models:
- **Decision Tree**
- **Random Forest** (Best performance)

### Key Predictive Features (Random Forest):
- `first_interaction_website`
- `time_spent_on_website`
- `profile_completed`
- `age`
- `last_activity`
- `current_occupation`

The model can now be used to **score leads daily**, helping sales teams prioritize the most promising prospects.

## 💼 Business Recommendations

### 1. Lead Prioritization
- Focus on **professionals** and **unemployed leads** from the **website channel**
- Target those with **medium or high profile completion**

### 2. Marketing & Channel Strategy
- Enhance and promote **referral programs**
- Optimize the **mobile app** experience
- Monitor and expand **print/digital media** based on performance

### 3. Profile Completion Strategy
- Incentivize completion (rewards, unlockables)
- Improve UX, show completion progress
- Send reminder emails or helpful tips

### 4. Communication Optimization
- Continue nurturing through **email**, supported by website tools (e.g., **live chat**)
- Reduce reliance on cold calling unless paired with contextual personalization

### 5. Predictive Analytics & Automation
- Deploy the ML model to **score leads in real-time**
- Allocate human resources to **top-ranked leads**

## 🛠️ Tools & Technologies

- **Python**: pandas, NumPy, matplotlib, seaborn, scikit-learn
- **ML Models**: Decision Tree, Random Forest
- **Jupyter Notebook** for exploration and model training

## 📌 Conclusion

The ML-driven lead scoring solution helps ExtraaLearn:
- Improve conversion rates
- Optimize marketing spend
- Reduce wasted sales efforts

This approach provides **data-driven insights** for building a more effective lead conversion pipeline in the growing EdTech industry.

## 📄 License

This project is for educational and research purposes.

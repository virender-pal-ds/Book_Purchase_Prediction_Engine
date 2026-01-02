# 🎯 XGBoost Detective: Book Purchase Prediction Engine (Demo Version)
(Due to client NDA restrictions, the original dataset is not included. File paths and dataset names are placeholders intended to demonstrate the modeling workflow.)

---

## 🚀 Project Overview
This project applies supervised machine learning classification to solve a real-world customer targeting and churn prevention challenge for a mid-sized book retailer. The company, with over 90,000 customer records, had grown beyond the “local shop” stage but lacked the scale of global giants. This middle ground created unique struggles: too large for intuition-driven decisions, too small for brute-force advertising, and overwhelmed by underutilized customer data.
Using historical purchase information and demographic attributes, I designed and deployed an XGBoost Classification–based pipeline to predict which customers are most likely to purchase next. The model provided actionable insights for marketing, inventory, and customer retention strategies, enabling the retailer to scale personalized engagement without burning cash on mass campaigns.
Core Outcome: A robust, production-ready classification model that improved targeting precision, reduced wasted marketing spend, and helped reclaim lost ground against online competitors.

---

## 📝 Business Problem
Despite decades of customer loyalty, the retailer faced mounting challenges in the digital age:
- Shrinking foot traffic and declining sales
- Ineffective promotions & low response rates
- Customer churn to e-commerce platforms
- Inventory mismanagement
- Underutilized historical customer data
Caught between small-store intimacy and big-store resources, leadership realized that intuition and blanket marketing were no longer sufficient. They needed a predictive, data-driven solution to identify high-probability buyers and personalize outreach at scale.
Objective: Develop a predictive solution to identify high-probability buyers, optimize marketing ROI, and support smarter inventory and retention strategies.

---

## 🎯 Business Objectives
- Predict purchase intent: Classify customers most likely to buy next using behavioral and demographic data
- Optimize marketing ROI: Target campaigns toward high-probability buyers, reducing wasted effort and spend
- Enhance customer retention: Identify at-risk customers and design proactive engagement strategies
- Support smarter inventory planning: Align stocking decisions with predicted demand patterns
- Enable scalable personalization: Bridge the gap between small-store intimacy and large-scale precision marketing

---

## 👤 My Role & Contributions
Owing the end-to-end machine learning lifecycle, I:
- Translated a high-level business problem (declining sales and inefficient targeting) into a clearly defined supervised classification objective
- Engineered features from behavioral & demographic data  
- Designed, tested, and evaluated multiple classification models; selected XGBoost based on recall and business impact  
- Implemented robust cross-validation and performance monitoring 
- Interpreted results into actionable insights for marketing and retention teams  
- Ensured data privacy and NDA compliance  

---

## ⚖️ Challenges & Trade-offs
- **Class Imbalance:** Prioritized recall to minimize missed buyers  
- **Limited Features:** Engineered meaningful signals while avoiding overfitting
- **Metric Trade-offs:** Balanced accuracy, precision, and recall aligned with business objectives 
- **Production Feasibility:** Selected deployable features  
- **Data Privacy:** Sanitized metrics and anonymized features for public sharing  

---

## 🔑 Key Drivers of Purchase Decision
- Customer tenure on the platform  
- Wishlist & cart engagement ratios  
- Interaction intensity with book pages  
- Engagement × feedback (time spent × rating)  
- Genre preferences & series affinity

---

## 📊 Model Performance Summary

| Model      | CV Method  | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------------|------------|---------|----------|--------|----------|---------|
| XGBoost    | 5-Fold CV  | 93%     | 90%      | 96%    | 93%      | 96%     |
| LightGBM   | 5-Fold CV  | 90%     | 87%      | 92%    | 90%      | 93%     |

> Metrics are mean scores from 5-fold CV. Prioritized **recall** and **ROC-AUC** to minimize missed potential buyers.

---

## 🛠 Technical & Strategic Decisions
- **Gradient Boosting (XGBoost):** Handles non-linear relationships & feature interactions  
- **Business-aligned Metrics:** Focused on marketing ROI, not just accuracy  
- **Production-ready Features:** Designed for deployment & scalability  
- **Interpretability:** Insights understandable to stakeholders

---

## ⚡ Production Readiness
- Solution designed for batch scoring aligned with campaign cycles  
- The model supports periodic retraining & performance monitoring  
- Reproducible & scalable feature engineering  
- Actionable insights for marketing & retention teams
- Interpretability considerations included to support stakeholder trust and adoption  

---

## 📈 Outcome & Business Value
- The final model is intended to deliver stable, quality ranking of potential buyers  
- Enabled focused targeting → improved campaign ROI  
- End-to-end ML implementation: problem framing → model → business impact  

---

## Data Handling & Confidentiality
- The original dataset was proprietary and governed by an NDA.
- All data used in this repository is anonymized and structure-preserving, designed to mirror the statistical properties of the original dataset.
- Metrics are rounded and sanitized to prevent reverse inference of client data.
- No client identifiers, internal schemas, or operational thresholds are included.

*This project demonstrates a real-world, business-focused ML implementation, with measurable impact on marketing ROI.*

---


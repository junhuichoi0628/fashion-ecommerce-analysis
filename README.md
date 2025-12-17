# Fashion E-commerce Revenue Decline Analysis

Root cause analysis of abnormal revenue decline using transactional and clickstream data  
(Indonesia Fashion E-commerce Mobile App)

---

## 1. Project Overview
This project investigates the root causes behind an **unexpected and sustained revenue decline** observed in an Indonesia-based fashion e-commerce mobile application.

Despite July typically being a **peak season** for fashion e-commerce, the platform experienced **three consecutive months of revenue contraction (May–July 2022)**.  
The objective of this analysis is to identify **structural issues**, rather than seasonal effects, and to derive **actionable, data-driven business recommendations**.

---

## 2. Business Problem
The platform showed:
- Continuous month-over-month revenue decline
- Revenue decrease during a historically strong seasonal period
- Signs of growth stagnation despite prior upward trends

**Key Questions**
- Which metrics drove the revenue decline?
- Was the decline caused by traffic, conversion behavior, or pricing?
- Where in the customer journey did users drop off?
- What actions can recover sustainable growth?

---

## 3. Data Source
This analysis is based on a public transactional e-commerce dataset.

- **Source**: Kaggle – Transactional E-commerce Dataset  
- **URL**: https://www.kaggle.com/datasets/bytadit/transactional-ecommerce  
- **Region**: Indonesia  
- **Period**: Jun 2016 – Jul 2022  

### Data Components
- Customer information  
- Product metadata  
- Transaction records  
- Clickstream and event-level logs  

The dataset enables end-to-end analysis of user behavior from visit to purchase.

---

## 4. Analytical Framework

### Revenue Decomposition
Revenue was decomposed into three core drivers:

> **Revenue = Traffic × Conversion Rate (CVR) × Average Order Value (AOV)**

This framework allows isolation of whether revenue changes are driven by:
- User volume (Traffic)
- Purchase behavior (CVR)
- Pricing and basket size (AOV)

### Key Methods
- Monthly time-series growth analysis
- Traffic segmentation by device and user type
- Funnel-based conversion analysis using event sequences

---

## 5. Key Findings

### 1) Revenue Decline Structure
- Traffic decline acted as the **leading indicator**
- Conversion rate deterioration **amplified** the revenue drop
- AOV remained relatively stable → pricing was not the issue

### 2) Traffic Analysis
- Traffic loss was **highly concentrated among Android users**
- iOS traffic remained relatively stable
- Returning users were more affected than new users

### 3) Funnel Bottleneck
- The largest drop-off occurred at the **Explore → Intent** stage
- Drop-off rate reached approximately **31.1%**
- Users browsed products but failed to transition into purchase intent

---

## 6. Business Implications & Recommendations

### Traffic Recovery
- Review Android app update history during the affected period
- Strengthen OS- and device-level compatibility testing
- Improve performance monitoring and rapid patch deployment

### Conversion Improvement (Mid-Funnel)
- Optimize search relevance, filtering, and ranking logic
- Enhance personalized product recommendations
- Improve product detail pages (images, reviews, sizing, delivery clarity)

### Marketing Focus
- Retarget users who exited after the exploration stage
- Shift focus from acquisition to mid-funnel recovery

---

## 7. Tools & Environment
- **Environment**: Google Colab  
- **Languages & Libraries**:
  - Python
  - Pandas, NumPy
  - Matplotlib
  - ast, datetime

---

## 8. Related Links
- 📊 Project Slides (Google Slides):  
  https://docs.google.com/presentation/d/e/2PACX-1vSmr9woxhArPnIb24Qx6qokWVeffNFRsu8Njh0arcWgc6RxywTcZ8D_pR_qbPry8Ot5lp0O440kE4m9/pub

- 🌐 Portfolio Website:  
  https://junhuichoi.github.io

---

## 9. Business Value
- Identified structural causes behind abnormal revenue decline
- Delivered prioritized, data-backed recommendations
- Established a reusable KPI and funnel monitoring framework
- Insights directly applicable to product, marketing, and engineering teams


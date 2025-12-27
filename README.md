# 🎓 College Compass  
### AI-Powered College Guidance for Social Mobility  
Built for the **2025 UC Berkeley Datathon**

---

## 📌 Overview

**College Compass** is a Streamlit application designed to help students—especially those from underrepresented minority groups—identify colleges that maximize **social mobility**, **affordability**, and **equitable outcomes**.

Using the **College Results dataset (2021)** and the **Affordability Gap dataset (2022–23)**, the app evaluates institutions on four core metrics:

- **Earnings Score** – 10-year post-graduation median salary  
- **Net Price Score** – student cost after grants and aid  
- **Debt Burden** – median student debt and repayment outcomes  
- **Equity Score** – graduation gaps for Black and Latino students  

We also trained a **k-means clustering model** to group colleges into intuitive “types” such as:

- *Budget-Friendly Colleges*  
- *High ROI but Expensive Institutions*  
- *Low-Value Institutions*  
- *Mid-Value Colleges*  

---

## 🧠 Features

### 💬 Chatbot-style Advisor  
Users interact with a virtual advising assistant that collects background information and priorities:
- Budget  
- Ethnic background considerations  
- Earnings vs. affordability preferences  
- Equity and campus support needs  

The system generates **weighted recommendations** based on the user's goals.

---

### 📊 Tableau Dashboard Integration  
Our dashboard includes:

- **Net Price vs. Earnings Scatterplot**  
- **Equity Gap Bar Chart** (Graduation rates for overall, Black, and Latino students)  
- **Cluster Visualization** of college types  
- Interactive school tooltips with key metrics

This allows users to visually compare institutions and understand trade-offs.

---

### 🎯 Personalized Recommendations  
The app creates a ranked list of colleges with:
- School name  
- Equity, earnings, and cost scores  
- Cluster type  
- Summary of strengths  
- Click-through for more details

---

## 🛠️ Tech Stack

| Component | Tools Used |
|----------|------------|
| Backend | Python, pandas, numpy |
| Web App | Streamlit |
| ML | scikit-learn (k-means clustering) |
| Visualization | Tableau |
| Version Control | GitHub |

---

## 🚀 Getting Started

### 1. Install Dependencies  
```bash
pip install streamlit pandas numpy scikit-learn
```
### 2. Run the App
```bash
streamlit run app.py


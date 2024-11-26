
---

# **Depression and Lifestyle Analysis**

**Project Overview**:  
This project explores the relationship between lifestyle factors and depression among professionals. The dataset contains information on various attributes such as **Gender**, **Sleep Duration**, **Dietary Habits**, **Family History of Mental Illness**, and **Depression Status**. The analysis focuses on identifying patterns, visualizing trends, and deriving insights.

---

## **Dataset Overview**  
- **Total Rows**: 1,000 (example)
- **Total Columns**: 12  
- **Key Features**:
  - Gender
  - Sleep Duration
  - Dietary Habits
  - Family History of Mental Illness
  - Depression Status

---

## **Data Cleaning and Transformation**  
Key steps performed:
- **Dropped rows with null values** in key columns.
- **Mapped Sleep Duration** to numeric values for better analysis.
- **Created a new feature**: **Sleep Category**, with levels: **Very Low**, **Low**, **Moderate**, **High**.
- **Categorical Data Standardization** was performed on columns such as **Gender**, **Sleep Duration**, and **Dietary Habits**.

---

## **Key Insights**  

### **3.1 Sleep Duration and Depression**  
- **Short Sleepers (<5 hours)**: Highest depression rates (~14.67%).
- **Long Sleepers (>9 hours)**: Lowest depression rates (~6.88%).
- A **balanced sleep duration** (5–9 hours) is associated with moderate effects on depression (~10.42%).

### **3.2 Dietary Habits and Depression**  
- **Healthy Diet**: Low depression rates (~6.75%).
- **Unhealthy Diet**: High depression rates (~13.74%).
- **Moderate eaters** fall in between, highlighting the importance of dietary balance.

### **3.3 Family History of Mental Illness and Depression**  
- **Yes**: Higher likelihood of depression (~10.42%).
- **No**: Lower likelihood of depression (~9.37%).

---

## **Visualizations**  

### **4.1 Sleep Duration vs Depression**  
A **boxplot** demonstrates the variation of sleep hours by depression status.

### **4.2 Dietary Habits vs Depression**  
- **Count plot** shows the distribution of dietary habits by depression status.
- **Pie chart** for the proportion of depression in each dietary category.

---

## **Summary of Findings**  

- **Gender**: Male and Female professionals show similar depression trends (~10% affected).
- **Sleep**: Short sleepers (<5 hours) and long sleepers (>9 hours) exhibit extreme depression rates, while balanced sleep duration has moderate effects.
- **Dietary Habits**: Unhealthy eaters are significantly more likely to suffer from depression.

---

## **Lifestyle Factors**  
A combination of healthy sleep, diet, and no family history of mental illness reduces depression risks.

---

## **Future Work**  
Explore additional lifestyle factors like physical activity and stress management. Use machine learning models to predict depression trends based on lifestyle factors.

---

## **Dataset Source**  
The dataset for this project was obtained from Kaggle:  
[**Depression Professional Dataset**](https://www.kaggle.com)

---


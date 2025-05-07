# 🍔 McDonald's Menu Nutritional Facts – Data Analysis Project
## 📌 Project Description
This project explores the nutritional composition of items on the McDonald's menu using a dataset that includes macro and micronutrient data for various food categories. The goal is to analyze trends in calorie content, sugar, fat, and other nutritional components to provide insights into food choices and health impacts.
Whether you're a nutritionist, a data enthusiast, or a consumer looking to make healthier choices, this project provides a deep dive into what goes into some of the world’s most consumed fast food.

---

## 🎯 Objectives
- Perform **exploratory data analysis (EDA)** on McDonald's nutritional data.
- Identify high and low-calorie items across categories.
- Visualize and compare key nutrients such as:
  - Calories
  - Protein
  - Total Fat
  - Saturated Fat
  - Carbohydrates
  - Sugar
  - Sodium
- Detect correlations between nutrients and portion sizes.
- Segment and compare different menu item types (e.g., burgers vs. salads vs. drinks).

---

## 🗂️ Dataset Overview
The dataset contains nutritional facts for various McDonald's menu items and includes:
- **Category**: Food type (e.g., Beverage, Burger, Salad)
- **Serving Size**
- **Calories**
- **Total Fat**, **Saturated Fat**
- **Cholesterol**
- **Sodium**
- **Carbohydrates**, **Sugars**, **Dietary Fiber**
- **Protein**
- **Vitamin and Mineral content** (optional/varied)

---

## 📦 Libraries Used
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px
import warnings
warnings.filterwarnings('ignore')
```

---

## 📊 Key Analysis Tasks
- Overview and structure of the dataset
- Checking for missing values and data cleaning
- Summary statistics for nutrients
- Category-wise comparisons using bar plots and box plots
- Nutrient distribution histograms
- Heatmap of correlations among nutritional variables
- Interactive visualizations using Plotly

---

## 🧠 Insights & Outcomes
- Identify the highest-calorie and lowest-calorie menu items.
- Find nutrient-dense items that offer better protein-to-calorie ratios.
- Understand which categories (e.g., Drinks, Desserts) contribute the most to sugar or fat intake.
- Help users make more informed dietary choices when eating at McDonald’s.

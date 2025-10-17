# EDA-California-Housing-
Data analysis project exploring California housing trends through data cleaning, visualization, and statistical insights — a foundation for predictive modeling.
# 🏡 California Housing Dataset - Exploratory Data Analysis (EDA)

This project involves a detailed **Exploratory Data Analysis (EDA)** of the **California Housing Dataset** to uncover insights about housing prices, demographics, and geographical patterns across different regions of California.

The goal is to **clean, analyze, and visualize** the dataset to identify key factors affecting housing prices and build a strong foundation for future predictive modeling.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Key Steps](#key-steps)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Future Work](#future-work)
- [How to Run](#how-to-run)
- [Author](#author)

---

## 📝 Project Overview

The **California Housing Dataset** contains information on housing prices and demographics for various districts in California.  
The analysis focuses on:
- Understanding the distribution and structure of the dataset.
- Cleaning and preprocessing data (missing values, outliers, categorical variables).
- Performing **univariate**, **bivariate**, and **multivariate** analysis.
- Deriving **geographical and socio-economic insights** related to house values.

---

## 🧾 Dataset

- **Dataset Name:** California Housing Dataset  
- **Number of Records:** 20,640  
- **Number of Features:** 10  
- **Source:** Scikit-learn's built-in California housing dataset

| Feature | Description |
|---------|-------------|
| longitude | Longitude coordinate |
| latitude | Latitude coordinate |
| housing_median_age | Median age of houses in the district |
| total_rooms | Total number of rooms |
| total_bedrooms | Total number of bedrooms |
| population | District population |
| households | Number of households |
| median_income | Median income in the district |
| median_house_value | Median house value in the district |
| ocean_proximity | Proximity to the ocean (categorical) |

---

## 🧠 Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **IDE/Tools:** Jupyter Notebook / VS Code

---

## 🔍 Key Steps

1. **Data Cleaning**
   - Handled missing values (`total_bedrooms`) using median imputation.
   - Fixed categorical inconsistencies and standardized data types.

2. **Outlier Detection & Handling**
   - Detected outliers in `total_rooms`, `population`, and `households` using boxplots and IQR method.
   - Retained legitimate outliers to preserve real-world distribution.

3. **Univariate Analysis**
   - Histograms and KDE plots for understanding distributions.
   - Bar plots for categorical variables like `ocean_proximity`.

4. **Bivariate Analysis**
   - Scatter and regression plots between `median_income` and `median_house_value`.
   - Categorical vs numerical analysis using box, violin, and strip plots.

5. **Multivariate Analysis**
   - Scatter plots with hue to analyze 3 variables simultaneously.
   - Pair plots to identify relationships between income, age, and house value.

---

## 📊 Key Insights

- **Median Income** is the **strongest predictor** of median house value.  
- **Coastal areas** (Near Ocean / Bay) show **35–40% higher house values** compared to inland regions.  
- The **distribution of house values is right-skewed**, with a clear upper cap.  
- Outliers correspond to **high-density urban tracts** and were not removed to maintain dataset integrity.  
- **Geographical location** (latitude, longitude, ocean proximity) plays a significant role in price variation.

---

## 📈 Visualizations

The notebook contains multiple visualizations:
- Histograms & KDE plots for feature distributions  
- Box & Violin plots for categorical vs numerical analysis  
- Scatter & regression plots for numerical relationships  
- Pair plots for multivariate insights  
- Geographical scatter visualizations (latitude vs longitude vs price)

---

## 🚀 Future Work

- Build **regression models** to predict house values based on features.  
- Apply **feature engineering** (e.g., rooms per household, income per capita).  
- Perform **geospatial analysis** using libraries like `folium` or `plotly`.  
- Deploy interactive dashboards using **Streamlit** or **Power BI**.

---

## 🧠 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/california-housing-eda.git
   cd california-housing-eda
   👨‍💻 Author

Gundu Venkata Naga Sai Yaswanth
📧 gvnsyaswanth2002@gmail.com

🔗 LinkedIn
 | GitHub

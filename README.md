# 🌾 Sugarcane-EDA

This repository contains a Jupyter Notebook that performs **Exploratory Data Analysis (EDA)** on sugarcane production data across various countries. It leverages Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib** to uncover insights from the dataset:  
📄 **List of Countries by Sugarcane Production.csv**

---

## 📁 Dataset Overview

The dataset provides sugarcane production metrics for countries and continents worldwide. The columns include:

- **`Country`**: Name of the country  
- **`Continent`**: Continent to which the country belongs  
- **`Production(Tons)`**: Total sugarcane production (in tons)  
- **`Production_per_person(Kg)`**: Sugarcane production per person (in kg)  
- **`Acreage(Hectare)`**: Land area under sugarcane cultivation (in hectares)  
- **`Yield(Kg/Hectare)`**: Production yield per hectare (in kg)

---

## 🛠️ Tools Used

- Python 3.x  
- Pandas  
- Seaborn  
- Matplotlib  
- Jupyter Notebook

---

## 🧹 Data Cleaning

The notebook includes preprocessing steps to ensure data quality:

- Removal of special characters (e.g., commas, dots) from numerical fields  
- Conversion of columns to appropriate data types  
- Dropping irrelevant or empty rows  
- Suppression of harmless future warnings for clean output

---

## 📊 Exploratory Analysis

### 🔸 Univariate Analysis

Analyzes the distribution of individual features such as:
- Sugarcane production
- Yield
- Cultivation area

📌 Tools: Bar plots, distribution plots

---

### 🔸 Bivariate Analysis

Investigates relationships between variables:
- Acreage vs Production  
- Yield vs Production  
- Country-wise comparisons

📌 Tools: Scatter plots, bar plots

---

### 🔸 Correlation Matrix

Examines correlations between numerical variables using:
- Correlation heatmap (via Seaborn)

Insights include which factors most strongly influence total production.

---

## 🌍 Continental Analysis

Groups and analyzes data by **continent** to identify regional trends:
- Average and total production
- Yield performance by continent

📌 Tools: Grouped bar plots, line plots

---

## ✅ Conclusion

This analysis reveals key patterns in sugarcane production globally:
- High yield doesn’t always equate to high total production  
- Certain continents dominate in both cultivation and yield  
- Correlations between acreage, yield, and output offer strategic insights

The notebook serves as a foundation for agricultural production research or regional resource planning.

---

## 📎 Files

- `Sugarcane EDA.ipynb` – Main analysis notebook  
- `List of Countries by Sugarcane Production.csv` – Dataset used for analysis

---

## Contact

 📧 aishwaryasr097@gmail.com
 
 🔗 [LinkedIn](https://www.linkedin.com/in/aishwarya-sr/)
 






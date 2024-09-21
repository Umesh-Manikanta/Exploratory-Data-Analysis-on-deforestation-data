# Exploratory-Data-Analysis-on-deforestation-data
# 🌳 Deforestation Data Analysis


## 📚 Project Overview
This project focuses on analyzing **deforestation trends** across states and districts in **India** from **2001 to 2020**. By using a rich dataset and applying statistical and visualization techniques, we aim to provide insights that can help with **environmental conservation** and **policy planning**.

The goal is to:
- Detect regions with the **highest** and **lowest** deforestation rates.
- Highlight **afforestation** trends from **2000 to 2012**.
- Visualize the data for **key insights**.

---

## 🎯 Objectives
✨ **Key Focus Areas**:
1. **Data Cleaning & Preprocessing**: Handle missing data and detect outliers.
2. **Deforestation Analysis**:
   - Examine **deforestation trends** between 2001-2020.
   - Identify **states** and **districts** with the least and most deforestation.
3. **Afforestation Trends**: Analyze forest gain from 2000 to 2012.
4. **Visualization**: Present the findings using insightful plots and charts.

---

## 🛠️ Features
- **Data Cleaning**: Handle missing values and detect outliers using the **IQR method**.
- **Statistical Summary**: Detailed descriptions of the data including **means**, **medians**, and **data types**.
- **Visualization**: 
  - **📊 Bar Plots**: Showing deforestation by **state** and **district**.
  - **📈 Heatmaps**: Displaying **correlations** between yearly deforestation rates.
  - **📉 Histograms**: Distribution of **average deforestation** across regions.
- **Afforestation Trends**: Analyze the **gain of forest area** from 2000 to 2012.

---

## 🗃️ Dataset Description

The dataset contains annual deforestation data from **2001 to 2020**. It also includes data for **forest gain** from **2000 to 2012**. The key columns include:

- `subnational`: Represents **states** and **union territories**.
- `subnational2`: Represents the **districts** within the states.
- `extent_2000_ha` and `extent_2010_ha`: Deforestation extent in hectares for the respective years.
- `gain_2000-2012_ha`: Forest gain from **2000-2012**.

---

## 🔧 Data Preprocessing Steps
1. **Load Dataset**: The dataset is loaded from a **CSV file** using `pandas`.
2. **Handling Missing Data**: Missing values are filled with the **mean** value for the column.
3. **Outlier Detection**: Outliers are detected using the **Interquartile Range (IQR)** method.
   
---

## 📊 Key Metrics and Calculations

### 📌 **Average Deforestation**
A new column is added to the dataset, calculating the **average deforestation** from 2001 to 2020.

### 📌 **State-wise & District-wise Analysis**
States and districts are analyzed to determine:
- Regions with the **least** and **most** deforestation.
- Identification of peak deforestation **years**.

### 📌 **Afforestation Trends**
Analysis of the **gain of forest areas** from 2000 to 2012. States with the highest and lowest rates of **afforestation** are highlighted.

---

## 🔍 Insights & Findings

### 📍 **Highest Deforestation**
- **Mizoram** recorded the highest deforestation from 2001 to 2020, with the district **Champhai** experiencing the maximum loss.

### 📍 **Least Deforestation**
- **Lakshadweep** and **Daman and Diu** had the least deforestation in the same period.

### 📍 **Afforestation Trends**
- The state of **Manipur** saw the highest afforestation between 2000 and 2012, while **Meghalaya** saw the least.

---

## 🖼️ Visualizations

### 🗺️ **State-wise Deforestation Bar Plot**
![State-wise Deforestation](./assets/state-wise-deforestation.png)

### 📅 **Year-wise Deforestation Trend**
![Year-wise Deforestation](./assets/year-wise-deforestation.png)

### 🔥 **Heatmap of Correlations**
![Heatmap](./assets/heatmap-correlation.png)

---

## 🚀 How to Run the Project
1. **Clone** the repository:
    ```bash
    git clone https://github.com/Umesh-Manikanta/Exploratory-Data-Analysis-on-deforestation-data.git
    ```

2. **Install Dependencies**:
    ```bash
    pip install numpy pandas matplotlib seaborn
    ```

3. Place your `dataset.csv` file in the root directory.

4. **Run the analysis**:
    ```bash
    python analysis.py
    ```

---

## 💡 Future Enhancements
1. **Advanced Outlier Handling**: Incorporating methods to deal with outliers more effectively.
2. **Predictive Modeling**: Using **time-series forecasting** to predict future deforestation trends.
3. **Interactive Visualizations**: Implementing tools like **Plotly** or **Dash** for more interactive data exploration.
4. **Machine Learning Models**: Use ML models to predict regions at risk of deforestation.


---

## 🎨 Credits
- **Icons and images** used in this project were designed for better readability and presentation. You can replace placeholders (`./assets/`) with actual paths to your images.

# Data-Cleaning-and-Preprocessing
This project demonstrates a beginner-level data cleaning and preprocessing pipeline using global COVID-19 data from Our World in Data. The project focuses on selecting relevant data, handling missing values, and preparing the dataset for future analysis.

# 🌍 COVID-19 Data Cleaning and Preprocessing Pipeline

This project demonstrates a beginner-level **data cleaning and preprocessing pipeline** using global COVID-19 data from [Our World in Data](https://ourworldindata.org/coronavirus). The goal was to select relevant information, clean the dataset, and prepare it for further analysis or visualization.

---

## 🔧 Steps Taken

1. **Imported and inspected the dataset** containing over 490,000 rows and 61 columns.
2. **Selected 5 countries from each continent** (with significant economic relevance) to reduce the scope of the data.
3. **Visualized missing values** to identify columns with poor data quality.
4. **Split the dataset column-wise into two parts** to improve the clarity of visual inspections.
5. **Dropped columns** with missing values above a predefined general tolerance threshold.
6. **Defined a custom function** to handle missing values:
   - Replaced missing values in **numeric columns** with the **mean**.
   - Replaced missing values in **string columns** with the **mode**.
7. **Applied the function only on numeric columns** (since there were no missing string values).
8. **Final cleaned dataset**:
   - Reduced from **490,127 rows and 61 columns**  
   - To **115,960 rows and 26 columns**

---

## 📁 File Included

- `Beginners_Project2.ipynb` – The Google Colab notebook showing all steps

---

## 💡 Future Suggestions

- Visualize trends of cases, deaths, and vaccinations over time by country or continent
- Analyze the impact of vaccination rollouts
- Perform time series forecasting or build interactive dashboards

---

## 🛠 Tools Used

- **Python**: pandas, numpy, matplotlib, seaborn  
- **Google Colab**

---

## 🔗 Data Source

- [Our World in Data – COVID-19 Dataset](https://ourworldindata.org/coronavirus)

---

## 🙌 Author

This project is part of my portfolio to showcase data cleaning and preprocessing skills using Python. Feedback is welcome!

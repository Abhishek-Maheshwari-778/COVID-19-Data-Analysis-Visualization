# 🦠 COVID-19 Data Analysis & Visualization

This project explores COVID-19 data to uncover key trends and visualize the global impact using Python libraries like pandas, matplotlib, and seaborn.

---

## 📁 Dataset

- Source: https://www.kaggle.com/datasets/imdevskp/corona-virus-report
- Features: Country-wise data including Confirmed, Deaths, Recovered, Active cases

---

## 🛠️ Tools & Libraries Used

- Python (Jupyter Notebook)
- pandas
- numpy
- matplotlib
- seaborn
- plotly (optional for interactive visuals)

---

## 📊 Key Analysis Steps

1. ✅ Data Loading and Initial Exploration
2. ✅ Data Cleaning (Handling Nulls, Removing Duplicates)
3. ✅ Grouping by Country and Aggregation
4. ✅ Calculating Metrics:
   - Recovery Rate = Recovered / Confirmed
   - Death Rate = Deaths / Confirmed
5. ✅ Visualizations:
   - Bar Charts (Top 10 countries)
   - Pie Chart (Proportion of active, recovered, deaths)
   - Horizontal Charts (Recovery and Death Rates)
   - Correlation Heatmap

---

## 📈 Visualizations Preview

| Chart | Description |
|-------|-------------|
| 📊 Bar Plot | Top 10 countries by confirmed cases |
| 📉 Pie Chart | Confirmed vs Active cases |
| 📏 Horizontal Bar | Top 10 countries by Recovery Rate and Death Rate |
| 🧠 Heatmap | Correlation between Confirmed, Deaths, Recovered |

---

## 📌 Insights

- Not all highly infected countries have high recovery rates.
- Some countries exhibit significantly higher death rates.
- Active case numbers can be misleading without context.

---

## 🚀 Future Improvements

- Add time-series analysis (using date-wise data)
- Create interactive dashboards (with Plotly Dash or Streamlit)
- Normalize data per million population

---

## ▶️ Run Locally

1. Clone the repo or download the notebook
2. Install required libraries:
```bash
pip install pandas matplotlib seaborn plotly

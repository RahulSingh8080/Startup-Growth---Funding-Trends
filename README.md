# 🚀 Startup Data Analysis & Prediction

## 📌 Project Overview  
This project analyzes startup data to uncover key trends, correlations, and predictions related to funding, valuation, and exit status. The dataset includes information such as funding rounds, revenue, employees, market share, and profitability. The goal is to gain insights into startup success factors using **data visualization, machine learning models, and statistical analysis**.

---

## 📂 Dataset Information  
The dataset (`startup_data.csv`) consists of **500 startup records** with the following attributes:

| Column Name                | Description                                      |
|----------------------------|--------------------------------------------------|
| **Startup Name**           | Name of the startup                              |
| **Industry**               | Sector in which the startup operates            |
| **Funding Rounds**         | Number of funding rounds received               |
| **Funding Amount (M USD)** | Total funding received in million USD           |
| **Valuation (M USD)**      | Latest valuation in million USD                  |
| **Revenue (M USD)**        | Annual revenue generated                         |
| **Employees**              | Number of employees in the startup               |
| **Market Share (%)**       | Market share percentage                          |
| **Profitable**             | Binary indicator (1 = Profitable, 0 = Not Profitable) |
| **Year Founded**           | Year the startup was established                 |
| **Region**                 | Geographical region of the startup               |
| **Exit Status**            | Final status (Private, Acquired, IPO)            |

---

## 📊 Exploratory Data Analysis (EDA)  
This project includes extensive **EDA** using Python and **Seaborn/Matplotlib** visualizations:  
✅ **Correlation Analysis** – Heatmaps to identify relationships between features  
✅ **Histograms & KDE Plots** – Distribution of funding, valuation, and revenue  
✅ **Pair Plots** – Relationships between key numeric variables  
✅ **Count Plots** – Distribution of startups across industries  

📌 **Sample Correlation Heatmap:**  
![Correlation Heatmap](image.png)  

---

## ⚙️ Machine Learning Models  
We implemented **regression models** to predict startup valuations and success probabilities:  
- **Linear Regression** – Basic baseline model  
- **K-Nearest Neighbors (KNN)** – Captures local trends in startup data  
- **XGBoost** – High-performance gradient boosting for better accuracy  

**Performance Metrics Used:**  
✅ **Mean Absolute Error (MAE)**  
✅ **R² Score**  

---

## 📌 Key Findings  
🔹 **Funding Amount & Valuation** have a high correlation (~0.8) – Startups with higher funding tend to have higher valuations.  
🔹 **Revenue does not always correlate with profitability** – Some high-revenue startups still operate at a loss.  
🔹 **Exit Status (IPO/Acquisition) is not solely determined by funding** – Other factors like industry and market share matter.  

---


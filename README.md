# 🧠 Sentiment-Driven Sales Forecasting (2023)

**Combining Amazon Customer Sentiment with Walmart Sales using Python & GenAI**

![Dashboard](dashboard/Sentiment-Driven_Sales.png)

## 📌 Overview

This project explores the power of **Natural Language Processing (NLP)** and **GenAI** to enhance traditional sales forecasting. By analyzing customer sentiment from Amazon product reviews and aligning it with Walmart's historical sales data, we aim to uncover how public sentiment can influence purchasing behavior.

---

## 🧰 Tech Stack

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **TextBlob** for sentiment analysis
- **Jupyter Notebooks** for EDA & modeling
- **Tableau Public** for dashboarding
- **Amazon Fine Food Reviews Dataset**
- **Walmart Sales Forecasting Dataset (M5)**

---

## 📂 Project Structure

Sentiment-Driven-Sales-Forecasting/
│
├── data/
│ └── raw/
│ ├── reviews/ # Amazon Fine Food Reviews CSV
│ └── walmart/ # Walmart sales data CSV
│
├── notebooks/
│ ├── 01_clean_reviews.ipynb # Preprocess & analyze sentiments
│ ├── 02_clean_sales.ipynb # Clean & transform Walmart sales
│ └── 03_merge_analyze.ipynb # Merge, aggregate & insights
│
├── visualizations/
│ └── sentiment_sales_trends.png # Plots & graphs
│
├── dashboard/
│ └── Sentiment-Driven_Sales.twbx # Tableau workbook file
│
├── insights.txt # Final findings & conclusions
└── README.md 

---

## 📈 Key Insights

- 📉 **July sales dropped** despite high positive sentiment → potential external disruptions
- 📊 **Negative sentiment spike in November** correlated with a decline in sales
- 🔁 **Sentiment ratios can be early indicators** for future sales behavior
- 💬 Average positive sentiment: **75.5%**
- 💰 Total sales: ₹6.7B (₹6,737,218,987)
- 🧾 Total reviews analyzed: **441,779**

---

## 📊 Tableau Dashboard

Explore the interactive dashboard below:

🔗 [**View on Tableau Public**](https://public.tableau.com/views/SentimentDriven-SalesForecastingAmazonWalmart/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 💡 How This Project Stands Out

- 🔍 Applied **GenAI NLP models** to large-scale customer feedback
- 🔄 Bridged **unstructured reviews** with **structured sales data**
- 📊 Created a **professional-grade Tableau dashboard**
- 🧪 Demonstrated **real-world data storytelling** with actionable insights

---

## 🤝 Let's Connect

If you found this project interesting or want to collaborate, feel free to connect:

- 🔗 [LinkedIn](https://www.linkedin.com/in/uday-meka)
- 📬 udaymeka@example.com

---

## 📁 Datasets

- **Amazon reviews**:[Amazon Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/udaymadhusudhan/amazon-reviews-dataset/data)
- **Walmart Sales**: [Cleaned Walmart Sales Forecasting on Kaggle](https://www.kaggle.com/datasets/udaymadhusudhan/cleaned-walmart-sales-forecasting)

---

## 📌 Future Improvements

- Integrate **LLM-based sentiment analysis (like GPT or BERT)**  
- Add **seasonality and promotions** data  
- Improve forecasting using **time-series models** (ARIMA, Prophet, LSTM)

---


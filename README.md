# ☕ Coffee Sales Analysis

This project involves **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** on a dataset containing coffee sales transactions from a vending machine, spanning from **March 2024 to July 2024**. The goal is to uncover customer purchasing patterns, popular coffee types, peak hours, and use linear regression to predict future sales.

---

## 📂 Dataset Overview

- **Source**: Provided via internship project PDF (public link)
- **Transactions**: 1133 rows
- **Period**: March 2024 – July 2024
- **Fields**:
  - `date` / `datetime`
  - `coffee_name` (e.g., Latte, Americano, Hot Chocolate)
  - `cash_type` (card or cash)
  - `card` (anonymized customer ID)
  - `money` (amount spent)


## 📂 Dataset Used

  - <a href = 'https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/Dataset%20Used/Coffee_Sales.csv'>Dataset</a>


## 📝 Google Colab Notebook

  - <a href = 'https://colab.research.google.com/drive/12MZHwFvBghfcqCu9GAUFJF1nZYTEb8m9?usp=sharing'>Analyzed Dataset</a>


---

## ⚙️ Tools & Technologies Used

- Python
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (Linear Regression)

---

## 📊 Key Analysis Performed

- Missing value treatment (card column)
- Outlier removal using IQR method
- Feature engineering: `month`, `day`, `hour`, `weekday`
- Monthly sales trend analysis
- Top-selling coffee types
- Sales by time of day and weekday
- Payment method breakdown (cash vs card)
- Top 10 spending customers
- Line plot of coffee sales by month

---

## 🤖 Machine Learning Modeling

- **Model Used**: Linear Regression
- **Goal**: Predict total daily sales
- **Features**: Time-based & categorical encodings
- **Evaluation**:
  - R² Score: *[0.9297660878636852]*  
  - MSE: *[1.3075076793337863]*

---

## 📌 Key Business Insights

- 💳 Over **92%** of transactions are card-based.
- ☕ **Latte** and **Americano with Milk** are the most popular coffee types.
- ⏰ Peak purchase hours are **10 AM** and **7 PM**.
- 📅 **Tuesdays** see the highest sales volume.
- 📈 Monthly sales showed an upward trend for major products.

---

## 🖼️ Sample Visuals

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Actual%20vs%20Predicted%20Values.png'>Actual vs Predicted Values</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Monthly%20Sales%20Over%20Year.png'>Monthly Sales Over Year</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Monthly%20Sales%20by%20Coffee%20type(With%20Total%20Sales).png'>Monthly Sales by Coffee type(With Total Sales)</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Sales%20by%20Day%20of%20the%20Week.png'>Sales by Day of the Week</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Sales%20by%20Hour%20of%20the%20day.png'>Sales by Hour of the day</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Total%20Revenue%20by%20Coffee%20Name.png'>Total Revenue by Coffee Name</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Total%20Sales%20by%20Card.png'>Total Sales by Card</a>

- <a href ='https://github.com/SantoshKumar902/Coffee-Sales-Analysis/blob/main/images/Total%20Sales%20by%20Coffee%20Product.png'>Total Sales by Coffee Product</a>



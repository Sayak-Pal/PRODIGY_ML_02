

---

# 🛍️ Customer Segmentation using K-Means Clustering

This project is part of the **Prodigy Infotech Internship** and aims to implement **unsupervised machine learning** using the **K-Means Clustering algorithm** to segment customers of a supermarket based on their demographic and purchasing behavior.

---

## 📌 Project Overview

Imagine owning a shopping mall and having access to customer data through membership cards. You want to identify **high-value or easily convertible customers** so the marketing team can design **targeted campaigns**.

This project performs **customer segmentation** using:

* Age
* Gender
* Annual Income
* Spending Score (a score based on purchasing behavior and loyalty)

The result is **clear segmentation of customer groups**, enabling actionable business strategies.

---

## 📂 Dataset

* **Source**: [Mall Customer Segmentation Data (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
* **Columns Used**:

  * `CustomerID`
  * `Gender`
  * `Age`
  * `Annual Income (k$)`
  * `Spending Score (1-100)`

---

## ⚙️ Technologies Used

* **Python 3.x**
* **Pandas & NumPy** – Data processing
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Clustering with KMeans, feature scaling

---

## 🔍 Key Steps

1. **Exploratory Data Analysis (EDA)**

   * Age, income, and spending distribution
   * Gender-based analysis
   * Scatter plots and pair plots to identify patterns

2. **Data Preprocessing**

   * Missing and duplicate value checks
   * Encoding categorical variables (`Gender`)
   * Feature scaling with `StandardScaler`

3. **Model Building**

   * **KMeans Clustering** using 3 features: Age, Annual Income, Spending Score
   * **Elbow Method** to find the optimal number of clusters (k)

4. **Customer Segmentation**

   * Assigning cluster labels to each customer
   * Visualizing cluster composition and gender distribution

---

## 📊 Results

* Optimal number of clusters: **5**
* Each cluster reveals unique customer behavior patterns (e.g. low income but high spenders, high income but low spenders)
* These insights are crucial for **marketing**, **loyalty programs**, and **customer retention**

---

## 🧠 Concepts Learned

* Fundamentals of **unsupervised learning**
* Choosing `k` with the **Elbow Method**
* Data standardization and preprocessing best practices
* Real-world applications of **KMeans clustering** in business strategy

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or Python script:

   ```bash
   jupyter notebook customer_segmentation.ipynb
   # or
   python customer_segmentation.py
   ```

---

## 📁 File Structure

```
├── customer_segmentation.py              # Main project script
├── Mall_Customers.csv                    # Dataset
├── requirements.txt                      # Dependencies
├── README.md                             # Project documentation
```

---

## 🏷️ Tags

`#MachineLearning` `#CustomerSegmentation` `#KMeans` `#Clustering` `#Python` `#RetailAnalytics` `#ProdigyInfotech` `#UnsupervisedLearning` `#MarketingStrategy` `#DataScience`

---


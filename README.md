# 🛍️ Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

This project applies the **K-Means Clustering** algorithm to segment customers based on their **Annual Income** and **Spending Score**. Customer segmentation helps businesses identify groups of customers with similar purchasing behavior, enabling more personalized marketing strategies and better business decisions.

The analysis uses the **Mall Customers Dataset** and visualizes customer groups to uncover meaningful patterns.

---

## 🎯 Objectives

* Analyze customer purchasing behavior.
* Identify distinct customer segments using K-Means Clustering.
* Determine the optimal number of clusters using the Elbow Method.
* Visualize customer groups and cluster centroids.
* Demonstrate how clustering can support business decision-making.

---

## 📂 Dataset

**Dataset:** Mall Customers Dataset

### Features Used

* **Annual Income (k$)**
* **Spending Score (1–100)**

These features are used to group customers with similar income levels and spending habits.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📈 Project Workflow

1. Import required libraries.
2. Load and inspect the dataset.
3. Select Annual Income and Spending Score as features.
4. Apply the Elbow Method to determine the optimal number of clusters.
5. Train the K-Means clustering model.
6. Assign each customer to a cluster.
7. Visualize the customer segments along with cluster centroids.

---

## 📊 Results

* The Elbow Method indicated that **5 clusters** provide an appropriate segmentation of the customers.
* Customers were grouped based on similar income and spending patterns.
* Cluster centroids represent the average characteristics of each customer segment.

The generated visualization clearly distinguishes customer groups, making it easier to understand customer behavior.

---

## 💼 Business Applications

Customer segmentation can be used to:

* Design targeted marketing campaigns.
* Identify high-value customers.
* Improve customer retention strategies.
* Develop personalized promotional offers.
* Support pricing and product recommendation decisions.
* Optimize resource allocation for marketing teams.

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/<your-username>/Customer-Segmentation-Analysis.git
```

Move to the project directory:

```bash
cd Customer-Segmentation-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

Run all cells to reproduce the analysis and visualizations.

---

## 📁 Project Structure

```text
Customer-Segmentation-Analysis/
│── main.ipynb
│── Mall_Customers.csv
│── requirements.txt
│── README.md
```

---

## 📸 Output

Include screenshots of:

* Dataset preview
* Elbow Method graph
* Customer Segmentation scatter plot

---

## 🚀 Future Improvements

* Evaluate cluster quality using the Silhouette Score.
* Apply feature scaling before clustering.
* Experiment with DBSCAN and Hierarchical Clustering.
* Build an interactive Streamlit dashboard for customer segmentation.
* Include additional customer attributes for more detailed segmentation.

---

## 👨‍💻 Author

**Hari Krishna**

If you found this project useful, consider giving it a ⭐ on GitHub.


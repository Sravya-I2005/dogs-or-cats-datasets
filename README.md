# dogs-or-cats-datasets
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview

This project applies **K-Means Clustering** to group retail store customers based on their purchasing behavior.

## 🎯 Objective

Segment customers into distinct groups to:

* Understand buying patterns
* Improve marketing strategies
* Target specific customer segments

---

## 📂 Project Structure

```
├── customers.csv
├── kmeans_customer_segmentation.py
├── clustered_customers.csv
├── README.md
```

---

## ⚙️ Installation

```bash
pip install pandas matplotlib scikit-learn
```

---

## ▶️ Usage

Run the script:

```bash
python kmeans_customer_segmentation.py
```

---

## 📊 Methodology

1. Data preprocessing
2. Feature scaling
3. Finding optimal clusters using Elbow Method
4. Applying K-Means clustering
5. Visualization of clusters

---

## 📈 Features Used

* Annual Income
* Spending Score

---

## 📉 Output

* Clustered dataset saved as `clustered_customers.csv`
* Visualization of customer segments

---

## 🧪 Example Insight

* High income + high spending → Premium customers
* Low income + low spending → Budget customers

---

## 🔮 Future Improvements

* Use more features (age, purchase frequency)
* Apply hierarchical clustering
* Deploy dashboard using Streamlit
* Use silhouette score for evaluation

---

## 📜 License

Open-source and free to use.

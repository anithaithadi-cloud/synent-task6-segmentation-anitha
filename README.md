# 🧠 Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on **customer segmentation** using the K-Means clustering algorithm. The goal is to group customers based on their purchasing behavior, helping businesses better understand their target audience and make data-driven decisions.

---

## 📂 Dataset

The dataset used in this project contains customer information such as:

* Customer ID
* Annual Income (k$)
* Spending Score (1–100)

> ⚠️ **Note:** The dataset included in this repository is a sample for demonstration purposes. For improved accuracy and real-world relevance, it is recommended to use a standard dataset such as the *Mall Customer Segmentation Dataset* from Kaggle.

---

## ⚙️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 🔍 Methodology

1. **Data Loading**

   * Imported dataset using Pandas

2. **Data Preprocessing**

   * Selected relevant features: Annual Income and Spending Score

3. **Model Implementation**

   * Applied K-Means clustering algorithm
   * Defined number of clusters (k = 3)

4. **Visualization**

   * Plotted clusters using scatter plot
   * Each cluster represented with different colors

---

## 📊 Output

The output of this project is a visualization (`customer_clusters.png`) that clearly shows:

* Distinct customer groups
* Spending behavior patterns
* Income distribution across clusters

---

## 🚀 How to Run the Project

1. Install required libraries:

   ```
   pip install pandas matplotlib scikit-learn
   ```

2. Run the script:

   ```
   python customer_segmentation.py
   ```

3. View the generated cluster visualization.

---

## 🎯 Key Insights

* Customers can be grouped into distinct segments based on income and spending behavior
* Businesses can target each segment differently for better marketing strategies
* Data clustering helps uncover hidden patterns in customer data

---

## 🔮 Future Improvements

* Use Elbow Method to determine optimal number of clusters
* Include additional features (Age, Gender)
* Apply advanced clustering techniques

---

## 📌 Conclusion

This project demonstrates how machine learning techniques like K-Means clustering can be used to perform effective customer segmentation. It highlights the importance of data-driven strategies in understanding customer behavior and improving business outcomes.

---

## 📁 Project Structure

```
├── Mall_Customers.csv
├── customer_segmentation.py
├── customer_clusters.png
└── README.md
```

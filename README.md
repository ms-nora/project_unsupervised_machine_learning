## **Note on GitHub Alerts:**
This repository may trigger alerts or warnings on GitHub 
(e.g., RuntimeWarning: All-NaN slice encountered) 
during automated workflows or static analysis tools. 
These warnings occur because stricter testing environments 
like GitHub Actions flag potential issues (e.g., operations on NaN-only slices) 
that do not halt execution in environments like Google Colab. 
While these warnings do not cause errors during execution, 
they serve as reminders to handle edge cases like NaN values 
or zero variance columns in datasets.


# **Project: Clustering and Audio Feature Analysis**

---

## **K-Means Clustering**
- **The basics of K-Means:**  
  An introduction to the K-Means clustering algorithm and its key concepts.  
- **Implementing K-Means:**  
  Practical implementation of K-Means using Python.  
- **Understanding audio features:**  
  Exploring song features and their relevance to clustering.  

---

## **Similarities: Distance and Scale**
- **Similar songs: building your intuition:**  
  A conceptual overview of how similarity is determined in song datasets.  
- **Similar songs: computing distances:**  
  Calculating distances between songs to measure similarity.  
- **Scaling data: a brief overview:**  
  Why scaling is necessary and how it impacts clustering results.  
- **Scaling data: intro to Scikit-Learn transformers:**  
  Using Scikit-Learn to scale and preprocess data.  

---

## **Analyzing Clusters**
- **Using maths to determine the number of clusters:**  
  A mathematical approach to selecting the optimal number of clusters.  
- **Using business sense to determine the number of clusters:**  
  A practical, real-world perspective on deciding the number of clusters.  

---

## **PCA**
- **Principal Component Analysis (PCA):**  
  Introduction to PCA for dimensionality reduction and its role in clustering high-dimensional data.  


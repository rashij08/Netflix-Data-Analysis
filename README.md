# 🎬 Netflix Content Clustering & Analysis

## 📌 Project Overview
This project analyzes and clusters Netflix’s vast catalog of movies and TV shows using machine learning and visualization techniques.  
The goal is to perform **content-based clustering** to group similar shows/movies together based on features such as **genre, rating, description, and duration**.

By identifying content clusters, Netflix can enhance its **recommendation system**, understand **content trends**, and improve **strategic decision-making**.

---

## 🎯 Business Objective
- Segment Netflix’s catalog using **K-Means clustering** and **TF-IDF text representation**.
- Identify content similarities and trends based on genre, rating, and description.
- Support **data-driven recommendations** and **content strategy optimization**.

---

## 🧠 Technologies Used
- **Python**
- **Pandas, NumPy** – Data handling
- **Matplotlib, Seaborn** – Data Visualization
- **Scikit-learn (TF-IDF, PCA, KMeans)** – Machine Learning
- **Jupyter Notebook** – Development Environment

---

## 🧹 Steps Followed
1. Data Cleaning & Preprocessing 
   - Removed missing values and duplicates  
   - Cleaned categorical fields (`type`, `country`, `rating`, etc.)

2. Exploratory Data Analysis (EDA) 
   - Created 15+ insightful charts (Univariate, Bivariate, Multivariate)  
   - Key insights on countries, genres, ratings, and release trends

3. Feature Extraction (TF-IDF) 
   - Converted textual `description` into numerical vectors  

4. Dimensionality Reduction (PCA)
   - Reduced features for better visualization and clustering efficiency  

5. Clustering (K-Means) 
   - Segmented content into groups based on similarity  

6. Cluster Evaluation & Visualization 
   - Visualized content clusters and analyzed dominant genres per cluster  



## 💼 Business Impact
- Enhanced content recommendation for users.
- Helped Netflix identify content gaps and underrepresented genres.
- Guided regional marketing and production planning.

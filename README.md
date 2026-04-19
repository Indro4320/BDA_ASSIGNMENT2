# Big Data Analytics with PySpark

This project explores how PySpark can be used to solve real-world machine learning problems at scale. It demonstrates three core analytics tasks—classification, clustering, and recommendation systems—while walking through the full pipeline from raw data to meaningful insights.

The implementation is designed to be simple, practical, and reproducible, making it suitable for learning and experimentation in distributed data processing.

---

## Project Highlights

- End-to-end machine learning workflows using PySpark  
- Hands-on implementation with real-world datasets  
- Covers data preprocessing, feature engineering, modeling, and evaluation  
- Includes visualizations to better understand model performance  

---

## Environment Setup

This project is designed to run in **Google Colab**.

- No manual dataset downloads required  
- All datasets are fetched automatically during execution  

---

## Core Components

### 1. Classification — Titanic Dataset

A binary classification problem to predict passenger survival.

**Workflow:**
- Selected features: `Pclass`, `Sex`, `Age`, `Fare`  
- Handled missing values  
- Encoded categorical variables using `StringIndexer`  
- Built a Logistic Regression model  

**Evaluation Metrics:**
- Accuracy  
- Precision  
- Recall  
- F1 Score  

**Visualizations:**
- Confusion Matrix  
- Scatter Plot (Age vs Fare)  

---

### 2. Clustering — Iris Dataset

An unsupervised learning task to group similar data points.

**Workflow:**
- Created feature vectors using `VectorAssembler`  
- Applied K-Means clustering (`k = 3`)  

**Evaluation:**
- Silhouette Score  

**Visualization:**
- Cluster Scatter Plot (Sepal Length vs Petal Length)  

---

### 3. Recommendation System — MovieLens Dataset

A collaborative filtering system for personalized movie recommendations.

**Workflow:**
- Used ALS (Alternating Least Squares)  
- Modeled user-item interactions  
- Generated recommendations  

**Evaluation:**
- RMSE (Root Mean Squared Error)  

**Outputs:**
- Top movie recommendations for users  
- Ratings distribution histogram  

---

## 🛠️ Technologies Used

- Python  
- PySpark (MLlib)  
- Pandas  
- Matplotlib  

---

## 📈 Visualizations

- Confusion Matrix for classification  
- Scatter plots for feature relationships  
- Cluster visualization  
- Ratings distribution histogram  

---

## How to Run

1. Open the notebook in Google Colab  
2. Ensure PySpark is available  
3. Run all cells sequentially  
4. Datasets will be downloaded automatically  

---

## Learning Outcomes

- Understanding PySpark ML pipelines  
- Working with distributed datasets  
- Implementing:
  - Classification  
  - Clustering  
  - Recommendation systems  
- Evaluating machine learning models  
- Creating meaningful data visualizations  

---

## Note

All datasets are downloaded dynamically during execution and are not stored in this repository.

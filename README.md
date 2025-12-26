# 📊 Assignment 1: Supervised Learning and kNN Algorithm

## 📌 Project Overview
This repository contains the implementation and analysis for **Assignment 1: Supervised Learning and kNN Algorithm**, completed as a group project 🤝.  
The goal of this assignment is to explore the **k-Nearest Neighbors (kNN)** classification algorithm by applying it to a real-world dataset, evaluating its performance, and experimenting with different parameters and validation techniques.

The project is divided into two main parts:
- 🔹 Basic understanding and application of the kNN algorithm  
- 🔹 In-depth experimentation and evaluation of kNN performance  

All code, experiments, and analysis are implemented in a Jupyter Notebook 📓.

---

## 👥 Group Members
- Muntasir Islam  
- Md Maruf  

---

## 🗂️ Dataset Description
The dataset used in this project is the **Work Hours and Productivity Dataset**, obtained from Kaggle.

### 📄 Dataset Summary
- Focuses on employee work hours and productivity levels  
- Suitable for classification and business analytics tasks  
- Registered on Moodle to ensure dataset uniqueness across groups  

### 🔢 Example Features
- Work hours  
- Productivity-related attributes  
- Target variable representing productivity category  

This dataset will also be reused in future assignments where applicable 🔁.

---

## 📓 Jupyter Notebook Description (`Assignment1.ipynb`)
The notebook **`Assignment1.ipynb`** contains the complete workflow for this assignment, including:

- 📥 Loading and exploring the dataset  
- 🧹 Data preprocessing and feature selection  
- 🤖 Implementation of the kNN classifier using `scikit-learn`  
- 🏋️ Model training and prediction  
- 📊 Performance evaluation using accuracy metrics  
- 🔄 Experimentation with different values of **k**  
- ✂️ Analysis of different train/test splits  
- 🔁 Application of **k-fold cross-validation**  
- 📈 Visualization of results and accuracy comparisons  

Each section of the notebook is clearly structured and commented for easy understanding.

---

## 🧪 Part 1: Familiarization and Basic Testing

### ⚙️ kNN Algorithm Implementation
- The kNN classifier is implemented using the **scikit-learn** library  
- An initial model is trained and tested using a standard train/test split  
- Baseline accuracy is calculated and analyzed  

### 🌍 Real-World Applications of kNN
1. 🛒 **Recommendation Systems** – Suggesting products, movies, or content based on user similarity  
2. 🏥 **Medical Diagnosis** – Classifying patients by comparing symptoms with historical cases  

---

## 🔬 Part 2: In-Depth Experimentation

### 🔢 Parameter Experimentation
- Multiple values of **k** are tested to observe their effect on model accuracy  
- Results show how different k values impact classification performance  

### ✂️ Train-Test Split Analysis
- Different train/test ratios (e.g., 80/20) are evaluated  
- The effect of data size on accuracy and generalization is analyzed  

### 🔁 k-Fold Cross-Validation
- k-fold cross-validation is applied for more reliable evaluation  
- Accuracy is computed for each fold and averaged  
- Results demonstrate improved robustness compared to a single split  

---

## 📌 Key Findings
- 📉 Model performance is sensitive to the choice of k  
- 📊 Cross-validation provides a more stable accuracy estimate  
- ✅ kNN performs well on this dataset when properly tuned  

---

## ▶️ How to Run the Project
1. Clone this repository 📦  
2. Open `Assignment1.ipynb` using Jupyter Notebook or JupyterLab  
3. Install required libraries:
   - numpy  
   - pandas  
   - matplotlib  
   - scikit-learn  
4. Run all cells sequentially to reproduce the results ▶️  

---

## 🏁 Conclusion
This project demonstrates the practical application of the **kNN algorithm** for supervised learning tasks. Through parameter tuning, train/test analysis, and cross-validation, we gain valuable insights into model behavior and performance evaluation in real-world scenarios 🚀.


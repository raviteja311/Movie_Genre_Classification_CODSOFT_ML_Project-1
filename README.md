# 🎮 Movie Genre Classification

## 📌 Project Overview
This project focuses on **classifying movie genres** based on their descriptions using **Machine Learning models**. We use **TF-IDF vectorization** to transform text data and apply **Naïve Bayes, Logistic Regression, and SVM models** for classification. 

## 📂 Dataset
The dataset consists of three columns:
- **Title**: Movie name along with the release year (e.g., *Inception (2010)*).
- **Genre**: The target label (e.g., *Sci-Fi*).
- **Description**: A brief plot summary of the movie.

## 🔄 Workflow
1. **Data Preprocessing**
   - Remove year from titles
   - Text cleaning (lowercasing, stopword removal, punctuation removal)
   - Tokenization & Lemmatization
   - Label Encoding for genres
   - Train-test split
   - TF-IDF Vectorization
   - Handle class imbalance using SMOTE

2. **Exploratory Data Analysis (EDA)**
   - Genre distribution analysis
   - Word cloud visualization
   - TF-IDF feature importance

3. **Model Training & Tuning**
### **1⃣ Naïve Bayes (NB)**
- Trained using **MultinomialNB**.
- Best for text classification.

### **2⃣ Logistic Regression (LR)**
- Tuned using **GridSearchCV** to find optimal hyperparameters.

### **3⃣ Support Vector Machine (SVM)**
- Tuned hyperparameters **C, kernel**.
- Best kernel selected through **GridSearchCV**.


4. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

5. **Predicting Movie Genres**
   - predict genres based on descriptions.
   

## 🚀 How to Run the Project
1. **Install Dependencies**:
   ```bash
   pip install numpy pandas scikit-learn imbalanced-learn
   ```
2. **Load the dataset** and preprocess it.
3. **Train models** with optimal hyperparameters.
4. **Evaluate & predict** genres based on descriptions.

## 📌 Acknowledgment
This project was completed as part of **CODSOFT** internship/training program. Special thanks to **CODSOFT** for providing the opportunity to work on this project.



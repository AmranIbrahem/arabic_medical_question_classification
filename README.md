# Arabic Medical Question Classification Using Machine Learning

## 📌 Project Overview
This project presents a comprehensive system for classifying Arabic medical questions into specific medical categories using machine learning techniques. The model is developed based on a large dataset of Arabic medical consultations containing over 84,000 medical questions with their specialized classifications.

## 🎯 Primary Objective
Build an intelligent model capable of automatically classifying Arabic medical questions into 16 main medical categories, contributing to:
- Accelerating the process of directing medical inquiries to appropriate specialists
- Improving the efficiency of electronic medical platforms
- Supporting intelligent diagnosis and medical consultation systems

## 📊 Dataset
- **Source:** Shifaa Arabic Medical Consultations from Hugging Face
- **Size:** 84,422 medical questions
- **Categories:** 16 main medical categories
- **Language:** Modern Standard Arabic and medical colloquial Arabic

### Included Medical Categories:
1. Obstetrics and Gynecology
2. Internal Medicine and Respiratory Diseases
3. Pharmaceuticals and Preparations
4. Dermatological Diseases
5. Head Diseases
6. Urinary System Diseases and Others
7. Bone Diseases
8. Physical Health
9. Blood Diseases and Oncology
10. Nervous System Diseases
11. Medical Affairs and Miscellaneous Issues
12. Pediatrics
13. Endocrine and Hormonal Diseases
14. Muscular Diseases
15. General Surgery and Cosmetic Surgery
16. Alternative Medicine

## 🔧 Technical Features

### 1. Exploratory Data Analysis (EDA)
- Analysis of medical category distribution
- Study of text lengths and data volume
- Detection of duplicate questions
- Analysis of descriptive statistics

### 2. Text Preprocessing
- Cleaning Arabic texts
- Removing duplicates
- Preparing data for machine learning

### 3. Models Used
#### Traditional Models:
- Random Forest
- Naive Bayes
- SVM
- Logistic Regression

#### Neural Network Models:
- BiLSTM
- CNN
- Hybrid CNN-BiLSTM

#### Advanced Model:
- AraBERT (Arabic pre-trained model)

### 4. Evaluation and Comparison
- Comparison of all model performances
- Analysis of evaluation metrics
- Selection of the best prediction model

## ⚙️ Requirements
- Python 3.8+
- TensorFlow 2.x
- Scikit-learn
- Pandas, NumPy
- Transformers (Hugging Face)
- NLTK

## 🚀 How to Run

### Step 1: Install Dependencies
```bash
pip install -r requirements.txt
```
### Step 2: Run the Code
```python
▎Open Jupyter Notebook

jupyter notebook arabic_medical_question_classification.ipynb

▎Or use Google Colab

▎Upload the file to Colab and run cells in order
```

### Step 3: Train Models
Training happens automatically when running cells in this order:
1. Load libraries
2. Load data
3. Explore data
4. Preprocess texts
5. Split data
6. Train models
7. Evaluate and compare

## 📈 Performance Results

### Evaluation Metrics Used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🔍 Important Notes
## 1. Data Challenges
- Class imbalance: Some categories have thousands of samples while others have only a few hundred.
- Duplication: 29,212 duplicate questions.
- Text length variation: From a few words to over 1000 words.

## 2. Imbalance Handling Algorithms
- Resampling
- Class weights
- Augmentation techniques

## 3. Arabic Text Processing
- Handling diacritics and vowels.
- Preprocessing medical vocabulary.
- Text normalization.

- 

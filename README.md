# Sentiment Analysis & Supervised Learning Projects

A comprehensive collection of machine learning projects focusing on **sentiment analysis** and **supervised learning classification algorithms**.

---

## 📋 Table of Contents
- [Projects Overview](#projects-overview)
- [Technologies & Libraries](#technologies--libraries)
- [Project Descriptions](#project-descriptions)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Results & Performance](#results--performance)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Projects Overview

This repository contains two major machine learning projects:

1. **Twitter Sentiment Analysis** - Multi-class text classification
2. **ML Classification Project** - Algorithm comparison on standard datasets

---

## 🛠️ Technologies & Libraries

### Core Libraries
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning algorithms and evaluation metrics
- **matplotlib** & **seaborn** - Data visualization
- **wordcloud** - Text visualization

### Machine Learning Models
- **Text Processing**: TF-IDF Vectorization, Text Preprocessing
- **Classification Models**: 
  - SVM (Support Vector Machines)
  - Logistic Regression
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Random Forest
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 📁 Project Descriptions

### Project 1: Twitter Sentiment Analysis
**File**: `sentiment_analysis_(1).ipynb`

**Objective**: Classify tweets into three sentiment categories (Positive, Negative, Neutral)

**Dataset Features**:
- `text` - Raw tweet content
- `selected_text` - Key sentiment phrase
- `sentiment` - Target label (positive/negative/neutral)
- `Time of Tweet` - Time period (morning/noon/night)
- `Age of User`, `Country`, `Population`, `Land Area`, `Density` - Demographic features

**Pipeline**:
```
Upload Data → EDA → Preprocessing → Feature Engineering → Model Training → Evaluation → Prediction
```

**Key Steps**:
1. **Exploratory Data Analysis** - Understand data distribution and patterns
2. **Text Preprocessing** - Cleaning, tokenization, stop word removal
3. **Feature Engineering** - TF-IDF vectorization, demographic feature encoding
4. **Model Development** - Train multiple classifiers
5. **Model Evaluation** - Cross-validation and performance metrics
6. **Prediction** - Classify new tweets

**Expected Outcomes**:
- High-performing multi-class classifier
- Feature importance analysis
- Word cloud visualizations showing sentiment patterns

---

### Project 2: ML Classification Algorithms
**File**: `ml_classification_project (2).ipynb`

**Objective**: Compare multiple classification algorithms on standard ML datasets

**Datasets Used**:
1. **Iris Dataset** - 150 samples, 4 features, 3 classes
2. **Breast Cancer Dataset** - 569 samples, 30 features, 2 classes (binary)

**Algorithms Compared**:
- **K-Nearest Neighbors (KNN)** - Proximity-based classification
- **Support Vector Machines (SVM)** - Hyperplane optimization
- **Decision Trees** - Rule-based hierarchical classification

**Pipeline**:
```
Load Data → Exploratory Analysis → Data Scaling → Train-Test Split → Model Training → Evaluation
```

**Key Steps**:
1. **Data Loading** - Import Iris and Breast Cancer datasets
2. **Feature Scaling** - Standardize features for distance-based algorithms
3. **Model Training** - Train KNN, SVM, and Decision Tree
4. **Hyperparameter Tuning** - Optimize model parameters
5. **Performance Comparison** - Accuracy, classification reports, confusion matrices
6. **Visualization** - Decision boundaries, confusion matrices, decision trees

**Expected Outcomes**:
- Algorithm performance comparison
- Optimal hyperparameters for each model
- Decision tree visualizations
- Confusion matrices and classification metrics

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Sentiment-Analysis-ML-Projects.git
cd Sentiment-Analysis-ML-Projects
```

### Step 2: Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn wordcloud jupyter
```

### Step 4: Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 📖 Usage

### Running the Projects

#### Twitter Sentiment Analysis
1. Open `sentiment_analysis_(1).ipynb` in Jupyter
2. Run cells sequentially from top to bottom
3. Modify the data path if needed
4. Experiment with different models and hyperparameters

#### ML Classification Project
1. Open `ml_classification_project (2).ipynb` in Jupyter
2. The notebook uses built-in datasets (no external data needed)
3. Run all cells to train and evaluate all models
4. Visualize results with confusion matrices and decision trees

---

## 📊 Results & Performance

### Sentiment Analysis
Expected performance metrics:
- **Accuracy**: ~80-90% depending on model and preprocessing
- **Best Performing Models**: SVM or Logistic Regression typically outperform Naive Bayes
- **Key Insight**: TF-IDF features with demographic data improve classification

### ML Classification
Expected results:
- **Iris Dataset**: Near-perfect accuracy (~95-100%) across all algorithms
- **Breast Cancer Dataset**: High accuracy (~95-97%) with optimized hyperparameters
- **Algorithm Ranking**: Performance varies by dataset and parameters

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add improvement'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

---

---

## 📧 Contact & Questions

For questions or suggestions about this project, feel free to reach out or open an issue on GitHub.

---

## 🔗 Quick Links

- **Scikit-learn Documentation**: https://scikit-learn.org/
- **Pandas Documentation**: https://pandas.pydata.org/
- **Jupyter Notebooks**: https://jupyter.org/

---

**Last Updated**: May 8, 2026


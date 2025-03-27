# Cybersecurity Threat Classification Using ML for CICIDS2017

## Overview
This repository presents a comprehensive analysis of the CIC-IDS2017 dataset, developed by the Canadian Institute for Cybersecurity (CIC) for advancing intrusion detection systems (IDS). The core objective is to demonstrate the implementation and evaluation of various machine learning models for binary and multi-class network intrusion classification. The dataset is publicly accessible. The dataset can be obtained from [here](https://www.unb.ca/cic/datasets/ids-2017.html).

## Dataset Characteristics
### Size and Composition
- The dataset contains more than 2.8 million records collected over a five-day period (from July 3 to July 7, 2017).
- It features both normal network activity and a variety of attack types, including Brute Force, Heartbleed, Botnet, DoS, DDoS, Web Attacks, and Infiltration.
- The data is significantly imbalanced, with the majority of entries labeled as 'Benign' (representing normal traffic).

### Dataset Overview
- The dataset comprises 79 features—78 numerical attributes describing network flow metrics (such as flow duration, packet sizes, ports, and flags), along with a categorical 'Label' column indicating the type of traffic. It also includes a thorough exploratory data analysis (EDA), providing insights into the dataset’s structure and characteristics, while highlighting key patterns and anomalies through visualizations.

### Data Preprocessing and ML models
- The data preprocessing phase involved cleaning the dataset by addressing duplicates and missing values, optimizing memory usage, standardizing features, and applying PCA to enhance the dataset’s suitability for analysis.
- Multiple machine learning models were implemented and trained, including Logistic Regression, Support Vector Machine, Random Forest, Decision Tree, and K-Nearest Neighbors. The analysis covers both binary and multi-class classification tasks.

### Performance Evaluation and Discussion
- Each model's performance is assessed using evaluation metrics including accuracy, recall, F1-score, and the confusion matrix. Additionally, the effects of class imbalance on the effectiveness of the models are analyzed and discussed.

## Key Features
- Applies a range of data preprocessing techniques, including feature standardization for consistency, Principal Component Analysis (PCA) for reducing dimensionality, and SMOTE for addressing class imbalance. Explores both binary and multi-class classification approaches.
- Employs various machine learning algorithms such as Logistic Regression, Support Vector Machines (SVM), Random Forests, Decision Trees, and K-Nearest Neighbors (KNN).
- Leverages a real-world dataset for training and evaluation and utilizes cross-validation to prevent overfitting and ensure robust model performance.
- Delivers a comprehensive comparison and analysis of multiple classification models and evaluates performance using metrics like precision, recall, accuracy, F1-score, and confusion matrix.
- Provides actionable insights into enhancing network security by identifying the most effective model for intrusion detection.

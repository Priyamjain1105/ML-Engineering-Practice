
# 📚 **एमएलसंग्रह (MLSangrah)** 📚
![Avery Davis](https://github.com/user-attachments/assets/60f9df3c-77fc-4d90-a56e-7a530ae63c61)



Welcome to **"एमएलसंग्रह"** – a collection of **Machine Learning** projects! 🤖💻

This repository is designed to showcase various **ML concepts** through hands-on implementations. Each project highlights different applications of ML algorithms, helping to demonstrate a wide range of techniques and models. 🌱

### **✨ Purpose**
The goal of this repository is to gather practical **Machine Learning** projects that explore fundamental and advanced techniques. Whether you're a beginner or looking to refine your skills, this is your space for **learning and growth**! 🚀

### **📂 Project Structure**
Each folder in this repository contains a unique project demonstrating different **Machine Learning** methods such as:
- **Supervised Learning** 📈
- **Unsupervised Learning** 🧑‍🏫
- **Reinforcement Learning** 🌐
- **Neural Networks** 🧠

### Prerequisite's
  - **[Numpy basics](prerequisite/numpy1.ipynb)**
    - Creating two numpy array
    - Combining two numpy array
  - **[Numpy Advance](prerequisite/numpy2.ipynb)**
    - Random Number generation and seeting seed
  - [Pandas Basic](prerequisite/pandas1.ipynb)
    - Types of datastructure (series and Dataframe)
    - Loading data from different types of file (CSV, Excel...)
    - Viewing Data & Summary of data (head(), info()...)
    - Filtering rows and selecting columns
  - **[Data Cleaning and Preparation with Pandas](prerequisite/pandas2.ipynb)**
    - Handling Missing values (Dropping,filling(backrd, forward), interpolate
    - Data transfromation: Renaming columns, changing datetype, modigying columns and creating new once
    - Combining and Merging dataframe
  - **[Data Aggregations and Grouping in Pandas](prerequisite/pandas3.ipynb)**
    - Performing different operations on Group iteration, Aggregation(min, max, mean)
    - `df.groupby("category_column")["numeric_column"].mean()`
    - Multi Aggregation using agg() function
    - Pivot Table
    - Custom Agg()
  - **[Data Visualization and Mathplotlib](prerequisite/matplotlib.ipynb)**
    - Line Plot, Barchart, Histogram, Scatter Plot
    - Customizing the Plot
  - **[Data Visualization with Seaborn](prerequisite/seaborn.ipynb)**
    - HeatMap/Correlation matrix btw the features and target
    - Pair Plot
  - **[Exploratory Data Analysis on the data](prerequisite/EDA.ipynb)**
    - Steps in EDA
    - Different Ways of feaature Identification
      - By Feature type, By Role in ML Model, & By Domain
    - Psrformad EDA on dataset with different Visualisations btw data histogram,, scatterplot, barchart...
    - Summarize finding in a Report

# 🔗 Machine Learning
  ## Foundational Topics
  - [1. Simple Linear Regression](BasicML/Simple_regression.ipynb) 
  - [2. Advanced Regression Models – Polynomial Regression and Regularization](BasicML/regression_advanced.ipynb) 
  - [3. Lasso and Ridge Regression](BasicML/regularization1.ipynb)
  - [4. Logistic Regression for Binary Classification](BasicML/classification.ipynb)  
  - [5. Model Evaluation Metrics for Regression and Classification](BasicML/evaluation_metrics.ipynb)
  - [6. K-Nearest Neighbours](BasicML/k-nearest.ipynb)
  - [7. Linear Regression Project California House price Prediction](BasicML/project1.ipynb)
  - [8. Classification Project Customer Churn Prediction](BasicML/project2.ipynb)
  

  ## Featuring Enginnering and Model Evaluation
  - **[1. Introduction to Feature Enginnering](Feature_Enginnering/intro.ipynb)**
    - Types of Feature (Categorical , Numerical and Ordinal)
    - Selecting Features Based on their datatypesz
  - **[2. Scaling and Normalisation](Feature_Enginnering/Scaling_And_Normalisation.ipynb)**
    - Preprocessing technique used to transform numerical features to a common range or distribution
    - MinMax [0  to 1]  & Standardization(Z Score scaling) : Standard deviation of 1
  - **[3. Encoding Categorical Variables (One-Hot Encoding anf Labeled Encoding)](Feature_Enginnering/encoding.ipynb)**
    -  Onehot Encoding, Label Encoding, Frenquency Encoding, Target Encoding
  - **[4. Feature Selection](Feature_Enginnering/feature_selection.ipynb)**
    - Techniques
      - Filter Method: feature statistical properties in trealtion with target variable
      - Wrapper Method: Iteratively select feature by trainin and evaluating model
      - Embedded Method: 
    - Corrlelaion matrix for feature selection (w.r.t target)
    - Feature selection with high correlation to the target
    - Using Mututal info Regression (w.r.t target)
    - Feature Importance using random forest and plotting it (w.r.t target)
  - **[5. Cross-Validation and Hyperparameter Tuning](Feature_Enginnering/cross_validation.ipynb)**
    - Types of Cross-Validation
      - K-Fold
      - Stratifies K-Fold
      - Leave-One-Out
    - Hyperparameter Tuning: Paramtetr not learned by model & are set before training
      - Grid Search
      - Random Search
    - Hands on Using Cross alidation and Grid Search with Random Forest
  - **[6. Transformation](Feature_Enginnering/transformation.ipynb)**
    - Feature Creation: deriving new feature form existing once
      - Date-Time Features [dd/mm/yyyy] -> [dd,mm,yyyy]
      - Interaction Features Area * price = real state price
      - Aggeregations Feature (mean, sum, count)
    - Transforming Feature: modifying existing feature to bettr suit the learning algo
      - Logarithmic Transformation
      - Square Root Transformation
      - Polynomial Transformation
    - HandsON: date to -> day, month, year
    - HandsOn: Polynomial Transformation
  
  ## Advanced Machine Learning Algorithms
  - [1. Introduction to Ensemble Learning and Hands on Boosting with 3 model (log, decision_tree and KNN)](AdvancedML/ensemble_learning.ipynb)
  - [2. Bagging and Random Forest, Handson - Breast Cancer](AdvancedML/bagging_rf.ipynb)
  - [3. Boosting and Gradient Boosting, Handson - Breast Cancer](AdvancedML/boosting_gb.ipynb)
  - [4. XGBoost, Handson - Breast Cancer XGBoost vs Gradient](AdvancedML/XGBoost.ipynb)
  - [5. CatBoost and LightGBM ](AdvancedML/LightGBM_and_CatBoost.ipynb)
    - Catboost vs LighTGBM vs XGBoost on titanic dataset

  ## Model Tuning and Optimixation

# Deep Learning

## Basics of ANN
- [1. Deep Learning Basics](ANN/deeplearning.ipynb)
- [2. Forward Propagation](ANN/forward_propagation.ipynb)
- [3. Loss Function and Backpropagation](ANN/backpropagation.ipynb)
- [4. ANN MINST Dataset trained using Tensorflow](ANN/ANN_tensorflow.ipynb)
- [5. ANN MNIST Dataset trained using PyTorch](ANN/ANN_pytorch.ipynb)
- [6. Project CIFAR-10 Using TensorFlow](ANN/ANN_CIFAR-10.ipynb)
  
## Convolutional Neural Network
- [1 Introcustion to CNN](CNN/into_cnn.ipynb)
  - Basics of CNN
  - Loading the CIFER Dataset
  - Visualise the sample dataset
  - Display the pixel value of the first image
  - Tensorflow CNN Model
  - Pytorch CNN Model

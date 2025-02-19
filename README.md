# A Comprehensive Exploration of Machine Learning Techniques for EV Battery SoC Estimation

## Description
This project presents a thorough investigation of various machine learning models applied to the **State of Charge (SoC)** estimation for Lithium-ion batteries under different operating conditions. By leveraging algorithms like **Random Forest (RF)**, **Decision Tree (DT)**, **Support Vector Regression (SVR)**, **Gradient Boosting**, **Polynomial Regression**, and **Multilayer Perceptron (ANN)**, the work achieves **high accuracy** (up to 99.9%) and **low Mean Absolute Error (1.21%)** in predicting SoC. Extensive experiments were conducted on two real-world datasets—**LG Battery** and **Unibo Powertools Battery**—along with K-fold cross validation and Grid Search for hyperparameter tuning.

## Key Features
- **Robust SoC Estimation**  
  Evaluates performance in estimating SoC across varying battery conditions (temperature, load, etc.).
- **Machine Learning Comparisons**  
  Compares multiple ML techniques (RF, DT, SVM, Gradient Boosting, ANN) for best accuracy and minimal error.
- **Error Minimization**  
  Employs systematic validation (K-fold, Grid Search) to reduce errors, with the **Random Forest** model showing the highest accuracy and **Decision Tree** model achieving minimal MAE.
- **Real-World Datasets**  
  Validates findings using **LG Battery** and **Unibo Powertools** data, demonstrating practical applicability.

## Techniques Used
- **Random Forest, Decision Tree, Gradient Boosting**  
  Ensemble methods for capturing complex relationships in voltage, current, and temperature.
- **Support Vector Regression (SVR)**  
  Robust to outliers, suitable for high-dimensional feature spaces.
- **Polynomial Regression**  
  Models nonlinear SoC-voltage correlations.
- **Multilayer Perceptron (ANN)**  
  Learns intricate battery behavior through layered nonlinear transformations.
- **Statistical Validation**  
  K-fold cross validation and Grid Search to fine-tune hyperparameters and confirm model reliability.

## Publication and Presentation
- **58th International UPEC 2023, Ireland**  
  Paper presented at the conference, illustrating the comparative performance of ML models for SoC estimation.  
  [IEEE Xplore Link](https://ieeexplore.ieee.org/document/10294352)


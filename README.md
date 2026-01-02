# Insurance-Claim-Prediction
* **Project Summary:**
   This project focuses on pretending wheather a customer will file an insuarance claim
   using machine learning technques.The dataset is highly imbalanced and contains anonymized customer,
   vehicle and regional features.Multiple classification model were trained and evaluated.
*  **Problem Statement:**
   Insuranace Companies face significant financial risk due to incorrect claim predictions
   the goal of this project is to:
     * Predict wheather a customer is likely to make an insurance claim.
     * Handle severe class imbalance
     * Identify the best performing classification model.
     * Provide actionable insights for business decision-making.
*  **Dataset Description:**  
   * **Target Variable:**  
       * 1- Customer will file a claim
       * 0- Customer will not file a claim  
   * **Feature Categories:**  
        * ps_ind_* - Personal Info
        * ps_car_* - Car Features
        * ps_reg_* - Regional Features
        * ps_calc_* - Calculation Features  
 *  **Key Charcteristics:** 
        * No missing values  
        * Highly imbalanced target variable   
        * Large number of anonymized features    
 * **Project Workflow**  
   **1.Data Understanding  & EDA**    
       *  Dataset Shape and Structure analysis  
       *  Target Class distribution analysis  
       *  Feature Categorization  
       *  Identification of class imbalance    
    **2.Data Preprocessing**    
       *  Feature selection  
       *  Handling class imbalace using undersampling    
    **3.Model Building**      
       The follwing models were implemented and comparerd:    
        *  Logistic Rregression  
        *  Supprort Vector Machine  
        *  Neural Network(MLPClassifier)  
        *  Decision Tree  
        *  Random Forest  
        *  XGBoost    
     **4.Model Evaluation**    
        *  Accuracy  
        *  Precision  
        *  Recall  
        *  F!-Score  
        *  Confusion Matrix    
**5.Hyperparameter Tuning**    
             * Grid Search applied on Random Forest  
             * Performance improvement after tuning  
* **Best Model**    
      **Random Forest Classifier**    
        * Strong performance on imbalanced data  
        * High recall for claim prediction  
        * Balanced precision and F1_score  
        * Robust against overfitting    
* **Business Insights & Actionable Suggestions**  
    **Feature**            -            **Marketing**    
      Vehicle age          -    Target older vaehicles with preventive insuarance offers      
      Region               -    Focus marketing compaingns in high risk regions  
      Driving history      -    Provide discounts for safe drivers  
      High-risk profiles   -    Personlized prenium pricing  
* **Technologies Used **
   * Python
   * Pandas ,NUmpy
   * Matplotlib,Seaborn
   * Scikit-learn
   * XGBoost 

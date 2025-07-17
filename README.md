# Innovative Regression Models for Agricultural Yield Prediction

This project explores an integrated approach for accurate crop yield prediction by combining process-based agricultural models with machine learning (ML) techniques. It is motivated by the need for timely and reliable yield forecasting to support precision agriculture and sustainable food production.

## 📌 Project Objectives

- To design a machine learning pipeline that predicts crop yield using environmental and agricultural features.
- To leverage hybrid modeling by integrating process-based variables (like soil, weather patterns) with ML-based predictors.
- To evaluate the performance of regression models like Random Forest, Extra Trees, XGBoost, and Online Extra Trees Regressor.

## 🛠️ Tools & Technologies

- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit
- **Models Used**:
  - Extra Trees Regressor
  - Random Forest
  - XGBoost
  - Decision Tree
  - Bagging Regressor
  - Linear Regressor

## 📊 Workflow Overview

1. **Data Acquisition**  
   Collected agricultural and weather datasets (rainfall, temperature, pesticide usage, etc.)

2. **Data Preprocessing**  
   - Missing value handling  
   - Normalization/standardization  
   - Label encoding (if required)

3. **Feature Engineering**  
   - Correlation-based feature selection  
   - Temporal trend analysis  
   - Interaction feature creation

4. **Model Training**  
   - Trained multiple regression models using k-fold cross-validation  
   - Performed hyperparameter tuning

5. **Evaluation Metrics**  
   - R² Score  
   - MAE (Mean Absolute Error)  
   - RMSE (Root Mean Squared Error)

6. **Interpretation & Visualization**  
   - Feature importance plots  
   - Model comparison graphs  


## 📈 Results Summary

- Extra Trees showed superior performance in terms of accuracy and speed.
- Integration of environmental and process-based features improved predictive power significantly.
- The final model achieved **R² of 0.87**, demonstrating reliable performance in yield prediction.


## 🚀 Future Work

- Integration with satellite imagery for spatial yield forecasting
- Real-time predictions with edge deployment
- Inclusion of economic and socio-political factors in prediction models

## 🤝 Contributions

Contributions are welcome! Please raise an issue or submit a pull request.



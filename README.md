# Resale-car-price-prediction

## Summary

   This project focuses on building a machine learning model to predict the resale value of used cars based on various features such 
    as mileage, age, power, seating capacity, transmission, fuel type, and brand.
    [GitHub](https://github.com/christina3099/Resale-car-price-prediction/blob/main/Resale_Car_Value_Predictor.ipynb) ,
    [Kaggle Writeup](https://www.kaggle.com/writeups/christinastalin/car-resale-price-prediction-using-machine-learning)


## 🎯 Background

The resale car market is a dynamic space where multiple factors — such as brand reputation, mileage efficiency, ownership history, and fuel type — influence the perceived value of a car.

The goal of this project was to:

  * Understand the key drivers behind used car resale prices.

  * Build predictive models that can estimate car prices with high accuracy.

  * Provide actionable insights for buyers, sellers, and dealerships to make informed decisions.

By combining data analysis and machine learning, this project delivers both interpretability (which features matter) and predictive performance (how well the model estimates prices).

## Highlights:

  * **Data Wrangling & Cleaning:** Handling missing values, parsing mixed-format columns (e.g., "Mileage: 18.9 kmpl" → 18.9), and dealing with outliers.

  * **Hypothetical Analysis:** Analysing business/domain based questions and uncovering relation between age of car and the resale value, Fuel type Vs Price, Transmission Vs price, etc.

  * **Feature Engineering:** Extracting brand and car model from textual names, encoding categorical variables, and creating domain-specific features (e.g., brand-level median mileage).

  * **Exploratory Data Analysis (EDA):** Performing statistical analysis and creating visual insights on how features like transmission type, fuel type, ownership, and brand impact resale price.

  * **Machine Learning Modeling:** Experimenting with regression models (Linear Regression, Random Forest, Gradient Boosting, XGBoost) and comparing performance using metrics like RMSE and R².

  * **Model Evaluation & Trade-offs:** Comparing models in terms of accuracy, interpretability, and computational efficiency.

  * **Visualization & Communication:** Presenting results in intuitive charts and tables for clear storytelling.

## 🔮 Future Work

* Hyperparameter tuning with GridSearchCV

* Larger dataset for better generalization

* Deployment as a web app (Streamlit/FastAPI)


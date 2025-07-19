# Key Factors in Global Freelancer Ratings

This README provides a description of the analysis performed in the `Key_Factors_in_Global_Freelancer_Ratings.ipynb` notebook.

## Project Description

This project is a comprehensive exploration of a global freelancers dataset, focusing on identifying the key factors that influence their ratings. **This kernel is based on and forked from an insightful original work by Devrai Brian Risk, with additional modifications and improvements made.** The notebook covers data preparation, visualization, and predictive modeling to understand the dynamics contributing to freelancer performance.

## Key Features and Analysis

* **Data Cleaning:** Addresses issues such as non-numeric characters in the hourly rate column to ensure data integrity.
* **Data Visualization:** Multiple visualizations are generated to uncover relationships and distributions within the dataset, providing insights into freelancer behavior.
* **Predictive Modeling:** A Random Forest Regressor is utilized to build a predictive model capable of estimating freelancer ratings.
* **Model Evaluation:** The model's performance is assessed using the R² score, indicating the strength of the model's predictions.
* **Feature Importance Analysis:** An analysis is conducted to identify which factors, such as years of experience and hourly rate, exert the most influence on freelancer ratings.

## Future Work

For future analysis, the following enhancements could be considered:

* **One-Hot Encoding:** Diving deeper into categorical predictors by using techniques like one-hot encoding for skills, language, and country.
* **Model Experimentation:** Experimenting with alternate models and hyperparameter tuning to potentially improve predictive performance.
* **Time-Series Data Incorporation:** Incorporating time-series data, if available, to study freelancer activity trends over time.

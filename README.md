
# Medical Insurance Cost Prediction 🏥📊

An End-to-End Machine Learning project utilizing **Linear Regression** to estimate annual medical insurance premiums based on patient demographic and lifestyle data.

## Project Overview
* **Objective:** Predict individual medical charges based on attributes like age, BMI, and smoker status.
* **Key Finding:** Exploratory data analysis revealed that smoking status is the most significant driver of costs, adding an average of over $23,000 to baseline patient premiums.
* **Performance:** Achieved a baseline model accuracy (**R² Score**) of **77.77%** using Scikit-Learn.

## Technologies Used
* Python 
* Pandas & NumPy (Data Manipulation)
* Seaborn & Matplotlib (Data Visualization)
* Scikit-Learn (Machine Learning Pipeline)

## Key Results
* **Scenario A (25yo, Fit, Non-Smoker):** Estimated Bill: `$1,959.36`
* **Scenario B (25yo, Fit, Smoker):** Estimated Bill: `$25,634.73`

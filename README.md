# Fertilizer_Optimizer

# 📌 Overview

Fertilizer optimizer is for recommendation of correct and optimized use of fertilizer
The Fertilizer Optimizer is an AI-based tool built using Python that recommends the most suitable fertilizer type and quantity based on various agronomic factors. This project uses machine learning (Random Forest) to analyze multiple parameters such as crop type, soil nutrient levels (N-P-K), temperature, humidity, and rainfall. The model provides intelligent fertilizer recommendations to improve crop yield and reduce over-fertilization.


# 🔍 Problem Statement 

Farmers often struggle with selecting the correct fertilizer type and applying the right quantity. Excess or improper use of fertilizers can degrade soil quality, harm the environment, and affect productivity. This system aims to address:

* Fertilizer overuse or underuse.
* Environmental concerns due to improper application.
* Lack of tailored recommendations for each crop-soil-weather combination.

# 🧠 Machine Learning Model 

Algorithm Used: Random Forest Classifier / Regressor

Why Random Forest?

* High accuracy for classification tasks.
* Handles both numerical and categorical data.
* Resistant to overfitting.

# 🧪 Input Parameters 

The model takes the following inputs:

  

| Feature     | Description                             |
| ----------- | --------------------------------------- |
| Crop        | Name of the crop (e.g., Rice, Wheat)    |
| N, P, K     | Nitrogen, Phosphorus, Potassium levels  |
| Temperature | In degrees Celsius                      |
| Humidity    | In percentage (%)                       |
| Rainfall    | In millimeters (mm)                     |
| Soil Type   | (Optional) Type or pH level of the soil |


# 🖥️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib (for visualization)
* CSV Dataset
* HTML
* CSS
* Java Script


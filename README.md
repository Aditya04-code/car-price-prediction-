# Car Price Prediction

## Project Overview  
In this project, I developed a **Car Price Prediction** model using **Linear Regression**. The model predicts the price of a car based on 26 different parameters, such as **horsepower**, **engine size**, **curb weight**, **car length**, and **city miles per gallon**. The goal of this project is to showcase how linear regression can be applied to a real-world problem and provide insights into car pricing.

## Objective  
The objective of this project is to create a model that can predict the price of a car based on a set of features. By using a linear regression model, the project aims to determine how each feature influences the price and predict the price for any given set of car characteristics.

## Dataset  
The dataset used in this project consists of multiple features. Some of the important features used for predicting the price include:
- **Horsepower**
- **Engine size**
- **Curb weight**
- **Car length**
- **City MPG**

These features are used to train the model, which will then predict the price of a car based on these attributes.

## Methodology  
1. **Data Preprocessing**:  
   The first step was to clean the data by handling missing values, encoding categorical variables, and normalizing numeric features. This ensures that the data is in a suitable format for training the model.

2. **Feature Selection**:  
   The model uses multiple features to predict car prices. Feature selection techniques were applied to ensure that only the most relevant features were used to improve model performance.

3. **Linear Regression Model**:  
   I employed **Linear Regression** to develop the model. This technique was selected for its simplicity and effectiveness in predicting a continuous target variable (car price) based on a set of independent features.

4. **Model Evaluation**:  
   The model's performance was evaluated using various metrics such as **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared** to assess its accuracy and the relationship between the independent variables and the car price.

5. **Prediction**:  
   Once the model was trained, it was used to predict car prices for new data points, providing valuable insights for anyone looking to estimate car prices based on given attributes.

## Technologies Used  
- **Python**  
- **Pandas** (for data manipulation)  
- **Scikit-learn** (for Linear Regression)  
- **Matplotlib / Seaborn** (for data visualization)  
- **NumPy** (for numerical operations)

## Results  
The linear regression model successfully predicted car prices with good accuracy, and the evaluation metrics showed that the model had a decent fit for the data. The model can be used as a basic reference for estimating car prices based on the selected parameters.

## Conclusion  
This project demonstrates the power of **Linear Regression** in solving real-world problems such as predicting car prices. With further improvements like using more advanced algorithms or incorporating additional data, the model could become even more accurate.

## Live Demo  
Unfortunately, there is no live demo for this project, but the model can be easily run locally with the provided code.

## How to Run  
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya04-code/car-price-prediction.git

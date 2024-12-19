**Company**: CODTECH IT SOLUTIONS

**ID**: CTO8DFJ

**Domain**: Machine Learning

**Duration**: December 2024 to January 2025

**Mentor**: NEELA SANTHOSH KUMAR

### **Overview of the Project**

#### **Project**: Housing Price Prediction using Linear Regression  

![image](https://github.com/user-attachments/assets/bde447b5-28af-41b2-8952-6bfdb6c1acd1)


#### **Description**  
This project implements a **Linear Regression model** to predict housing prices based on key features such as:  
- **Square Footage**: The size of the house in square feet.  
- **Number of Bedrooms**: The total number of bedrooms in the house.  
- **Location Factor**: A multiplier representing the desirability of the location (e.g., city tiers).  

The dataset is **synthetically generated** within the program to mimic real-world housing market conditions. This ensures the flexibility of testing and avoids reliance on external data sources. The housing price is calculated using a weighted formula with added random noise to simulate realistic variations in price trends.  

#### **Features**
- **Data Generation**: Automatically creates a dataset with 500 samples, including features and target variables.  
- **Linear Regression Model**: Trains a model to predict housing prices with features as input.  
- **Performance Evaluation**: Evaluates the model using key metrics such as **Mean Squared Error (MSE)** and **R-squared score**.  
- **Custom Prediction**: Demonstrates model predictions for example inputs.  

#### **Libraries Used**
- **Numpy**: For numerical computations.  
- **Pandas**: For handling and processing tabular data.  
- **Scikit-learn**: For implementing the Linear Regression model and evaluation metrics.  

#### **Results**
- **Coefficients and Intercept**: The model reveals the contribution of each feature to the housing price.  
- **Model Performance**: Metrics such as MSE and R-squared show the accuracy of the predictions.  
- **Custom Predictions**: Predicts prices for specific combinations of house size, number of bedrooms, and location.  

#### **How It Works**
1. Generate a dataset programmatically with features like square footage, bedrooms, and location factor.  
2. Split the dataset into **training** and **testing** subsets.  
3. Train a **Linear Regression model** on the training data.  
4. Evaluate the model on the testing data to measure accuracy.  
5. Use the trained model to make predictions for new inputs.  

#### **Future Enhancements**
- Incorporate additional features like the age of the house or neighborhood amenities.  
- Visualize predictions and trends using `matplotlib` or `seaborn`.  
- Deploy the model using a web application framework such as **Flask** or **FastAPI** for real-time user interaction.  

This project serves as a foundational example for using machine learning techniques to solve real-world regression problems, particularly in predicting housing prices.  

Feel free to explore the code, suggest improvements, or contribute to the repository!  

Name:RAGUTHU YAMUNA
Company:CODTECHITSOLUTIONS
ID:CT12DS2502
Domain:Machine Learning
Duration:sept to november 2024

OVERVIEW OF THE PROJECT
Project:Linear Regression on Housing prices like
Square footage
Number of bedrooms
Locations

![Screenshot (207)](https://github.com/user-attachments/assets/d426e6ac-a961-4641-8941-ef6f83194560)


![Screenshot (208)](https://github.com/user-attachments/assets/c0ec58d5-f040-45aa-a027-36ec10b7dc75)

![Screenshot (209)](https://github.com/user-attachments/assets/0a1bcea8-4c48-426d-8c22-1355051642f4)














Objective
/* LINEAR REGRESSION OF SQUARE FOOTAGE ON HOUSING PRICES*/

Dataset:

We create a simple dataset with two columns: square_footage (independent variable) and price (dependent variable).
Model:

The linear regression model is trained using the square_footage to predict the price of a house.
Model Training:

We split the data into training and testing sets. The model learns from the training data and is evaluated using the testing data.
Evaluation Metrics:

Mean Squared Error (MSE): Measures how close the predictions are to the actual prices.
R-squared (R²): Measures how well the model fits the data (higher values indicate a better fit).
Intercept and Coefficient:

Intercept: The predicted price when square footage is zero.
Coefficient: The rate at which the price increases for each additional square foot.
Plot:

The scatter plot shows the actual data points, and the red line represents the fitted regression line.

/*LENEAR REGRESSION ON NUMBER OF BED ROOMS IN HOUSING PRICES*/
Dataset:

We create a dataset with two columns: bedrooms (independent variable) and price (dependent variable).
Model:

A linear regression model is trained using the bedrooms to predict the price of a house.
Model Training:

We split the data into training and testing sets. The model learns from the training data and is evaluated using the testing data.
Evaluation Metrics:

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted prices.
R-squared (R²): Measures how well the model fits the data (a value closer to 1 indicates a better fit).
Intercept and Coefficient:

Intercept: The predicted price when the number of bedrooms is zero.
Coefficient: Indicates the change in price for every additional bedroom.
Plot:

The scatter plot shows the actual data points, and the red line represents the fitted regression line.
/*LINEAR REGRESSION OF LOCATION ON HOUSING PRICES*/

Data:

We have a dataset of location (categorical data) and price (numerical data). Locations like "Downtown," "Suburb," and "Rural" are categories that need to be converted to numerical values.
One-Hot Encoding:

We use one-hot encoding to convert the location feature into multiple binary columns (one for each location). For example, if there are three locations ("Downtown," "Suburb," and "Rural"), they will be transformed into three columns: location_Downtown, location_Suburb, and location_Rural.
Linear Regression:

The linear regression model is trained on the one-hot encoded location features and the corresponding housing prices.
Evaluation:

Mean Squared Error (MSE): Measures how close the predicted prices are to the actual prices.
R-squared (R²): Indicates how well the model fits the data.
Coefficients:

The coefficients correspond to each one-hot encoded location, representing how much the price increases or decreases for a house in a particular location compared to the baseline (intercept).
Plot:

A scatter plot is generated comparing the actual vs. predicted prices. The red line represents a perfect prediction line (actual = predicted).

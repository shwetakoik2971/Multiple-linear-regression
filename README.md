# Experiment - Multiple Linear Regression (Car Price Prediction)

## Aim

To predict the selling price of cars using Multiple Linear Regression with Python and Scikit-learn.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Label Encoder
- Google Colab
- Multiple Linear Regression

## Dataset

Car Data Dataset (`car data.csv`)

The dataset contains 301 records and 9 columns:
- Car Name
- Year
- Selling Price
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

## Procedure
1. Import the required Python libraries.
2. Load the car dataset using Pandas.
3. Display the dataset and check its shape.
4. Check for missing values.
5. Identify and remove duplicate records.
6. Convert categorical columns into numerical values using Label Encoder.
7. Select independent and dependent variables.
8. Split the dataset into training and testing sets (80:20).
9. Create a Multiple Linear Regression model.
10. Train the model using training data.
11. Predict car selling prices using testing data.
12. Evaluate the model using MAE, MSE and R2 Score.

## Result

The Multiple Linear Regression model was successfully implemented to predict car selling prices.

The following results were obtained:
- Initial dataset: 301 records and 9 columns.
- Duplicate records found: 2.
- Duplicate records after removal: 0.
- Mean Absolute Error (MAE): 1.22
- Mean Squared Error (MSE): 3.53
- R2 Score: 0.8468 (84.68%)

The model achieved an R2 Score of approximately 84.68%.

## Author

Shweta Koik

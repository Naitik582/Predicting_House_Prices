<h1>Predicting House Prices with Linear Regression</h1>

**Project Overview**

• The objective of this project is to build a predictive model using linear regression to estimate house prices based on relevant features in the dataset. This project involves data exploration, feature selection, model training, evaluation, and visualization.

**Dataset**

• The dataset used for this project contains numerical and categorical features relevant to house pricing. The key attributes include:

  price: Target variable (house price)

  area: Size of the house

• bedrooms, bathrooms, stories: Structural characteristics of the house

• mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus: Categorical attributes converted using Label Encoding

• parking: Number of parking spaces available


**Steps Involved**

**1. Data Exploration & Cleaning**

• Loaded the dataset using Pandas.

• Displayed dataset structure, summary statistics, and handled missing values.

• Applied Label Encoding to categorical features.


**2. Feature Selection**

• Defined independent variables (features) and the dependent variable (house price).


**3. Model Training**

• Split the dataset into training (80%) and testing (20%) sets.

• Trained a Linear Regression model using Scikit-Learn.


**4. Model Evaluation**

• Predicted house prices using the test dataset.

• Evaluated performance using:

• Mean Squared Error (MSE): 1771751116594.0352

• R-squared Score (R²): 0.6495



**5. Visualization**

• Created a scatter plot to compare actual and predicted prices.


**Dependencies**

The following Python libraries were used:

• Pandas

• NumPy

• Matplotlib

• Seaborn

• Scikit-Learn


**How to Run the Project**

1. Upload the dataset (Housing.csv) to Google Colab or a local Jupyter Notebook.


2. Execute the provided code sequentially.


3. Observe the model’s evaluation metrics and visualization.



**Results & Insights**

• The model achieves an R² score of 0.6495, indicating a moderate correlation between the features and house prices.

• Further improvements can be made by feature engineering, removing outliers, or trying advanced regression techniques.


**Conclusion**

• This project demonstrates the implementation of Linear Regression for house price prediction, covering data preprocessing, model training, evaluation, and visualization.


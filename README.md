# OIBSIP_03
### Car Sales Price Predictor

This project aims to predict the selling price of cars based on various features such as mileage, brand, and age. The model was developed using Python and scikit-learn library.

---

#### Dataset
The dataset used for this project is the "Car Data" dataset, which contains information about various cars including their selling price, present price, mileage, fuel type, and other relevant features.

---

#### Data Preprocessing
- Checked for null values (no null values found)
- Removed outliers from the columns 'Selling_Price', 'Present_Price', and 'Driven_kms'
- Calculated the age of cars using the 'Year' column and the current year (2024)

---

#### Feature Engineering
- Encoded categorical columns ('Fuel_Type', 'Selling_Type', 'Transmission') using LabelEncoder

---

#### Model Building
- Split the dataset into training and testing sets
- Trained four different regression models (Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, XGBoost Regressor)
- Selected the Gradient Boosting Regressor as the best performing model based on the R2 score (0.9591)

---

#### Saving the Model
- Saved the trained model (Gradient Boosting Regressor) using joblib for future use

---

#### User Interface
- Created a simple user interface using Tkinter for users to input the car details and get a predicted selling price

---

#### Usage
1. Clone the repository to your local machine
2. Install the required libraries using `pip install -r requirements.txt`
3. Run the Tkinter application `car_price_prediction_ui.py` to predict the car's selling price

---

#### Future Improvements
- Include more features such as car model, engine size, and condition for better predictions
- Explore other machine learning algorithms for potentially better results

---

#### References
- Python
- scikit-learn
- pandas
- numpy
- Tkinter
- joblib

---

Feel free to customize this README file to include more details about your project and its implementation.

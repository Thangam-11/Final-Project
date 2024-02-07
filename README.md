# Food Price Inflation :

**Introduction**:
            The dataset comprises estimates of food prices, aiming to capture local price fluctuations in regions where people are vulnerable to localized price surges. These estimates are generated using a machine-learning algorithm that predicts ongoing subnational price surveys, often achieving accuracy comparable to direct price measurements.

**Purpose**:
            The primary goal of this dataset is to provide a more accurate representation of food price trends in rural or impoverished areas, where traditional sources of consumer prices may face delays or offer only aggregated data. This information is valuable for policymakers, researchers, and organizations working in areas with large populations living in fragile conditions.

**Key Technologies and Skills**:

Python
Numpy
Pandas
Scikit-Learn
Matplotlib
Seaborn
Pickle

**Data Preprocessing**:

**Handling Missing Values**:

Identifying Missing Values for each feature.Utilized the groupby method on the missing values column to create subsets of the data for each country and Imputing with Mean Values.using the transform function with a lambda expression. The use of the mean value ensures that imputed values are representative of the overall distribution within each country.

**Encoding and Data Type Conversion**: 

To prepare categorical features for modeling, we employ LabelEncoder encoding. This technique transforms categorical values into numerical representations based on their intrinsic nature and their relationship with the target variable.

**Algorithm Selection:**

After thorough evaluation, XGBRegressor, demonstrate commendable testing accuracy. Upon checking for any overfitting issues in both training and testing, both models exhibit strong performance without overfitting concerns. I choose the Random Forest Regressor for its ability to strike a balance between interpretability and accuracy, ensuring robust performance on unseen data.

**Hyperparameter Tuning with GridSearchCV and Cross-Validation:**

To fine-tune our model and mitigate overfitting, we employ GridSearchCV with cross-validation for hyperparameter tuning. This function allows us to systematically explore multiple parameter values and return the optimal set of parameters. {learning_rate': 0.2, 'max_depth': 5, 'n_estimators': 150}

**Contributing**

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.

**Contact**

📧 Email: thangamani1128@gmail.com

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.












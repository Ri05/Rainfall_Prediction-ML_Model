# Rainfall Prediction Model

#### Table of Contents
- Project Overview
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Development
- Best Model Performance
- Further Enhancements
- Getting Started
- Contributing
- License

### Project Overview
The goal of this project is to build a reliable rainfall prediction model using historical weather data from Sydney. This involves handling missing values, creating dummy variables, converting date columns, and applying transformations to skewed data.

### Data Preprocessing
- **Handling Missing Values**: Imputation techniques are used to fill in missing data.
- **Creating Dummy Variables**: One-hot encoding is applied to categorical features.
- **Date Conversion**: Year, month, and day features are extracted from the date column.
- **Log Transformation**: Skewed numerical variables are normalized using log transformations.

### Exploratory Data Analysis (EDA)
- **Visualizing Key Variables**: Joint plots are used to understand relationships between variables.
- **Identifying Outliers and Skewness**: Outliers are identified and addressed, and skewness is corrected through appropriate transformations.

### Model Development
Several machine learning models were developed and evaluated:
- **Logistic Regression**
- **Linear Discriminant Analysis (LDA)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Ensemble Techniques**:
  - Bagging with Random Forest
  - Random Forest with Grid Search
  - Gradient Boosting
  - AdaBoost
  - XGBoost

### Best Model Performance
The best-performing model was **Gradient Boosting**, achieving an accuracy score of approximately **0.8443** after hyperparameter tuning with grid search.

### Further Enhancements
To further improve the model:
- Advanced hyperparameter tuning
- Enhanced feature engineering
- Model stacking
- Cross-validation
- Addressing class imbalance
- Ensemble of ensemble methods

### Getting Started

For detailed implementation and execution, please refer to the [Rainfall_Prediction ML_Model.ipynb](Rainfall_Prediction_ML_Model.ipynb).

### Contributing

Contributions are welcome. Here’s how you can contribute:

1. **Fork the Repository**.
2. **Create a New Branch** for your feature or bug fix.
3. **Commit Your Changes** with a meaningful commit message.
4. **Open a Pull Request**.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to explore this project and contribute to improve this rainfall prediction model.

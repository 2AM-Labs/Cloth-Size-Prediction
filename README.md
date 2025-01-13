# Cloth-Size-Prediction 👗👕👖

## Project Description
The **Cloth Size Prediction** project focuses on predicting the appropriate clothing size for individuals based on features such as height, weight, age, and other relevant attributes. Leveraging advanced machine learning techniques, this project provides a systematic approach to improving size recommendations, enhancing customer satisfaction, and reducing the rate of size-related returns in the clothing industry. 

Through rigorous data preprocessing, exploratory data analysis (EDA), and model evaluation, the project bridges theoretical concepts with practical implementations to address challenges in the retail and fashion sectors.

---

## Project Structure

```
Cloth-Size-Prediction/
├── notebooks/          
├── README.md           
└── requirements.txt 
```

---

## Workflow

### **1. Data Exploration**
- Perform exploratory data analysis (EDA) to understand data distributions, correlations, and trends.
- Visualize relationships between features (e.g., height, weight) and the target variable (clothing size).
- Identify and handle outliers or missing data.

### **2. Data Preprocessing**
- **Handle Missing Values:**
  - Use mean, median, or predictive models to impute missing data.
- **Feature Engineering:**
  - Create new features such as Body Mass Index (BMI) to enhance predictions.
  - Encode categorical features (e.g., gender) using one-hot encoding.
- **Scaling and Normalization:**
  - Standardize numerical features like height and weight to improve model performance.

### **3. Modeling**
- Train regression models to predict clothing size using:
  - **Linear Regression:** A baseline model for prediction.
  - **Random Forest Regressor:** To capture non-linear relationships.
  - **XGBoost Regressor:** For high-performance predictions with gradient boosting.

### **4. Model Evaluation**
- Evaluate model performance using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Use cross-validation to ensure generalizability of the model.

### **5. Result Interpretation**
- Visualize residuals, feature importance, and prediction accuracy.
- Document insights on key predictors of clothing size, such as height, weight, and gender.

---

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/2AM-Labs/Cloth-Size-Prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Cloth-Size-Prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook for data exploration and modeling:
   ```bash
   jupyter notebook notebooks/cloth_size_analysis.ipynb
   ```

---

## Technologies Used

- **Programming Language:** Python 3.9+
- **Libraries and Tools:**
  - **Pandas:** For data manipulation and cleaning.
  - **NumPy:** For numerical computations.
  - **Scikit-learn:** For machine learning models and evaluation.
  - **XGBoost:** For gradient boosting.
  - **Matplotlib & Seaborn:** For data visualization.
  - **Jupyter Notebook:** For interactive analysis and documentation.

---

## Dataset Information
- **Attributes:**
  - Height (in cm)
  - Weight (in kg)
  - Age (in years)
  - Gender (e.g., Male, Female)
  - Target variable: Clothing Size (numerical or categorical)
- **Data Sources:** Provided dataset with anonymized customer information.

---

## Results and Analysis
- **Model Performance:**
  - Linear Regression: R² = ...
  - Random Forest: R² = ...
  - XGBoost: R² = ...
- **Key Insights:**
  - Height and weight are the most significant predictors of clothing size.
  - Gender differences also play an important role in size determination.

---

## Documentation and Resources
- **Presentation Deck:** [Canva Cloth Size Presentation](https://www.canva.com/design/DAFx9r53zes/XoIlXjV4QUuI5yxpIoUVMw/view?utm_content=DAFx9r53zes&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h38437c0df9)
- **Exploratory Notebooks:** Jupyter notebooks detailing data exploration and modeling steps are available in the `notebooks/` folder.
- **Technical Reports:** Additional findings and documentation are in the `docs/` folder.

---

## Contribution Guidelines

1. Fork this repository.
2. Create a new branch for features or fixes:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Create a pull request on GitHub.

---

# requirements.txt

```
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
jupyter
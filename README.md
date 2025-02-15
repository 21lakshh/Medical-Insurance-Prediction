# **Medical Insurance Prediction** 
This project aims to predict medical insurance costs based on various factors such as age, BMI, number of children, smoking status, and region. The dataset used for this project had no missing values, and categorical features were encoded into numeric values for model training.

---
### **Features**  
The dataset includes property attributes such as:  

- age 
- sex 
- bmi 
- children 
- smoker 
- region 
- charges

## Exploratory Data Analysis (EDA)
The dataset was analyzed using various visualizations:
- **Pie Charts**:
  - Gender Distribution
  - Smoker Distribution
  - Regional Distribution
- **Histogram**:
  - BMI Distribution
  - Number of Children per Family

## Data Preprocessing
- Encoded categorical features (`sex`, `smoker`, `region`) into numeric values.
- Scaled numerical features where necessary.

## Model Used
The model tested for this task was **Linear Regression**.

## Performance Metrics
| Dataset  | R² Score |
|----------|---------|
| Training Data | 0.75 |
| Testing Data | 0.70 |

## Dependencies
Ensure you have the following Python libraries installed:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results
The Linear Regression model showed promising results with an R² score of **0.75** on training data and **0.706** on testing data. Further model improvements could include feature engineering and trying more complex models such as Decision Trees or Random Forest.

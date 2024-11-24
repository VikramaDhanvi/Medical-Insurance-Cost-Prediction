# Medical-Insurance-Cost-Prediction
# **Insurance Cost Prediction Using Machine Learning**

This project predicts insurance costs based on user-provided attributes such as age, gender, BMI, smoking habits, and region. Two machine learning models, **Random Forest Regression** and **Linear Regression**, are trained and evaluated to determine the best-performing algorithm for the prediction task.

---

## **Features of the Project**
- **Data Preprocessing**: 
  - Handles missing values (if any).
  - Encodes categorical variables (e.g., `sex`, `smoker`, `region`).
- **Visualizations**:
  - Distribution plots for BMI, age, and gender.
- **Model Comparison**:
  - **Random Forest Regression** and **Linear Regression** are implemented and evaluated.
  - The model with the higher \( R^2 \) score is selected as the best model.
- **Prediction**:
  - Predicts the insurance cost for user-input features using the best model.

---

## **Technologies and Libraries Used**
1. **Programming Language**: Python
2. **Libraries**:
   - **pandas**: For data manipulation and analysis.
   - **numpy**: For numerical operations.
   - **matplotlib** and **seaborn**: For data visualization.
   - **scikit-learn**: For machine learning models and evaluation metrics.

---

## **Dataset**
The dataset used in this project (`insurance.csv`) contains the following columns:
- `age`: Age of the person.
- `sex`: Gender (male, female).
- `bmi`: Body Mass Index.
- `children`: Number of children covered by health insurance.
- `smoker`: Smoking habits (yes, no).
- `region`: Region of residence (southeast, southwest, northeast, northwest).
- `charges`: Medical insurance costs (target variable).

---

## **How the Project Works**
1. **Load and Inspect Dataset**:
   - Displays basic statistics, shape, and missing values.
2. **Data Visualization**:
   - Plots distributions for better understanding.
3. **Data Preprocessing**:
   - Encodes categorical variables into numeric values.
   - Splits data into training and testing sets.
4. **Model Training**:
   - Trains **Random Forest Regression** and **Linear Regression** models.
5. **Model Evaluation**:
   - Computes \( R^2 \) scores for both models on training and test datasets.
   - The model with the higher \( R^2 \) score is chosen as the best model.
6. **Prediction**:
   - Predicts insurance costs for a given input using the best model.

---

## **How to Use**
1. Clone or download the repository.
2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

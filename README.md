# 🌦️ Weather Prediction

This project focuses on developing a machine learning pipeline to predict weather conditions based on historical data. The primary objectives include data preprocessing, implementing various machine learning models, and evaluating their performance.

## 📁 Project Structure

- `weather_pred.ipynb`: Jupyter Notebook containing the step-by-step implementation of the machine learning pipeline.
- `train-val.csv`: Training and validation dataset used for model development.
- `test.csv`: Test dataset used for evaluating the final model.

## 🛠️ Workflow

1. **Data Acquisition & Cleaning**
   - Load datasets (`train-val.csv` and `test.csv`) into structured formats.
   - Handle missing values and clean noisy data to ensure data quality.

2. **Exploratory Data Analysis (EDA)**
   - Visualize feature distributions to understand data characteristics.
   - Identify patterns and correlations among variables to inform feature selection.

3. **Feature Engineering & Selection**
   - Encode categorical variables appropriately.
   - Select relevant features that contribute significantly to the predictive model.

4. **Model Selection & Training**
   - Compare various machine learning algorithms, including:
     - Logistic Regression
     - Decision Trees
     - Support Vector Machines
   - Fine-tune hyperparameters using cross-validation techniques to optimize model performance.

5. **Model Evaluation & Interpretation**
   - Measure model performance using metrics such as accuracy, precision, recall, and F1-score.
   - Interpret results to derive meaningful insights and assess model effectiveness.



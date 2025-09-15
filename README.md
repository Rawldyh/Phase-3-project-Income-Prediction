# Income Prediction Project

##  Overview
This project focuses on predicting whether an individual's income exceeds $50K per year using the UCI Adult Census dataset. 
It is a **binary classification problem** that demonstrates a full machine learning pipeline from preprocessing to evaluation.

---

##  Dataset
- **Source**: UCI Adult Census dataset
- **Rows**: ~32,000
- **Features**: Age, Education, Occupation, Workclass, Hours per week, etc.
- **Target Variable**: Income (<=50K, >50K)

---

##  Workflow
1. **Data Preprocessing**
   - Handle missing values (e.g., '?' entries)
   - Encode categorical variables (One-Hot, Label Encoding)
   - Feature scaling for numerical features
   - Train-test split

2. **Exploratory Data Analysis**
   - Distribution of income levels
   - Relationship between education, work hours, occupation, and income
   - Class balance check

3. **Modeling**
   - Algorithms tested:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Gradient Boosting
   - Hyperparameter tuning with GridSearchCV

4. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Confusion matrix and classification report

---

##  Results
- Best performing model: **Random Forest**
- Achieved accuracy: **~84%**
- Balanced precision and recall
- Strong predictive power for features such as education, hours worked, and occupation

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/income-prediction.git
   cd income-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or script:
   ```bash
   jupyter notebook Income_Prediction.ipynb
   ```

---

## Future Work
- Feature engineering for improved performance
- Try deep learning models
- Monitor real-world performance

---

## License
This project is licensed under the MIT License.

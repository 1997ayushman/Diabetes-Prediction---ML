#### Objective:
This notebook aims to build and compare machine learning models to classify the early-stage onset of diabetes using a medical dataset with 16 features and a target variable.

#### Dataset Overview:
- **Features**: Includes attributes like *Age*, *Gender*, *Polyuria*, *Polydipsia*, etc., with binary responses (*Yes/No*).
- **Target**: *Class* (Positive/Negative for diabetes).

---

### Workflow:
1. **Data Preparation**:
   - Checking for missing values, data types, and statistical summaries.
   - Encoding categorical variables (Yes/No → 0/1).

2. **Exploratory Data Analysis (EDA)**:
   - Gender-based analysis reveals age-specific diabetes trends.
   - Key features like *Polyuria* and *Polydipsia* strongly correlate with diabetes.

3. **Feature Normalization**:
   - Applied normalization to prepare data for model training.

4. **Model Building**:
   - **Logistic Regression**
   - **Decision Tree Classifier**
   - **Support Vector Classifier**
   - **Random Forest**
   - **K-Nearest Neighbors (KNN)**

5. **Evaluation Metrics**:
   - Used classification metrics like accuracy, precision, recall, and F1 score.

---

### Key Findings:
1. **Polyuria and Polydipsia**:
   - Strong predictors of diabetes, with high positive rates in affected individuals.

2. **Weakness and Sudden Weight Loss**:
   - Moderate correlation with diabetes onset.

3. **Model Insights**:
   - Random Forest and Support Vector Machine showed the best predictive accuracy compared to other models.

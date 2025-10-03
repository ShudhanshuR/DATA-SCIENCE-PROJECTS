## Project Workflow

1. **Data Cleaning**
   - Handling missing values for Age, Cabin, and Embarked columns.
   - Converting relevant columns to appropriate data types.

2. **Outlier Handling**
   - Winsorization applied on numerical columns to cap extreme values.

3. **Exploratory Data Analysis (EDA)**
   - Visualizations to understand survival patterns across features like Sex, Age, and Embarked.

4. **Feature Engineering**
   - Dropping irrelevant columns (`PassengerId`, `Name`, `Ticket`, `Cabin`, `Parch`).
   - Encoding categorical variables for model input.

5. **Model Building**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - k-Nearest Neighbors (kNN)

6. **Hyperparameter Tuning**
   - Grid Search applied on Random Forest for optimal parameters.

## Results
- Each model was evaluated using:
  - Accuracy
  - Classification Report
  - Confusion Matrix
- **Best Performance:** Tuned Random Forest provided the highest accuracy among all models.

## How to Run
1. Place `train.csv` and `titanic_analysis.py` in the same folder.  
2. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn


Shudhanshu Ranjan
Data Science Enthusiast | Machine Learning Practitioner

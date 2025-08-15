## ⚙️ Methodology
1. **Data Loading & Exploration**: Analyzed missing values, distributions, and relationships between variables.
2. **Feature Engineering**:
   - Extracted titles from names
   - Created new family size feature
   - Encoded categorical variables
   - Filled missing age and embarked values
3. **Model Training**:
   - Experimented with **4 different models**:
     - Logistic Regression
     - Random Forest Classifier
     - XGBoost Classifier
     - CatBoost Classifier ✅ *(Best Performance)*
   - Performed **GridSearchCV** for hyperparameter tuning
4. **Evaluation**:
   - Used accuracy, precision, recall, and F1-score
   - Achieved **~82.68% accuracy** on validation set with **CatBoostClassifier**

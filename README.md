# Heart Disease Prediction using Decision Trees & Random Forests

## Objective
Build and compare Decision Tree and Random Forest models to predict heart disease using a structured dataset.

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz (for visualization)

## Dataset
Heart Disease Dataset with features like age, sex, chest pain, cholesterol, etc., and a binary target column `target`.

## Steps Followed
1. Loaded and checked the dataset for null values and data types.
2. Split the data into features (X) and target (y).
3. Performed train-test split (80% train, 20% test).
4. Trained a Decision Tree model and visualized it.
5. Trained a Random Forest model and compared accuracy.
6. Evaluated models using accuracy, confusion matrix, precision, recall, F1 score, and cross-validation.
7. Plotted feature importances.

## Future Improvements
- Use GridSearchCV for hyperparameter tuning
- Handle imbalanced data if needed
- Save models for future use

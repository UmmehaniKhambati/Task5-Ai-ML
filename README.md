# Task5-Ai-ML

#Objective

Compared Decision Tree and Random Forest classifiers on the Heart Disease dataset, checked for overfitting, and evaluate performance.

#Dataset

File: `heart.csv`
Rows: 303
Features: 14 (including target)
Target: `target` (1 = Disease, 0 = No Disease)

#Steps
1. Trained a Decision Tree and visualized it.
2. Checked overfitting and tuned `max_depth`.
3. Trained a Random Forest and compared results.
4. Checked feature importance.
5. Evaluated with 5-fold cross-validation.

Random Forest Cross-Validation:
Scores: \[1.00, 1.00, 0.9854, 1.00, 0.9854]
Mean Accuracy: 99.41%

Top Features: `cp`, `thalach`, `ca`, `oldpeak`, `thal`

#Conclusion

Random Forest gave the highest accuracy but may be overfitting.
Decision Tree with limited depth had lower accuracy but better generalization.
Further testing on external data is recommended.


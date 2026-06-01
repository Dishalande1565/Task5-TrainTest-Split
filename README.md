# Task 5: Train-Test Split & Evaluation Metrics
## AI & ML Data Analytics Internship

## Objective
To split dataset into train/test sets, train a 
Logistic Regression model and evaluate performance.

## Dataset Used
- Heart Disease Dataset
- 303 rows × 14 columns
- Target: 0=No Disease, 1=Has Disease

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Files
- Task5_TrainTest_Split.ipynb → Main notebook

## Steps Performed
1. Loaded Heart Disease Dataset
2. Split data 80% Train / 20% Test
3. Applied StandardScaler
4. Trained Logistic Regression Model
5. Predicted on Test Data
6. Calculated Accuracy, Precision, Recall
7. Plotted Confusion Matrix
8. Generated Classification Report

## Results
| Metric    | Score |
|-----------|-------|
| Accuracy  | ~85%  |
| Precision | ~84%  |
| Recall    | ~87%  |

## Key Learnings
- Train/Test split prevents overfitting
- Recall is most important for disease detection
- Confusion matrix shows detailed predictions ✅

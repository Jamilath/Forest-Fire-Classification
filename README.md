# Forest-Fire-Classification
# Forest Fire Size Prediction Using SVM

## Overview
This project uses Support Vector Machines (SVM) to classify forest fires as "small" or "large" based on the UCI Forest Fires dataset. Key steps include data preprocessing, handling class imbalance with SMOTE, and hyperparameter tuning with GridSearchCV.

## Dataset
- Source: UCI Machine Learning Repository
- Features: FFMC, DMC, DC, ISI, temp, RH, wind, rain, and one-hot encoded month/day.
- Target: size_category (small/large)

## Methodology
- Preprocessing: Scaled numerical features, used stratified train-test split.
- Model: SVM with RBF kernel and class weighting.
- Results: ~70% accuracy, with improved recall for large fires.

## Files
- `forest_fire_svm.ipynb`: Main Jupyter Notebook with code.
- `forestfires.csv`: Dataset (upload if sharing).
- `visualizations/`: Folder for images like confusion matrix.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open `forest_fire_svm.ipynb` in Jupyter Notebook.
3. Run the cells step-by-step.

## Results
- Accuracy: 70%
- Classification Report: [Paste your report here]
- Confusion Matrix: ![Confusion Matrix](visualizations/confusion_matrix.png)

## Technologies
- Python, Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib, imbalanced-learn

Feel free to fork or contribute!

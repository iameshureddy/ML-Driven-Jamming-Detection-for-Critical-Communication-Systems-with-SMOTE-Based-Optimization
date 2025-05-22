# ML-Driven-Jamming-Detection-for-Critical-Communication-Systems-with-SMOTE-Based-Optimization
This research proposes a machine learning-based approach to detect wireless signal jamming in critical communication systems, using SMOTE to address class imbalance. XGBoost outperformed other models, offering a highly accurate and stable solution for real-world jamming detection.



This repository presents a machine learning-based approach for detecting jamming attacks in communication systems. The workflow includes exploratory data analysis (EDA), model training and evaluation, and handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## Objective

To compare the performance of multiple classification models on imbalanced and SMOTE-balanced datasets for effective jamming detection.

## Repository Structure

1. EDA and data preprocessing to understand feature distributions and class imbalance.
2. Implementation and evaluation of five machine learning models:
   - K-Nearest Neighbors (KNN)
   - Random Forest
   - Support Vector Machine (SVM)
   - Logistic Regression
   - XGBoost

Each model was evaluated both with and without SMOTE.

## Evaluation Metrics

The models were assessed using the following metrics:

- Accuracy
- Log Loss Score
- Cross-Validation (3-fold)
- Precision-Recall (P-R) Curves

## Files Overview

- `checkpoints.ipynb` - Initial data analysis and preprocessing (EDA, Training and evaluation of five models with and without SMOTE using accuracy, log loss.
- `Untitled14.ipynb` - Precision-Recall (P-R) curve plotting for all models
- `Untitled15.ipynb` - Cross-validation curve generation and manual result collection

Each evaluation highlights the contrast in performance with and without SMOTE.

## Research Paper

For detailed results, comparisons, figures, and discussions, please refer to the associated research paper:

ML-Driven Jamming Detection for Critical Communication Systems with SMOTE-Based Optimization

## How to Use

1. Clone the repository to your local machine.
2. Run the notebooks in the suggested order:
   - Start with `checkpoints.ipynb` for EDA and  for metric-based evaluation
   - Explore P-R and CV curves in `Untitled14.ipynb` and `Untitled15.ipynb`
3. Final result interpretation is available in the research paper.

## Requirements

The following Python libraries are required:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- imbalanced-learn



## Contact

For any queries or additional details, please refer to the contact information provided in the research paper.

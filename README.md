# ML_BreastCancer_Classification

A supervised learning assignment for classifying breast cancer tumors (benign/malignant) using the **Breast Cancer Wisconsin dataset**.  
The project explores different classification algorithms, model selection strategies, and includes bonus work with feature selection and SVM.

## 📂 Dataset

- `cancer_train.csv` - Training data (features + label)
- `cancer_test.csv` — Test data (for model evaluation)
- `breast_cancer_description.txt` — Feature explanations

## 🧑‍💻 Main notebook

- **Assignment2_supervised_learning_flow.ipynb**

The notebook includes:
- Data loading and exploration (EDA)
- Visualizations: histogram, boxplot, correlation heatmap
- Model selection: KNN, Decision Tree, SVM (bonus)
- Feature engineering: feature scaling, SelectKBest (bonus)
- Hyperparameter tuning with GridSearchCV
- 5-fold cross-validation, macro F1-score comparison
- Final model retraining on the full train set
- Evaluation on test set: accuracy, classification report, confusion matrix

## 🚀 Bonus Work

- **SVM** (Support Vector Machine): tested with multiple kernels and regularization values
- **Feature Selection**: KNN + SelectKBest to optimize performance with fewer features

## 📝 Results

- All results, experiments, and evaluation metrics are summarized and explained in the notebook, including a clear comparison table for all models and settings.

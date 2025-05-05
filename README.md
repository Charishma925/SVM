## Objective
- Use SVMs for:
- Linear and non-linear (RBF) classification
- Hyperparameter tuning (C, gamma)
- Cross-validation for robust evaluation

## Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib

## Dataset
- Digits dataset from sklearn.datasets
- Originally multi-class (0–9 digits), we filtered it to:
- Binary classification: digits 1 vs 7
- Each sample is an 8x8 grayscale image flattened into a 64-feature vector

## Models Trained
- SVM with Linear Kernel
- SVM with RBF Kernel

## Steps Performed
- Data Preparation
- Load digits dataset
- Filter only digits 1 and 7
- Split into training and test sets (70/30)
- Model Training
- Train Linear and RBF SVMs on training data
- Evaluation

## Results
- Both Linear and RBF SVMs perform well on this binary classification task
- RBF kernel generally shows better performance after tuning
- Cross-validation ensures the model generalizes well

This machine-learning project predicts whether a high-school student will pass or fail a mathematics exam using academic and demographic information, including reading and writing scores, gender, ethnicity, parental education, and test-preparation status.
The original mathematics score is converted into a binary target: scores below 60 are classified as failure, while scores of 60 or higher are classified as success.

Methodology

- Exploratory analysis of student characteristics and exam scores.
- Analysis of correlations between mathematics, reading, and writing performance.
- Ordinal encoding of parental education and one-hot encoding of categorical variables.
- Min-max scaling of numerical features.
- Comparison of SMOTE, random oversampling, and unbalanced training.
- Comparison of PCA, LDA, sequential feature selection, and no dimensionality reduction.
- Evaluation of Perceptron, Logistic Regression, K-Nearest Neighbors, and Random Forest models.
- Hyperparameter optimization with randomized search and nested cross-validation.
- Analysis through confusion matrices, learning curves, and validation curves.

Abusive Comment Detection using Machine Learning

This project detects whether a comment is abusive or non-abusive using different Machine Learning algorithms and Natural Language Processing (NLP) techniques.

The system was developed using multiple classification models with feature engineering and hyperparameter tuning to improve prediction accuracy.

Project Objective

The main objective of this project is to:

Detect abusive comments automatically
Classify text into:
Abusive
Non-Abusive
Improve prediction accuracy using Machine Learning techniques
Compare multiple ML algorithms
Technologies Used
Python
Google Colab
Scikit-learn
Pandas
NumPy
Joblib
Machine Learning Models Used

The following Machine Learning models were implemented and evaluated:

1. Logistic Regression (LR)

Logistic Regression is a classification algorithm used for binary classification tasks.

Hyperparameters Used
C
solver
max_iter
Purpose
Fast training
Good performance for text classification
Handles linear data effectively
2. Support Vector Machine (SVM)

SVM separates abusive and non-abusive comments using an optimal boundary.

Hyperparameters Used
C
kernel
gamma
Purpose
High accuracy for text classification
Effective for high-dimensional TF-IDF features
Performs well with sparse data
Achieved Accuracy
Accuracy: 0.80
3. Naive Bayes (NB)

Naive Bayes is a probability-based classification algorithm.

Hyperparameters Used
alpha
var_smoothing
Purpose
Works efficiently for NLP tasks
Fast and lightweight model
Good baseline classifier
4. Decision Tree (DT)

Decision Tree classifies comments using tree-based decision rules.

Hyperparameters Used
max_depth
min_samples_split
Purpose
Easy interpretation
Tree-based classification
Handles nonlinear patterns
5. Random Forest (RF)

Random Forest combines multiple decision trees to improve prediction accuracy.

Hyperparameters Used
n_estimators
max_depth
criterion
Purpose
Reduces overfitting
Improves generalization
Produces stable predictions
NLP Techniques Used
1. Feature Extraction
TF-IDF Vectorization

TF-IDF (Term Frequency – Inverse Document Frequency) converts text into numerical vectors.

Purpose
Converts text into machine-readable format
Gives importance to meaningful words
Removes less important words
Parameters Used
max_features = 10000
ngram_range = (1,2)
sublinear_tf = True
2. Feature Selection
SelectKBest with Chi-Square

Feature Selection chooses the most important features from TF-IDF vectors.

Purpose
Removes unnecessary features
Reduces dimensionality
Improves model performance
Reduces training time
Technique Used
Chi-Square (chi2)
Hyperparameter Tuning

Hyperparameter tuning was used to optimize model performance.

Different parameter combinations were tested to obtain better accuracy.

Techniques Used
1. Grid Search

Grid Search automatically tests multiple combinations of hyperparameters and selects the best combination.

2. Cross Validation

Cross Validation splits the dataset into multiple parts and evaluates the model several times for reliable performance measurement.

Performance Metrics Used

The following evaluation metrics were used:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
Dataset Workflow

The project uses:

Training Dataset
Test Dataset (Unlabeled)
Original Label Dataset
Project Workflow
Upload training dataset
Clean and preprocess text
Convert text using TF-IDF
Perform feature selection
Train ML models
Apply hyperparameter tuning
Upload test dataset
Predict abusive/non-abusive comments
Upload original labels
Evaluate model accuracy
Save final prediction results
Output

The final output file contains:

Original text
Original label
Logistic Regression prediction
SVM prediction
Naive Bayes prediction
Random Forest prediction
Decision Tree prediction
Saved Files

The following files are saved after training:

LogisticRegression_Model.pkl
SVM_Model.pkl
NaiveBayes_Model.pkl
RandomForest_Model.pkl
DecisionTree_Model.pkl
TFIDF_Vectorizer.pkl
Feature_Selector.pkl
Conclusion

This project successfully detects abusive comments using Machine Learning and NLP techniques.

Among all models, SVM achieved the best performance with approximately 80% accuracy after applying feature extraction, feature selection, and hyperparameter tuning techniques.

The system can be further improved using:

Deep Learning
Transformer Models
BERT
XLM-RoBERTa
Larger datasets

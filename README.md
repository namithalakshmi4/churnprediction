# churnprediction
Customer churn is a critical problem for businesses, especially in subscription-based industries like telecom, SaaS, and banking. In this project, I build and evaluate an Artificial Neural Network (ANN) to predict whether a customer will churn or not, based on their demographic, account, and usage details.

This project demonstrates a full machine learning pipeline: from data preprocessing to ANN modeling and evaluation.

⚙️ Workflow

Data Preprocessing

Handle missing values

Convert categorical variables using pd.get_dummies


Exploratory Data Analysis (EDA)

Visualize churn distribution (imbalanced dataset check)


Model Building (ANN)

Implement ANN using Keras (TensorFlow backend)

Architecture:

Input layer (features)

Hidden layers (ReLU activation)

Output layer (sigmoid activation for binary classification)

Loss = Binary Crossentropy

Optimizer = Adam

Metrics = Accuracy, Precision, Recall, AUC

Model Evaluation

Confusion Matrix

Classification Report


Conclusion

Insights from model performance

Business recommendations for reducing churn

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (train-test split, scaling, metrics)

TensorFlow / Keras (ANN model)

 Google Colab

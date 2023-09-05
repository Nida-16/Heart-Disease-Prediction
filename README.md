# About
This data science project is focused on predicting heart disease risk using machine learning techniques. It involved data collection from a CSV source, data preprocessing, feature engineering, and the development of a neural network model using TensorFlow/Keras. The model was trained and evaluated to predict heart disease risk, contributing to healthcare decision support.


# Key Steps :
1) Data Collection and Preprocessing: Loaded a dataset named 'HeartDiseaseDataset.csv' using pandas and performed some initial data exploration.
2) Data Cleaning: Removed duplicate rows from the dataset.
3) Feature Engineering: One-hot encoded categorical features like 'sex,' 'cp,' 'exang,' 'slope,' 'ca,' and 'thal' to prepare them for modeling.
4) Splitting Data: Split the data into training and testing sets using train_test_split.
5) Feature Scaling: Scaled the features using StandardScaler to ensure all features have the same scale.
6) Model Training: Created a neural network model using TensorFlow and Keras with several layers. The model has been compiled and trained using the training data.
7) Model Evaluation: Evaluating overfit or underfit by predicting training data and comparing with test data accuracy
8) Saving the weights: Saving and loading model using "joblib"


# Technical Stack used
- Programming Languages: Python
- Libraries and Frameworks: NumPy, Pandas, Scikit-learn, Keras, TensorFlow, Matplotlib
- Model Building: Neural network model using TensorFlow/Keras
- Model Compilation: Binary cross-entropy loss, Adam optimizer
  

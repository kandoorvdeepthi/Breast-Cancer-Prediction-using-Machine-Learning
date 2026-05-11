# Breast-Cancer-Prediction-using-Machine-Learning
A Machine Learning project that predicts whether a breast tumor is malignant or benign using Logistic Regression. The project includes data preprocessing, feature scaling, model training, evaluation, and a simple prediction system built with Python and Scikit-learn.

Overview
This project uses Machine Learning to predict whether a breast tumor is Malignant or Benign based on medical diagnostic data. The model is built using Logistic Regression and trained on a breast cancer dataset.

The project demonstrates:
1. Data preprocessing
2. Feature scaling using StandardScaler
3. Model training using Logistic Regression
4. Model evaluation using accuracy score
5. Building a prediction system

Technologies Used
1. Python
2. NumPy
3. Pandas
4. Scikit-learn
5. Jupyter Notebook

Machine Learning Workflow
1. Importing the dataset
2. Data preprocessing
3. Splitting dataset into training and testing sets
4. Standardizing the data
5. Training the Logistic Regression model
6. Evaluating model accuracy
7. Making predictions

Project Structure
├── data.csv
├── breast cancer prediction.ipynb
└── README.md

Installation
Install the required libraries before running the project: pip install numpy pandas scikit-learn jupyter

How to Run
1. Clone the repository
2. Open the notebook in Jupyter Notebook
3. Run all cells step by step
  i. git clone <your-repository-link>
  ii. cd <repository-name>
  iii. jupyter notebook

Model Used
Logistic Regression : Logistic Regression is a supervised machine learning algorithm used for classification problems. In this project, it is used to classify tumors as:
1. Malignant
2. Benign

Results
The model is trained and evaluated using accuracy score from Scikit-learn. The prediction system can take input data and predict the type of tumor.

Future Improvements
Add GUI using Streamlit or Flask
Use multiple ML algorithms for comparison
Improve accuracy with feature engineering
Deploy the model as a web application

# CODSOFT-3
Iris Flower Classification- CODSOFT Internship

This project is a part of the Codsoft Data Science Internship (Task 3).

Objective:

To build a machine learning model to classify Iris flowers into three species:
- Setosa
- Versicolor
- Virginica
using their sepal length, sepal width, petal length, and petal width.

Technologies Used:
 - Python
 - Pandas, NumPy (Data Handling)
 - Matplotlib, Seaborn (Data Visualization)
 - Scikit-learn (Model Building & Evaluation)

Step Followed:

 Step 1:Data Loading and Exploration
   - Loaded dataset using pandas
   - Displayed first few records and checked info and summary stats
   - Plotted pairplot to observe class separation visually

 Step 2:Preprocessing
   - Encoded species labels using LabelEncoder
   - Split the dataset into training and testing sets (80/20)

 Step 3:Model Training
  - Used RandomForestClassifier from sklearn.ensemble
  - Trained the model on the training data

 Step 4:Model Evaluation
  - Achieved 100% accuracy on the test data
  - Verified using accuracy_score, classification_report, and confusion_matrix

 Step 5:Prediction
  - Predicted the species of a new flower based on input values
  - Output returned the actual species label

Results:

  - The model classified all 3 species perfectly from test data.
  - This confirms that the Iris dataset is linearly separable, especially with petal measurements.

Dataset
- Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

 Author:

 T Harshitha

 Codsoft Data Science Intern

 #codsoft #datascience #internship

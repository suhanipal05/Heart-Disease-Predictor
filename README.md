## 🩺 About the Model 
This is a machine learning toolkit for predicting heart disease using patient health records.
This project includes preprocessing scripts, model training (Logistic Regression & Random Forest), evaluation, visualizations, and a prediction pipeline for new user data.
<br><br>
## 📌 Dataset
Following is the dataset used to train the model\
[Heart Disease UCI Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
<br><br>
## 🧰Technologies used
1. Python 3.x Numpy for performing mathematical operations
2. Python 3.x Pandas for manipulating data
3. Python 3.x Matplotlib to build graphs gor visualisations
4. Python 3.x Seaborn to make heatmap
5. Python 3.x Scikit-learn for machine learning algorithms
6. Python 3.x Joblib to store trained model
<br><br>
## 🚀 Usage
1. Preprocessing - Handles missing values. Encodes categorical columns. Scales numeric features
2. Train Models - Trains Logistic Regression & Random Forest. Saves trained models (.pkl) in models/ folder. Generates feature importance plots
3. Evaluation - Prints accuracy scores. Displays confusion matrix heatmap. Generates classification report.
4. Prediction on new data - Preprocesses uploaded data. Loads saved model & scaler. Predicts result for new .csv file for each user.
<br><br>
## 📊 Visualisations
Examples of generated plots:
* Distribution histograms of numeric features
* Correlation heatmap
* Confusion matrix heatmap
* Random Forest feature importance
<br><br>
## ✅ Results
# Model &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Accuracy
* Logistic Regression &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~83%
* Random Forest(100 trees) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~88%
<br><br>
## 🔮 Future Work
* Add more advanced ML models (XGBoost, SVM, Neural Networks).
* Hyperparameter tuning.
* Deploy as a Flask/Django Web App or Streamlit Dashboard.
* Integration with electronic health record (EHR) systems.
<br><br>
## 👩‍💻 Author
Developed as part of a learning project during "DevTown || Disease Predictor : Save lives with AI" Bootcamp.


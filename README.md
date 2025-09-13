
# **Diabetes Prediction App**

> Predict whether a patient has diabetes using Machine Learning and Flask.

This project demonstrates how to build a **complete machine learning workflow**: from **data preprocessing and analysis** to **training multiple models** and deploying a **web application** for real-time predictions. Users can input patient data like **Glucose level, Insulin, Age, and BMI**, and the app predicts whether the patient is diabetic.

---

# **Key Features**

* Handles missing data and scales features for better model performance.
* Compares multiple algorithms: Logistic Regression, K-Nearest Neighbors, SVM, Naive Bayes, Decision Tree, Random Forest.
* Displays model accuracy to identify the best-performing algorithm.
* Provides a **Flask-based web interface** for easy input and prediction.

---

# **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/DiabetesPredictionApp.git
   ```
2. Navigate to the project folder:

   ```bash
   cd DiabetesPredictionApp
   ```
3. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   .\venv\Scripts\activate   # Windows
   source venv/bin/activate  # Linux/Mac
   ```
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
5. Run the Flask application:

   ```bash
   python app.py
   ```
6. Open your browser and visit:

   ```
   http://127.0.0.1:5000/
   ```

---

# **How to Use**

1. Enter patient information in the web form.
2. Click **Predict**.
3. The app will display whether the patient is **diabetic or not**.

---


# **Dataset**

* The dataset used is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database).
* Ensure your `model.pkl` is generated with the same versions of scikit-learn and pandas used in this project.

---

# **Notes**

* This project is for learning and demonstration purposes.
* It can be further enhanced by improving the model, adding more features, or deploying it on cloud platforms like Heroku.

---




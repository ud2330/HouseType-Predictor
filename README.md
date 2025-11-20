# HouseType Predictor

HouseType Predictor is a **Flask-based web application** that predicts the type of house suitable for a user based on key inputs like BHK, architectural style, number of stories, location type, and budget. The project provides **dynamic explanations and price guidance**, making home selection easier and more insightful.

---

## 🛠 Features

* User-friendly web interface built with Flask.
* Predicts **house type** using a trained machine learning model.
* Generates **explanation points** to justify predictions.
* Shows a **price range estimate** based on the budget.
* Handles input validation and provides **friendly error messages**.

---

## 💻 Technology Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS
* **Machine Learning:** Scikit-learn
* **Model Storage:** Joblib for saving model and encoders

---

##  Machine Learning Concept Used

This project uses **supervised learning** with a **Random Forest Classifier**:

1. **Supervised Learning**: The model is trained on a dataset containing house features (BHK, style, stories, location, budget) and the corresponding house type.
2. **Random Forest Classifier**: An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and prevent overfitting.
3. **Label Encoding**: Converts categorical features (like style and location) and target labels into numerical values for model training.
4. **Train-Test Split**: Ensures the model is evaluated on unseen data for reliable performance.

---

## Run

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Install dependencies:

```bash
pip install flask pandas scikit-learn joblib
```

3. Run the Flask app:

```bash
python app.py
```

4. Open your browser and go to `http://127.0.0.1:10000/`

---

##  Usage

1. On the homepage, click **Get Started**.
2. Fill in the form with your house preferences:

   * BHK
   * Architectural Style
   * Number of Stories
   * Location Type
   * Budget
3. Submit the form to see:

   * Predicted house type
   * Suggested price range
   * Explanation points for the prediction

---

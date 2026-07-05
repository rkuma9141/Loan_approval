# 🏦 Loan Approval Prediction System

A Machine Learning web application that predicts whether a loan application is likely to be **Approved** or **Not Approved** based on applicant information.

## 📌 Project Overview

This project uses a trained Machine Learning model to predict loan approval status. Users enter applicant details through a simple web interface, and the application instantly displays the prediction.

## 🚀 Features

* Predicts loan approval status
* Simple and responsive user interface
* Built with Flask
* Machine Learning model using Scikit-learn
* Easy to deploy on Render

## 🛠️ Technologies Used

* Python
* Flask
* NumPy
* Scikit-learn
* Pickle
* HTML
* CSS

## 📂 Project Structure

```
Loan_Approval/
│
├── app.py
├── Loan approval.pkl
├── requirements.txt
├── templates/
│   └── index.html
└── README.md
```

## 📊 Input Features

The model uses the following 11 features:

1. Gender
2. Married
3. Dependents
4. Education
5. Self Employed
6. Applicant Income
7. Coapplicant Income
8. Loan Amount
9. Loan Amount Term
10. Credit History
11. Property Area

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/rkuma9141/Loan_approval.git
```

Move into the project folder:

```bash
cd Loan_approval
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

## 📷 Application Workflow

1. Open the web application.
2. Enter all required loan applicant details.
3. Click **Predict Loan Status**.
4. The system displays either:

   * ✅ Loan Approved
   * ❌ Loan Not Approved

## 📈 Machine Learning Model

The application uses a trained classification model saved as:

```
Loan approval.pkl
```

The model predicts loan approval using the provided applicant information.

## 👨‍💻 Author

**Ravi Ranjan Kumar**

Computer Science Engineering Student

## 📄 License

This project is created for learning, practice, internships, and educational purposes.

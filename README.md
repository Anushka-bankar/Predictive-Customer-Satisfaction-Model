# Predictive Customer Satisfaction Model for E-commerce

> A machine learning project to predict customer satisfaction based on e-commerce data. This project analyzes customer reviews and identifies the factors that influence positive or negative customer experiences.

---

## 📖 Overview

This project analyzes an e-commerce dataset to build a machine learning model for predicting customer satisfaction.

The goal is to classify customer satisfaction based on factors such as order details, product information, delivery time, and other customer/order-related features.

The model can help businesses:

* Identify factors contributing to negative customer experiences
* Understand what drives customer satisfaction
* Detect potential service issues
* Improve delivery and overall customer experience
* Make data-driven business decisions

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🚀 How to Run This Project

### Prerequisites

Make sure you have **Python 3.8+** installed.

### 1. Clone the repository

```bash
git clone https://github.com/Vishal-Dabhade/Predictive-Customer-Satisfaction-Model-for-E-commerce.git
cd Predictive-Customer-Satisfaction-Model-for-E-commerce
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**macOS/Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
.\venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Or, if a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook (`.ipynb`) from the Jupyter interface.

---

## 🔬 Project Workflow

The project follows a typical machine learning workflow:

### 1. Data Loading

The e-commerce dataset is loaded and prepared for analysis.

### 2. Data Cleaning

* Handled missing values
* Removed duplicate records
* Corrected data types
* Prepared the dataset for analysis and modeling

### 3. Exploratory Data Analysis

Performed EDA to:

* Understand customer behavior
* Analyze feature distributions
* Identify relationships between variables
* Find patterns related to customer satisfaction

### 4. Feature Engineering

Created and processed relevant features such as:

* `delivery_time`
* `review_score`
* Order-related features
* Product-related features

These features were used to improve the predictive performance of the models.

### 5. Model Building

Multiple machine learning models were trained and compared to determine which approach performs best for predicting customer satisfaction.

### 6. Model Evaluation

The models were evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

The evaluation was performed on a held-out test dataset.

---

## 📊 Key Finding

One of the key findings from the analysis was:

> **Delivery time was one of the most significant factors associated with negative customer reviews.**

This suggests that improving delivery performance can play an important role in improving customer satisfaction.

---

## 🎯 Project Objective

The main objective of this project is to demonstrate how machine learning and exploratory data analysis can be used to understand customer behavior and predict customer satisfaction in an e-commerce environment.

---

## 👨‍💻 Author

**Vishal Dabhade**

* GitHub: [Vishal-Dabhade](https://github.com/Vishal-Dabhade)
* Repository: [Predictive Customer Satisfaction Model for E-commerce](https://github.com/Vishal-Dabhade/Predictive-Customer-Satisfaction-Model-for-E-commerce)

---

## 📄 License

This project is intended for educational and learning purposes.

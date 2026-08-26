# Machine Learning Projects & Datasets

## 📌 About This Repository

This repository contains a collection of **Machine Learning datasets and projects** covering different supervised learning problems such as:

* Classification
* Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Cross-Validation
* Banking and Credit Risk Analysis
* Healthcare Prediction
* Human Resources Analytics
* Business and Delivery Prediction

The datasets are used for practicing **data preprocessing, exploratory data analysis, feature engineering, model building, evaluation, and prediction** using Python and Scikit-learn.

---

# 📂 Datasets Included

| No. | Dataset                 | Records | Features | Problem / Application                   |
| --: | ----------------------- | ------: | -------: | --------------------------------------- |
|   1 | `bank(1).csv`           |  41,188 |       21 | Bank Marketing Classification           |
|   2 | `bank_knn(1).csv`       |  41,188 |       21 | Bank Marketing using KNN                |
|   3 | `bank_marketing(1).csv` |  41,188 |       21 | Bank Marketing Prediction               |
|   4 | `chd(1).csv`            |     100 |        2 | Coronary Heart Disease                  |
|   5 | `computers(1).csv`      |      14 |        2 | Computer Usage / Delivery-Time Analysis |
|   6 | `credit(1).csv`         |   1,000 |       21 | Credit Risk Classification              |
|   7 | `creditrisk(1).csv`     |   1,000 |       21 | Credit Risk Prediction                  |
|   8 | `default_crossV(1).csv` |  10,000 |        4 | Default Prediction & Cross-Validation   |
|   9 | `default_knn(1).csv`    |      11 |        4 | Default Prediction using KNN            |
|  10 | `default_knn2(1).csv`   |  10,000 |        4 | Default Prediction using KNN            |
|  11 | `delivery(1).csv`       |      25 |        3 | Delivery Time Prediction                |
|  12 | `hr_project(1).csv`     |  14,999 |       10 | Employee Attrition Prediction           |
|  13 | `iris_svm(1).csv`       |     150 |        5 | Iris Flower Classification using SVM    |

---

# 1. 🏦 Bank Marketing Dataset

### Files

```text
bank(1).csv
bank_knn(1).csv
bank_marketing(1).csv
```

### Description

These datasets contain information from a **bank marketing campaign**. The objective is to predict whether a customer will subscribe to a bank term deposit.

### Dataset Size

* Records: **41,188**
* Features: **21**

### Important Features

* `age`
* `job`
* `marital`
* `education`
* `default`
* `housing`
* `loan`
* `contact`
* `month`
* `day_of_week`
* `duration`
* `campaign`
* `pdays`
* `previous`
* `poutcome`
* `emp.var.rate`
* `cons.price.idx`
* `cons.conf.idx`
* `euribor3m`
* `nr.employed`

### Target

```text
y
```

Possible values:

```text
yes
no
```

### Objective

Predict whether a customer will subscribe to a **term deposit**.

### Machine Learning Applications

* Classification
* KNN
* Data preprocessing
* Categorical encoding
* Model evaluation
* Customer prediction

---

# 2. ❤️ Coronary Heart Disease Dataset

### File

```text
chd(1).csv
```

### Description

This dataset contains information related to **age and coronary heart disease (CHD)**.

### Dataset Size

* Records: **100**
* Features: **2**

### Features

| Feature | Description                    |
| ------- | ------------------------------ |
| `age`   | Age of the individual          |
| `chd`   | Coronary heart disease outcome |

### Objective

Analyze the relationship between **age and coronary heart disease** and build a predictive model.

### Machine Learning Applications

* Classification
* Exploratory Data Analysis
* Healthcare prediction
* Visualization

---

# 3. 💻 Computers Dataset

### File

```text
computers(1).csv
```

### Dataset Size

* Records: **14**
* Features: **2**

### Features

| Feature   | Description     |
| --------- | --------------- |
| `Units`   | Number of units |
| `Minutes` | Time in minutes |

### Objective

Analyze the relationship between the number of units and the time required to process them.

### Machine Learning Applications

* Regression
* Correlation analysis
* Data visualization
* Prediction

---

# 4. 💳 Credit Dataset

### File

```text
credit(1).csv
```

### Dataset Size

* Records: **1,000**
* Features: **21**

### Important Features

* `over_draft`
* `credit_usage`
* `credit_history`
* `purpose`
* `current_balance`
* `Average_Credit_Balance`
* `employment`
* `location`
* `personal_status`
* `other_parties`
* `residence_since`
* `property_magnitude`
* `cc_age`
* `other_payment_plans`
* `housing`
* `existing_credits`
* `job`
* `num_dependents`
* `own_telephone`
* `foreign_worker`

### Target

```text
class
```

### Objective

Predict the **credit risk/classification of customers** based on their financial and personal information.

### Machine Learning Applications

* Classification
* Credit risk analysis
* Feature encoding
* Model evaluation

---

# 5. 🏦 Credit Risk Dataset

### File

```text
creditrisk(1).csv
```

### Dataset Size

* Records: **1,000**
* Features: **21**

### Description

This dataset contains customer financial and demographic information that can be used to analyze **credit risk**.

### Target

```text
class
```

### Objective

Build a machine learning model to classify customers according to their credit risk.

### Applications

* Credit scoring
* Risk classification
* Banking analytics
* Classification algorithms

---

# 6. 📊 Default Prediction Dataset

### File

```text
default_crossV(1).csv
```

### Dataset Size

* Records: **10,000**
* Features: **4**

### Features

| Feature   | Description     |
| --------- | --------------- |
| `default` | Default status  |
| `student` | Student status  |
| `balance` | Account balance |
| `income`  | Customer income |

### Objective

Predict whether a customer is likely to **default** based on financial and demographic information.

### Machine Learning Applications

* Classification
* Cross-validation
* Model evaluation
* Default prediction

---

# 7. 🤖 Default Prediction using KNN

### Files

```text
default_knn(1).csv
default_knn2(1).csv
```

### Dataset Sizes

`default_knn(1).csv`

* Records: **11**
* Features: **4**

`default_knn2(1).csv`

* Records: **10,000**
* Features: **4**

### Features

```text
defaulter
student
balance
income
```

### Objective

Use the **K-Nearest Neighbors (KNN)** algorithm to predict customer default behavior.

### Machine Learning Applications

* KNN classification
* Feature scaling
* Distance-based classification
* Model evaluation

---

# 8. 🚚 Delivery Time Dataset

### File

```text
delivery(1).csv
```

### Dataset Size

* Records: **25**
* Features: **3**

### Features

| Feature    | Description        |
| ---------- | ------------------ |
| `n.prod`   | Number of products |
| `distance` | Delivery distance  |
| `delTime`  | Delivery time      |

### Objective

Predict delivery time based on:

* Number of products
* Delivery distance

### Machine Learning Applications

* Regression
* Linear regression
* Correlation analysis
* Business prediction

---

# 9. 👥 HR Analytics Dataset

### File

```text
hr_project(1).csv
```

### Dataset Size

* Records: **14,999**
* Features: **10**

### Features

| Feature                 | Description                   |
| ----------------------- | ----------------------------- |
| `satisfaction_level`    | Employee satisfaction         |
| `last_evaluation`       | Last evaluation score         |
| `number_project`        | Number of projects            |
| `average_montly_hours`  | Average monthly working hours |
| `time_spend_company`    | Years spent in company        |
| `Work_accident`         | Work accident indicator       |
| `left`                  | Whether employee left         |
| `promotion_last_5years` | Promotion indicator           |
| `Department`            | Employee department           |
| `salary`                | Salary level                  |

### Target

```text
left
```

### Objective

Predict whether an employee is likely to **leave the company**.

### Machine Learning Applications

* Employee attrition prediction
* Classification
* HR analytics
* Feature importance
* Business intelligence

---

# 10. 🌸 Iris Dataset – SVM

### File

```text
iris_svm(1).csv
```

### Dataset Size

* Records: **150**
* Features: **5**

### Features

| Feature        | Description    |
| -------------- | -------------- |
| `Sepal.Length` | Sepal length   |
| `Sepal.Width`  | Sepal width    |
| `Petal.Length` | Petal length   |
| `Petal.Width`  | Petal width    |
| `Species`      | Flower species |

### Target

```text
Species
```

### Objective

Classify Iris flowers into their respective species using the **Support Vector Machine (SVM)** algorithm.

### Machine Learning Applications

* SVM classification
* Multi-class classification
* Feature scaling
* Model evaluation
* Data visualization

---

# 🧠 Machine Learning Techniques Covered

This repository provides practice with several important machine learning concepts.

### Supervised Learning

* Classification
* Regression

### Classification Algorithms

* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Logistic Regression
* Decision Trees
* Random Forest
* Other classification algorithms

### Regression

* Linear Regression
* Relationship analysis
* Prediction

### Model Validation

* Train/Test Split
* Cross-Validation
* Performance evaluation

---

# 📈 Evaluation Metrics

Depending on the problem, the following metrics can be used:

### Classification

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

### Regression

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Git**
* **GitHub**

---

# 📁 Recommended Repository Structure

```text
Machine-Learning-Projects/
│
├── README.md
│
├── datasets/
│   ├── bank.csv
│   ├── bank_knn.csv
│   ├── bank_marketing.csv
│   ├── chd.csv
│   ├── computers.csv
│   ├── credit.csv
│   ├── creditrisk.csv
│   ├── default_crossV.csv
│   ├── default_knn.csv
│   ├── default_knn2.csv
│   ├── delivery.csv
│   ├── hr_project.csv
│   └── iris_svm.csv
│
├── notebooks/
│   ├── bank_marketing.ipynb
│   ├── bank_knn.ipynb
│   ├── credit_risk.ipynb
│   ├── default_knn.ipynb
│   ├── hr_project.ipynb
│   └── iris_svm.ipynb
│
└── requirements.txt
```

---

# ▶️ How to Run the Projects

## Option 1: Google Colab

Upload the required dataset to Google Colab and open the corresponding `.ipynb` notebook.

Run the notebook cells sequentially.

## Option 2: Jupyter Notebook

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project:

```bash
cd Machine-Learning-Projects
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📦 Requirements

The main Python libraries used in these projects are:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

You can install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# 🎯 Learning Objectives

Through these datasets and projects, the following machine learning skills are practiced:

* Data loading
* Data cleaning
* Exploratory Data Analysis
* Data visualization
* Feature selection
* Feature encoding
* Feature scaling
* Train-test splitting
* Classification
* Regression
* KNN
* SVM
* Cross-validation
* Model evaluation
* Prediction
* Interpretation of results

---

# 🚀 Future Improvements

Future versions of these projects can include:

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Handling class imbalance
* Feature selection
* Model comparison
* Confusion matrix visualization
* ROC curves
* Feature importance
* SHAP explainability
* Streamlit applications
* Machine learning model deployment

---

# 👩‍💻 Author

**Snehitha Badduri

This repository contains machine learning practice projects developed to build practical skills in Data Science, Machine Learning, and Artificial Intelligence.


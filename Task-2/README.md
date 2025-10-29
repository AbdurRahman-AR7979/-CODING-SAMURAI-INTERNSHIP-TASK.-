
###````markdown
# 🚢 Task 2: Logistic Regression on Titanic Dataset

This project focuses on building a **Logistic Regression model** to predict the survival of passengers aboard the **Titanic**.  
It is developed as part of my Data Science learning journey — demonstrating the complete **Machine Learning pipeline** from data preprocessing to model evaluation.

---

## 🧭 Project Overview
The goal of this project is to analyze the Titanic dataset and predict which passengers survived the disaster based on various features such as:
- Age  
- Gender  
- Passenger class  
- Fare  
- Embarked location  

The project demonstrates how **Logistic Regression** can be applied to a real-world binary classification problem.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---###

## 🧩 Project Workflow
### **1️⃣ Data Loading**
Dataset is loaded using Seaborn’s built-in Titanic dataset:
```python
df = sns.load_dataset('titanic')
````

### **2️⃣ Exploratory Data Analysis (EDA)**

* Inspected dataset shape and structure
* Handled missing values for `age` and `embarked`
* Dropped irrelevant columns like `name`, `ticket`, and `cabin`

### **3️⃣ Data Preprocessing**

* Encoded categorical variables using `pd.get_dummies()`
* Split the dataset into training and testing sets (80-20 ratio)

### **4️⃣ Model Building**

Used **Logistic Regression** from `sklearn.linear_model`:

```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression()
model.fit(X_train, y_train)
```

### **5️⃣ Model Evaluation**

* Accuracy Score
* Confusion Matrix
* Classification Report

### **6️⃣ Feature Importance**

Visualized which features contributed most to survival prediction using a bar plot.

---

## 📊 Results & Insights

* Achieved an accuracy of around **XX%** (replace with your final score).
* **Top influential features:** `sex`, `pclass`, `fare`, and `age`.
* Female passengers and those in higher classes had a significantly higher survival rate.

---

## 🖼️ Visualizations

A few visual insights included in the notebook:

* Survival distribution by gender
* Correlation heatmap of numerical features
* Feature importance bar chart


---

## 📁 Folder Structure

```
Task 2/
│
├── Titanic_Logistic_Regression.ipynb
├── README.md
├── requirements.txt
└── images/
    └── titanic_banner.png
```

---

## 📦 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Navigate to the folder

   ```bash
   cd "Task 2"
   ```
3. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebook and run all cells:

   ```bash
   jupyter notebook Titanic_Logistic_Regression.ipynb
   ```

---

## 🌟 Key Learnings

* Hands-on understanding of **binary classification**
* Applying **Logistic Regression** to real-world data
* Evaluating model performance using metrics like precision, recall, and F1-score
* Visualizing model insights effectively

---

## 🧑‍💻 Author

**Abdur Rahman**
📍 Data Science Enthusiast | B.Tech in Computer Science (Data Science)


---

### 🔖

`#DataScience` `#MachineLearning` `#LogisticRegression` `#Python` `#ScikitLearn` `#TitanicDataset` `#ProjectShowcase`

```



#  Employee Mental Health Risk Prediction

This machine learning project aims to predict whether an employee is likely to seek treatment for mental health issues, based on various workplace, personal, and mental health-related factors. The dataset used comes from the 2016 OSMI Mental Health in Tech survey.

---

##  Business Problem

> **How can organizations proactively identify employees who are at risk of needing mental health treatment?**

Mental health issues in the workplace often go undetected until they impact performance, retention, or well-being. This project helps answer:

- Which factors contribute most to an employee seeking mental health treatment?
- Can we use existing survey or HR data to anticipate treatment needs early?
- How can tech companies build inclusive environments that reduce stigma and support employees effectively?

By predicting mental health risk, this project aims to assist HR departments in implementing timely interventions, mental health policies, and tailored support programs — ultimately improving employee retention, satisfaction, and productivity.

---

##  Problem Statement

> **Objective:**  
To build a classification model that can predict the likelihood of an employee seeking mental health treatment, helping organizations identify and support at-risk individuals.
>
> ##  Author

**Azib Malick**  
Data Science & Machine Learning Enthusiast  

---

##  Dataset

- **Source:** [OSMI Mental Health in Tech Survey (2016)](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)
- **File Used:** `survey.csv`
- **Target Column:** `treatment` (1 = Yes, 0 = No)

---

##  Data Preprocessing

- Dropped: `state`, `comments`
- Handled missing values in `self_employed`, `work_interfere`
- Encoded categorical features using `LabelEncoder`
- Scaled numerical features with `StandardScaler`

---

##  Exploratory Data Analysis (EDA)

- **Distribution Analysis:** Age, Gender, Country, etc.
- **Bivariate Analysis:** Heatmaps, pairplots, and boxplots to study relationships.
- **Class Balance Check:** The dataset was slightly imbalanced but manageable without resampling.

---

##  Models Applied

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 0.8095   |
| XGBoost Classifier     | 0.8135   |

###  Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC (optional)

---

##  Visualizations

- Countplots, Histograms
- Correlation Heatmap
- Feature Importance from XGBoost

---

##  Results

- XGBoost outperformed Logistic Regression by a slight margin.
- High precision and recall achieved for both classes.
- Model demonstrated strong generalization without overfitting.

---

##  Future Work

- Add other boosting algorithms (LightGBM, CatBoost)
- Improve interpretability using SHAP or LIME
- Incorporate real-time data or deploy using Streamlit/Flask

---

##  Tech Stack

- Python, Pandas, NumPy, Scikit-Learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Acknowledgement

Dataset by [OSMI - Open Sourcing Mental Illness](https://osmihelp.org/research)

---

> **“And We have certainly honored the children of Adam…” — _Qur’an 17:70_**

 ##  Author

**Azib Malick**  
Data Science & Machine Learning Enthusiast  

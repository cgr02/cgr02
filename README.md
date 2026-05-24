<h1 align="center">Carlos (Charlie) Gutierrez</h1>

<p align="center">
  Engineering Student · Universidad Industrial de Santander · 7th semester<br>
  <sub>Data Science &nbsp;·&nbsp; Machine Learning &nbsp;·&nbsp; AI</sub>
</p>

<p align="center">
  <a href="https://github.com/cgr02">
    <img src="https://img.shields.io/badge/GitHub-cgr02-181717?style=flat&logo=github" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/carlos-gutiérrez-b30a16401">
    <img src="https://img.shields.io/badge/LinkedIn-Carlos_Gutierrez-0A66C2?style=flat&logo=linkedin" />
  </a>
</p>

---

## About

I'm a 7th-semester student at UIS, focused on data science, machine learning, and AI.

I enjoy building end-to-end pipelines — from raw data cleaning to model evaluation and communicating results. This repository documents my three main undergraduate projects, each tackling a different problem with a different approach.

Outside academia, I'm exploring what else it comes.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=black)

---

## Projects

### Credit Risk Classification
`AI Course` &nbsp;·&nbsp; Binary classification

Kaggle dataset with ~29,000 records. Goal: predict whether a person will default on a loan.

Pipeline: data cleaning → median imputation → encoding → model comparison with KFold cross-validation.

**Result:** Random Forest with 70 estimators reached **92.85% accuracy** — the most stable and reliable of the three models compared (Decision Tree, Random Forest, SVM). Error rate ~6.8%, acceptable in a financial context.

`pandas` `scikit-learn` `KFold` `classification_report`

---

### Social Media & Stress
`Statistics 2` &nbsp;·&nbsp; Linear regression from scratch

~399 filtered observations on Instagram usage and engagement among rural Canadian women under 35.

Regression built **without sklearn**: manual implementation of SSE, R², t-stat, p-value, and residual diagnostics. Linear and non-linear models compared.

**Result:** Regression with transformations revealed a clear non-linear relationship between active time on Instagram and user engagement. Time series analysis showed stable average engagement over time — no significant trend or weekly seasonality. Remaining variability corresponds to random fluctuations around the mean.

`pandas` `scipy` `matplotlib` `numpy`

---

### Deep Learning with Keras
`AI Course` &nbsp;·&nbsp; Classification & regression

Dense neural networks for two problems: penguin species classification and regression on flipper length and supermarket sales.

Architecture: ReLU hidden layers, sigmoid/linear output, SGD optimizer. Fixed seed: `tf.random.set_seed(21)`.

`TensorFlow` `Keras` `SGD` `Dense`

---

<p align="center">
  <sub>Documenting the learning, one project at a time.</sub>
</p>

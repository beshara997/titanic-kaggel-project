# Titanic - Machine Learning from Disaster 🚢

<div dir="rtl">

## 🎯 الهدف من المشروع

ده مشروع بسيط تبدأ بيه على Kaggle. الموضوع مش معقد.

لما تبدأ:

- ذاكر النوتبوك واكتبه بنفسك
- افهم كل سطر بيعمل إيه
- في الآخر تكون عرفت يعني إيه **EDA**
- وتكون عرفت تستخدم الخوارزميات من مكتبة **sklearn**

</div>

---

A beginner-friendly walkthrough of the Kaggle **Titanic** competition: predicting which passengers survived using a classification model in Python.

## 📌 The Problem
Given passenger data (age, sex, class, fare, ...), predict whether each passenger **survived (1)** or **not (0)**. This is a **binary classification** problem.

## 🗺️ Beginner Strategy
1. **Read the data**: understand each column and check for missing values
2. **Clean it**: fill missing values (e.g. Age, Embarked) and drop useless columns
3. **Feature engineering**: encode categorical columns (e.g. Sex) into numbers
4. **Train a model**: start simple, then compare other models
5. **Predict & submit**: generate `submission.csv` and upload it to Kaggle
6. **Improve**: iterate and watch your score

## 🛠️ Tools
Python · pandas · scikit-learn · Jupyter Notebook

## 📂 Files
| File | Description |
|------|-------------|
| `titanic.ipynb` | Full notebook (cleaning, model, predictions) |
| `submission.csv` | Final predictions submitted to Kaggle |
| `gender_submission.csv` | Kaggle's sample submission |

## 📥 Get the Data
The data files are not included in this repo. Download them from the
[competition page](https://www.kaggle.com/competitions/titanic/data) and place `train.csv` and `test.csv` next to the notebook.

## ▶️ How to Run
```bash
git clone https://github.com/beshara997/titanic-kaggle-project.git
cd titanic-kaggle-project
pip install pandas scikit-learn jupyter
jupyter notebook titanic.ipynb
```

## 📊 Result
- Model used: _(write your model here)_
- Kaggle score: _(write your score here)_

## 💡 Tips for Beginners
- Start with a simple model before trying complex ones
- Always check for missing values first
- Don't just copy notebooks: understand every step
- Submit early, then improve

## 👤 Author
**beshara997** · 3rd-year AI student at Assiut University

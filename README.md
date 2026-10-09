# Heart Disease Prediction

A small machine learning web app that predicts whether a person is at **high or low risk of heart disease** from basic health details.

**Try it live:** https://heart-disease-suzume2006.streamlit.app

## How it works

1. You enter 11 health details in the app.
2. The app prepares the input the same way the training data was prepared (one-hot columns and scaling).
3. A **K-Nearest Neighbors (KNN)** model predicts high risk or low risk.
4. The app shows the result.

## What you enter

Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, oldpeak (ST depression) and ST slope.

## Files

| File | What it is |
|---|---|
| `app.py` | The Streamlit web app |
| `KNN_model.pkl` | The trained KNN model |
| `scaler.pkl` | The scaler used to normalize the inputs |
| `columns.pkl` | The list of columns the model expects |
| `requirements.txt` | Python packages needed |

## Run it on your computer

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Model details

- Model: K-Nearest Neighbors


## Important

This is a learning project. It is **not** a medical tool and should never be used to make health decisions. If you are worried about your health, please see a doctor.

## Ideas for next time

- Compare KNN with other models (logistic regression, random forest)
- Add a short note on how the model was trained and tested

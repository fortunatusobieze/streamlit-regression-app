# Streamlit Regression App

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

## Overview

An interactive web application that serves a trained Linear Regression model via a clean Streamlit interface. Users can input feature values and get real-time predictions from the deployed model.

## Features

- Interactive UI built with Streamlit
- Pre-trained Linear Regression model loaded from a `.pkl` file
- Real-time prediction output on user input
- Clean, minimal interface with instant feedback

## Project Structure

```
streamlit-regression-app/
|-- app.py                        # Main Streamlit application
|-- linear_regression_model.pkl   # Serialised trained model
|-- requirements.txt              # Python dependencies
|-- README.md
```

## Tech Stack

- **Python** — Core language
- **Streamlit** — Web app framework for ML deployment
- **Scikit-learn** — Model training and serialisation
- **Pickle** — Model loading

## How to Run Locally

```bash
# Clone the repository
git clone https://github.com/fortunatusobieze/streamlit-regression-app.git
cd streamlit-regression-app

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

## Author

**Fortunatus Obieze**
Data Scientist | MSc Data Science & Big Data Analytics
[LinkedIn](https://linkedin.com/in/fortunatusobieze)

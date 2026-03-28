# AI-HEALTH-ASSISTANT-
AI Health Assistant is a smart system that helps users monitor their health by analyzing symptoms, suggesting possible conditions, and providing basic precautions. It offers quick guidance, promotes awareness, and supports early decision-making, but does not replace professional medical advice.
# 🧠 AI Health Assistant

## 📌 Overview

The AI Health Assistant is a simple machine learning-based desktop
application that predicts possible diseases based on user-provided
symptoms. It uses NLP and a Random Forest classifier to analyze input
and provide the top 3 probable diseases along with precautions.

## 🚀 Features

-   Predicts diseases from symptoms using ML
-   Voice input support
-   Shows top 3 predictions with probabilities
-   Provides precautionary advice
-   GUI built with Tkinter

## 🧠 How It Works

1.  Dataset maps symptoms to diseases\
2.  Text preprocessing cleans input\
3.  TF-IDF vectorization converts text to features\
4.  Random Forest model predicts diseases\
5.  Top 3 predictions are shown\
6.  Precautions are displayed

## 📦 Requirements

pip install pandas scikit-learn speechrecognition pyaudio

## ▶️ Run

python app.py

## ⚠️ Disclaimer

Not a medical diagnostic tool. For educational purposes only.

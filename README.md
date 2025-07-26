# 🧠 EEG-Based Player Classification using Machine Learning

Welcome to our project repository! This work focuses on **Classifying players as Beginner & Advanced** based on their **Logical thinking patterns**, as captured through **EEG (Electroencephalogram) signals**.

We believe that the brain never lies — and through this project, we decode the electrical whispers of the mind to understand how experience reflects in neural activity during cognitively intense tasks.

---

## 🧬 Project Overview

This project leverages **EEG signals** from the **prefrontal cortex** to classify individuals into two groups:

- 🟢 **Beginners**
- 🔵 **Advanced Players**

The classification is based on logical thinking tasks (such as playing chess), where **EEG theta power** is a key feature to differentiate expertise levels.

---

## 🚀 Goals

- Analyze EEG data from participants during logical thinking activities
- Extract relevant features (focus on prefrontal cortex theta power)
- Train and evaluate ML models to classify individuals
- Study brainwave patterns to understand differences in cognitive effort

---

## 🧠 Data Description

- EEG recordings from participants during chess-based logical tasks
- Signals recorded from the **prefrontal cortex** only
- Labels assigned based on player's chess expertise level

📁 Data is anonymized and structured in `/data/` with preprocessing scripts provided in `/scripts/`.

---

## 🧪 ML Models Used

We experimented with a range of classical ML models:

-  **Support Vector Machine (SVM)**
-  **Random Forest**
-  **CatBoost**

We chose not to include XGBoost to ensure model diversity and interpretability.

---

## 📊 Results

- Theta power was consistently higher in advanced players
- Visualizations and confusion matrices are available in `/results/`

---





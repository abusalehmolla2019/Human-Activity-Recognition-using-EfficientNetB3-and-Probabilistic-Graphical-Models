# 🏆 Human Activity Recognition (HAR)

## EfficientNetB3 (Deep Learning) vs Probabilistic Graphical Models (PGM)

This project implements and compares **deep learning** and **probabilistic graphical models** for Human Activity Recognition (HAR).  
We use **EfficientNetB3** as the deep learning baseline and compare it with classical models:

- Naive Bayes
- Bayesian Network
- Hidden Markov Model (HMM)

The goal is to evaluate performance trade-offs between **accuracy, interpretability, and computational efficiency**.

---

## 📌 Project Highlights

- 🔬 Deep Learning model: EfficientNetB3
- 📊 Classical ML models: Naive Bayes, Bayesian Network, HMM
- ⚖️ Comparative analysis of:
  - Accuracy
  - F1-score
  - Training time
  - Interpretability
- 📈 Visualization of results and performance comparison

---

## 🧠 Problem Statement

Human Activity Recognition (HAR) is a key task in:
- Healthcare monitoring
- Smart homes
- Wearable sensor systems
- IoT-based systems

This project explores whether **deep learning models outperform classical probabilistic models** in HAR tasks.

---

## 🏗️ Methodology

### 1. Data Preprocessing
- Data cleaning and normalization
- Feature extraction / image transformation (if applicable)
- Train-test split

### 2. Deep Learning Model
- EfficientNetB3 pretrained architecture
- Fine-tuned for HAR classification
- Softmax classifier for multi-class output

### 3. Probabilistic Models
- Naive Bayes classifier
- Bayesian Network structure learning
- Hidden Markov Model for sequential activity patterns

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Training time comparison

---

## 📁 Project Structure
📦 HAR-EfficientNetB3-vs-PGM
┣ 📜 notebook.ipynb
┣ 📜 dataset/
┣ 📜 models/
┣ 📜 results/
┣ 📜 requirements.txt
┗ 📜 README.md


---

## 🚀 Installation

```bash
git clone https://github.com/your-username/har-efficientnet-pgm.git
cd har-efficientnet-pgm
pip install -r requirements.txt


##Usage

Run the Jupyter Notebook:

jupyter notebook efficientnetb3-deep-learning-vs-pgm-models.ipynb


 
## Requirements
Python 3.8+
TensorFlow / Keras
Scikit-learn
NumPy
Pandas
Matplotlib
Seaborn

Expected Results

| Model            | Accuracy | F1-score | Interpretability | Speed  |
| ---------------- | -------- | -------- | ---------------- | ------ |
| EfficientNetB3   | High     | High     | Low              | Medium |
| Naive Bayes      | Medium   | Medium   | High             | Fast   |
| Bayesian Network | Medium   | Medium   | High             | Medium |
| HMM              | Medium   | Medium   | High             | Medium |



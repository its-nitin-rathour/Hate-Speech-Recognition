# Hate Speech Detection using Machine Learning

This repository contains a Jupyter Notebook that performs **Hate Speech Detection** on social media text data using Natural Language Processing (NLP) and classical Machine Learning techniques like Logistic Regression, Naive Bayes, and Support Vector Machines (SVM).

## 📌 Project Overview

The objective of this project is to build a text classification model that can automatically identify and categorize tweets as:
- Hate speech
- Offensive language
- Neither (neutral content)

This model helps in monitoring and moderating harmful online content using basic ML models and NLP pipelines.

---

## 🧠 Techniques Used

- **Text Preprocessing**: Lowercasing, punctuation removal, stopword removal, stemming.
- **Feature Extraction**: TF-IDF vectorization
- **Model Building**: Logistic Regression, Multinomial Naive Bayes, SVM
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

---

## 📁 Files

| File Name | Description |
|-----------|-------------|
| `Hate_code.ipynb` | Main Jupyter notebook containing code for data preprocessing, model training, and evaluation. |
| `README.md` | Project documentation. *(You are here)* |
| `dataset` | Dataset used in this project |

---

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detection.git
   cd hate-speech-detection
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate` 
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
4. Launch the Jupyter Notebook:
   ```bash
    jupyter notebook
## 📊 Sample Output

Models were evaluated using precision, recall, and F1-score for each class. Logistic Regression and SVM performed better than Naive Bayes in this setup.

---

## 📌 Future Work

- Use deep learning models (e.g., LSTM, BERT) for improved accuracy.
- Deploy the model using Flask or FastAPI.
- Build a web interface for real-time hate speech detection.

---

## 📚 Dataset

This project uses a preprocessed version of a hate speech dataset (commonly known from Twitter). If not included, you can use publicly available datasets such as:

- [Davidson et al. (2017)](https://github.com/t-davidson/hate-speech-and-offensive-language)

---

## 📃 License

This project is open-source and available under the MIT License.

---

## 🙋‍♂️ Author

**Nitin Rathour**  
_M Tech Data Science | Delhi Technological University_

---

## ⭐ Show your support

If you like this project, don't forget to ⭐ star the repo and share it with others!

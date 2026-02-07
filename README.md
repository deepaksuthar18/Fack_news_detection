# Fake News Detection System

## 📌 Overview
This project implements an NLP pipeline for detecting fake news. It processes news text data, cleans it, extracts features, and trains machine learning models to classify news as real or fake.

## 🚀 NLP Pipeline
The project follows a structured NLP pipeline:
1.  **Data Loading**: Importing the dataset (`news_dataset`).
2.  **Preprocessing**:
    *   Lowercasing, HTML tag removal, Emoji removal.
    *   Stopword removal and Lemmatization.
3.  **Exploratory Data Analysis (EDA)**:
    *   Word Frequency Distribution.
    *   Zipf’s Law Visualization.
    *   Heaps’ Law (Vocabulary Growth).
    *   Type-Token Ratio (TTR) analysis.
4.  **Feature Engineering**:
    *   POS Tagging (HMM).
    *   TF-IDF with N-grams.
5.  **Model Training**:
    *   Naïve Bayes (NB)
    *   Support Vector Machine (SVM)
    *   Linear Regression
6.  **Evaluation**:
    *   Model Comparison & Performance Visualization.
    *   Confusion Matrix.
7.  **Prediction**: User input prediction system.

## 📂 Project Structure
```
d:/fack_news_detection/
├── Dataset_multimodel/       # Dataset files
├── Notebook/                 # Jupyter Notebooks for analysis and training
├── news_dataset/             # Source data
├── venv/                     # Virtual Environment (Ignored in Git)
├── requirements.txt          # Python dependencies
├── README.md                 # Project Documentation
└── .gitignore                # Git ignore rules
```

## 🛠️ Installation
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/deepaksuthar18/Fack_news_detection.git
    cd Fack_news_detection
    ```

2.  **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # Mac/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🏃 Usage
Run the Jupyter Notebooks in the `Notebook/` directory to explore the data and train the models.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## 📜 License
This project is open-source.

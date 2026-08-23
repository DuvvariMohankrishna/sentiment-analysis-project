🧠 Sentiment Analysis Project

An NLP-based machine learning project that analyzes text and classifies sentiment using Python, NLTK, TF-IDF, and Logistic Regression.

This project demonstrates an end-to-end machine learning workflow, including data preprocessing, text cleaning, tokenization, stemming, feature extraction, model training, and performance evaluation.

🚀 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine the sentiment or emotional tone expressed in text.

In this project, text data is preprocessed and transformed into numerical features using TF-IDF Vectorization. A Logistic Regression model is then trained to classify the sentiment of the input text.

The project was developed using Python and Jupyter Notebook.

✨ Features
📊 Text data processing and analysis
🧹 Text cleaning and preprocessing
🔤 Tokenization using NLTK
🌱 Text stemming
🔢 TF-IDF feature extraction
🤖 Sentiment classification using Logistic Regression
📈 Model evaluation using classification metrics
🧪 Train-test data splitting
🛠️ Tech Stack
Category	Technologies
Programming Language	Python
Development Environment	Jupyter Notebook
NLP	NLTK
Data Processing	Pandas, NumPy
Feature Extraction	TF-IDF Vectorizer
Machine Learning	Scikit-learn
Classification Model	Logistic Regression
🔄 Machine Learning Workflow
Text Dataset
     │
     ▼
Data Preprocessing
     │
     ▼
Text Cleaning
     │
     ▼
Tokenization & Stemming
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Train-Test Split
     │
     ▼
Logistic Regression
     │
     ▼
Model Evaluation
📁 Project Structure
sentiment-analysis-project/
│
├── README.md
├── Sanasyisisminiproject.ipynb    # Main Jupyter Notebook
├── sentiment_analysis.csv         # Dataset
└── sentimentanalysistrim.docx     # Project documentation
📊 Dataset

The project uses a CSV dataset containing text and corresponding sentiment labels.

The dataset is processed before training using NLP and text preprocessing techniques.

The workflow includes:

Loading the dataset
Cleaning and preprocessing text
Tokenizing text
Applying stemming
Converting text into numerical features using TF-IDF
🧪 Model Training

The machine learning pipeline follows these steps:

Load the sentiment dataset.
Clean and preprocess the text data.
Tokenize the text using NLTK.
Apply stemming to reduce words to their root form.
Convert text into numerical features using TF-IDF Vectorization.
Split the dataset into training and testing sets.
Train a Logistic Regression model.
Evaluate the model using standard classification metrics.
📈 Results

The Logistic Regression model is evaluated using:

Accuracy
Precision
Recall
F1-score
Classification Report
Current Results
Metric	Result
Training Accuracy	~84%
Test Accuracy	81%
Test Weighted F1-Score	~0.79

Results are based on the current notebook implementation and train-test split.

⚙️ Installation and Usage
1. Clone the repository
git clone https://github.com/DuvvariMohankrishna/sentiment-analysis-project.git
cd sentiment-analysis-project
2. Create a virtual environment
python -m venv venv
3. Activate the virtual environment

Windows

venv\Scripts\activate

macOS/Linux

source venv/bin/activate
4. Install dependencies
pip install pandas numpy nltk scikit-learn jupyter
5. Launch Jupyter Notebook
jupyter notebook

Then open:

Sanasyisisminiproject.ipynb

Run the notebook cells sequentially to reproduce the preprocessing, model training, and evaluation workflow.

💡 Key Learning Outcomes

Through this project, I gained hands-on experience with:

Natural Language Processing fundamentals
Text preprocessing and cleaning
Tokenization
Stemming
TF-IDF Vectorization
Feature engineering for text data
Train-test splitting
Logistic Regression
Model evaluation
Scikit-learn
NLTK
Jupyter Notebook
🔮 Future Improvements
 Compare Logistic Regression with additional machine learning models
 Perform hyperparameter tuning
 Add exploratory data analysis and visualizations
 Save the trained model using Joblib or Pickle
 Build a web interface for sentiment prediction
 Develop a REST API for model inference
 Deploy the model as an interactive application
 Add automated testing and reproducible dependency management
👨‍💻 Author

Duvvari Mohankrishna

MCA Graduate and aspiring Python Backend Developer with an interest in Machine Learning and Natural Language Processing.

GitHub: https://github.com/DuvvariMohankrishna
LinkedIn: https://www.linkedin.com/in/mohankrishna-duvvari/

⭐ If you found this project interesting, consider giving it a star!

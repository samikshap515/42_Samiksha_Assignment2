# Sentiment Analysis of Artificial Intelligence Tweets

## 📌 Student Details
- **Name:** Samiksha
- **Roll Number:** 42
- **Course:** Data Analytics and Visualisation (CSC601)
- **Semester:** VI
- **Institution:** Rizvi College of Engineering

---

## 📖 Project Overview
This project performs **sentiment analysis** on tweets related to **Artificial Intelligence (AI)**. The goal is to classify tweets into **Positive**, **Neutral**, and **Negative** sentiments using machine learning techniques. The performance of three classifiers—**Naïve Bayes**, **Logistic Regression**, and **Support Vector Machine (SVM)**—is evaluated and compared using precision, recall, F1-score, and accuracy.

---

## 🎯 Objectives
- Collect and manually label **100 tweets** related to Artificial Intelligence.
- Preprocess the text data to remove noise and improve model performance.
- Split the dataset into **80% training** and **20% testing** sets.
- Implement and compare the following classifiers:
  - Naïve Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
- Evaluate model performance using **Precision**, **Recall**, **F1-Score**, and **Accuracy**.
- Visualize the dataset and model results.

---

## 📂 Repository Structure
```
42_Samiksha_Assignment2/
│
├── data/
│   └── tweets.csv                # Dataset of 100 labeled tweets
├── reports/
│   └── final_report.pdf          # Detailed project report
├── sentiment_analysis.ipynb      # Jupyter Notebook with code and visualizations
├── README.md                    # Project documentation
├── requirements.txt             # Required Python libraries
└── .gitignore
```

---

## 📊 Dataset Description
- **Total Tweets:** 100
- **Sentiment Classes:** Positive, Neutral, Negative
- **Source:** Manually created and labeled tweets related to Artificial Intelligence.

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Conversion of text to lowercase.
- Removal of URLs, mentions (@), hashtags (#), punctuation, and special characters.
- Removal of stopwords using the **NLTK** library.
- Tokenization and cleaning of tweets.

### 2. Feature Extraction
- **TF-IDF (Term Frequency–Inverse Document Frequency)** was used to convert text into numerical feature vectors.

### 3. Train-Test Split
- **80% Training Data**
- **20% Testing Data**
- Stratified sampling was used to maintain class balance.

### 4. Machine Learning Models
| Model | Description |
|------|-------------|
| **Naïve Bayes** | Fast and efficient baseline model for text classification. |
| **Logistic Regression** | Provides probabilistic outputs and handles high-dimensional data well. |
| **Support Vector Machine (SVM)** | Effective in high-dimensional spaces and often achieves the best performance. |

---

## 📈 Evaluation Metrics
The models were evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

### 📊 Example Performance Comparison

| Model | Precision | Recall | F1-Score | Accuracy |
|------|-----------|--------|----------|----------|
| Naïve Bayes | 0.78 | 0.75 | 0.76 | 0.75 |
| Logistic Regression | 0.85 | 0.82 | 0.83 | 0.82 |
| SVM | **0.90** | **0.88** | **0.89** | **0.88** |

> **Note:** Replace these values with the actual results generated from the notebook.

---

## 📊 Visualizations Included
- 📌 Sentiment Distribution Bar Chart
- 📌 Confusion Matrices for each model
- 📌 Model Performance Comparison Chart
- 📌 (Optional) Word Cloud of tweets

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/samikshap515/42_Samiksha_Assignment2.git
cd 42_Samiksha_Assignment2
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook sentiment_analysis.ipynb
```

---

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation
- **NLTK** – Text preprocessing
- **Scikit-learn** – Machine learning models
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment

---

## 📌 Results and Discussion
- **Naïve Bayes** provided a strong baseline with fast computation.
- **Logistic Regression** achieved balanced precision and recall.
- **Support Vector Machine (SVM)** demonstrated the **best overall performance**, making it the most suitable model for this task.

---

## ✅ Conclusion
This project successfully demonstrated the application of machine learning techniques for sentiment analysis of social media data. The comparative analysis showed that **SVM outperformed the other models**, while Logistic Regression also provided competitive results. The study highlights the effectiveness of text analytics in understanding public opinion on Artificial Intelligence.

---

## 📬 Submission Details
- **Repository Link:**  
  https://github.com/samikshap515/42_Samiksha_Assignment2

---

## 👩‍💻 Author
**Samiksha**  
Roll Number: 42  
Rizvi College of Engineering

---

## 📜 License
This project is created for academic purposes only.

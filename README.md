# Email Spam Detection using Machine Learning

## Project Overview

Email Spam Detection is a Machine Learning project that classifies emails as **Spam** or **Ham** using text processing and classification algorithms. The system analyzes email content, extracts important features, and predicts whether an email is unwanted spam or a genuine message.

## Features

* Detects spam and non-spam emails
* Text preprocessing and cleaning
* Feature extraction using TF-IDF / Count Vectorizer
* Machine Learning model training
* Accuracy evaluation
* Simple and beginner-friendly implementation

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Jupyter Notebook / VS Code

## Machine Learning Workflow

1. Import dataset
2. Clean and preprocess text
3. Convert text into numerical features
4. Split data into training and testing sets
5. Train classification model
6. Evaluate model performance
7. Predict new email messages

## Algorithms Used

* Naive Bayes
* Logistic Regression
* Support Vector Machine

## Dataset

The dataset contains email or SMS messages labeled as:

* **Spam**: Unwanted or promotional messages
* **Ham**: Genuine messages

## Installation

```bash
pip install pandas numpy scikit-learn nltk
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/email-spam-detection.git
```

2. Open the project folder

```bash
cd email-spam-detection
```

3. Run the Python file or notebook

```bash
python spam_detection.py
```

## Sample Prediction

```python
message = "Congratulations! You won a free prize. Click now!"
prediction = model.predict([message])
print(prediction)
```

Output:

```text
Spam
```

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Applications

* Email filtering systems
* Message classification
* Cybersecurity awareness
* Spam prevention tools

## Future Enhancements

* Build a web application using Flask or Streamlit
* Add real-time email checking
* Improve accuracy using deep learning
* Deploy the model online
* Add user-friendly dashboard

## Conclusion

This project helps in identifying spam messages using Machine Learning techniques. It demonstrates text preprocessing, feature extraction, model training, and prediction in a simple and practical way.

## Author

**Avinash Basutkar**

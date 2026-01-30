INTRODUCTION:
This project is a Spam Detection System built using Machine Learning and NLP to classify messages as Spam or Not Spam (Ham).
It automates the process of filtering unwanted messages and demonstrates how text data can be cleaned, analyzed, and classified using ML models.

Its purpose;
Identifies whether a message is spam or legitimate
Uses NLP techniques to clean and process text data
Trains machine learning models for text classification
Evaluates model performance using standard metrics

Technologies Used: Python,Pandas, NumPy,Scikit-learn,NLTK,Matplotlib
Dataset: Email spam dataset from public resource

Procedures:
Data Collection:A labeled dataset containing spam and non-spam messages is used.
Text Preprocessing:Messages are cleaned by converting text to lowercase, removing punctuation, stopwords, and applying tokenization and stemming.
Feature Extraction:Text data is converted into numerical form using Bag of Words / TF-IDF.
Model Training:Machine learning models such as Naive Bayes and Logistic Regression are trained on the processed data.
EvaluationThe models are evaluated using accuracy, precision, recall, and confusion matrix.
Prediction:The trained model predicts whether a new message is spam or not.

Results:
The model achieves good accuracy on unseen data
Naive Bayes performs efficiently for text-based classification
The system reliably distinguishes spam from normal messages

Running the Project:
git clone https://github.com/your-username/spam-detector.git
cd spam-detector
pip install -r requirements.txt
python spam_detector.py

Sample Output:
Message: "Congratulations! You have won a free prize"
Result: Spam

Future Improvements:
Use deep learning models like LSTM or Transformers
Deploy the model as a web app using Flask or Stream

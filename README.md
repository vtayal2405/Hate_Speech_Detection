# Hate Speech Detection using Machine Learning

📌 **Overview**

This project implements a Hate Speech Detection system using Machine Learning. It classifies text into hate speech and non-hate speech categories using machine learning techniques.

🛠 **Features**

- Preprocessing of text data (tokenization, stopword removal, stemming, etc.)
- Feature extraction using CountVectorizer
- Machine learning models like Decision Tree Classifier
- Evaluation metrics: Accuracy, Precision, Recall

📊 **Dataset**

The dataset used is labeled_data.csv, which contains labeled tweets classified as:

- 0: Hate Speech
- 1: Offensive Speech
- 2: No Hate or Offensive Speech

🚀 **Usage**

1. Train the model:
   ```sh
   python train.py --model decision_tree_classifier
   ```

2. Test on sample text:
   ```sh
   python predict.py --text "Your input text here"
   ```


📈 **Model Performance**

- Accuracy : 87.59%


💡 **Developed by Vaibhav Tayal**

# Hate Speech Detection using Machine Learning

📌 **Overview**

This project implements a Hate Speech Detection system using Machine Learning. It classifies text into hate speech and non-hate speech categories using machine learning techniques.

🛠 **Features**

- Preprocessing of text data (tokenization, stopword removal, stemming, etc.)
- Feature extraction using TF-IDF or word embeddings
- Machine learning models like Decision Tree Classifier
- Evaluation metrics: Accuracy, Precision, Recall, and F1-score

🏗️ **Installation**

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hate-speech-detection.git
   cd hate-speech-detection
   ```

2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

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

3. Run the web application:
   ```sh
   streamlit run app.py
   ```

📈 **Model Performance**

📝 **Future Improvements**

- Enhance dataset with more diverse hate speech examples
- Experiment with transformer-based models (RoBERTa, DistilBERT)
- Deploy as a REST API for real-time detection

🤝 **Contributing**

Pull requests and feature suggestions are welcome! Please open an issue to discuss any improvements.

🛡 **License**

This project is licensed under the MIT License.

🌟 **Acknowledgments**

Special thanks to NLP and machine learning communities for open-source datasets and research.

---

💡 **Developed by Your Name**

SMS Spam Filter – Machine Learning Project

This is a machine learning-based spam detection system that classifies SMS messages as Spam or Ham (Not Spam). It uses text preprocessing, vectorization, and classification algorithms to predict whether a message is spam or not.

Features

* Real-time SMS classification
* CSV dataset analysis (`emails.csv`)
* Data preprocessing (tokenization, stopword removal, stemming)
* Vectorization using TF-IDF
* Model training using Multinomial Naive Bayes
* Evaluation with accuracy score, confusion matrix, and classification report
* User-friendly structure with clean, modular code

Project Structure

spam-detector/
│
├── spamDetection/
│   ├── emails.csv                  # Dataset
│   ├── spam_filter_model.pkl      # Trained model (optional)
│   ├── spam_detector.py           # Main code (training & prediction)
│   └── utils.py                   # Helper functions (e.g., preprocessing)
│
├── README.md                      # Project documentation
├── requirements.txt               # Python dependencies
└── .gitignore                     # Files to ignore by Git

Tech Stack

* Python 
* Pandas
* NumPy
* Scikit-learn
* NLTK (for text preprocessing)
* Jupyter / VS Code

How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/Shalinigowd/sms-spam-filter.git
   cd sms-spam-filter
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the code
   Open `spam_detector.py` and execute it (you can use VS Code, Jupyter, or CLI)

Example Output

Input: "Congratulations! You won a free ticket to Bahamas. Call now!"
Prediction: SPAM

Input: "Hey, are we still meeting at 6 PM?"
Prediction: HAM

Model Evaluation

* Accuracy: 97%
* Precision: 96%
* Recall: 95%

Dataset

* Source: `emails.csv` (included)
* Columns: `text`, `label`

Developed By

Shalini M
Computer Science and Business Systems
GitHub: [@Shalinigowd](https://github.com/Shalinigowd)
License

This project is open-source under the [MIT License](LICENSE)

📧 Spam Mail Detection using Logistic Regression

This project is a Spam Mail Classifier built with Python and Scikit-learn.
It uses TF-IDF Vectorization to extract features from email messages and a Logistic Regression model to classify emails as Spam (0) or Ham (1).

🚀 Features

Cleans and preprocesses email dataset.

Encodes labels: spam → 0, ham → 1.

Extracts features using TF-IDF Vectorizer.

Splits dataset into training and test sets.

Trains a Logistic Regression model.

Evaluates with accuracy score and classification report (precision, recall, F1-score).

📂 Project Structure
spam-mail-detection/
│── mail_data.csv           # Dataset (not included in repo if large)
│── spam_detector.py        # Main Python script
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
│── .gitignore              # Ignore unnecessary files

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/spam-mail-detection.git
cd spam-mail-detection

2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows

3. Install dependencies
pip install -r requirements.txt

▶️ Usage

Run the main script:

python spam_detector.py

📊 Example Output

Accuracy on training data: 0.98+

Accuracy on test data: 0.95+

Classification report with precision, recall, F1-score

🛠️ Tech Stack

Python 3.x

pandas – data handling

scikit-learn – ML model & feature extraction

📌 Future Improvements

Add more datasets for training.

Try advanced models (Naive Bayes, SVM, Random Forest).

Deploy as a web app with Flask/Streamlit.

👨‍💻 Author

Developed by Gourav Kumar Singh ✨

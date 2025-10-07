# spam-detection-naive-bayes
Features

🚀Text preprocessing using CountVectorizer

Machine learning model: Multinomial Naive Bayes

Splitting dataset into training and testing sets

Calculates accuracy score

Predicts whether new text messages are spam or not spam

🧩 Technologies Used

Python 🐍

scikit-learn (sklearn)

NumPy (for internal vector operations)

📊 Workflow

Data Preparation – A small sample dataset of text messages with labels (1 = spam, 0 = not spam).

Feature Extraction – Converts text into vectors using CountVectorizer().

Model Training – Fits a MultinomialNB() model to training data.

Evaluation – Computes accuracy using accuracy_score().

Prediction – Tests new messages to predict if they’re spam.

💻 How to Run the Project
1️⃣ Clone the repository
        
        git clone https://github.com/<your-username>/spam-detection-naive-bayes.git
        cd spam-detection-naive-bayes

2️⃣ Install dependencies

Make sure you have Python 3.x installed.
Then install required libraries using pip:


     pip install scikit-learn

3️⃣ Run the program

🧪 Example Output
Accuracy: 0.5
Prediction for sample text: [1]


✅ Here, 1 means the message is classified as spam, and 0 means not spam.

📘 Concepts Covered

Bag of Words model

Text vectorization using CountVectorizer

Naive Bayes algorithm

Model evaluation with accuracy metric

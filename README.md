# Email-Spam-Detection-Machine-Learning-Model-Project-in-Python

# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview

Email Spam Detection is a Machine Learning project that classifies text messages as **Spam** or **Not Spam**. It uses Python, CountVectorizer, and the Multinomial Naive Bayes algorithm to predict whether a given message is spam.

The project provides a simple web interface using Streamlit, where users can enter a message and check its category.

## 🎯 Objectives

- Detect spam and legitimate messages.
- Apply Machine Learning techniques to text classification.
- Convert text into numerical features using CountVectorizer.
- Build a simple interactive web application using Streamlit.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Dataset handling
- **Scikit-learn** – Machine Learning
- **CountVectorizer** – Text feature extraction
- **Multinomial Naive Bayes** – Classification algorithm
- **Streamlit** – Web application interface

## 📂 Project Structure

```text
spam-detection/
├── spam detection.py
├── spam.csv
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/shifa-th/Email-Spam-Detection-Machine-Learning-Model-Project-in-Python
```


### 2. Open the project folder

```bash
cd spam-detection
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run "spamdetection.py"
```

The application will open in your web browser.

## 🧠 How It Works

1. **Dataset Loading:** Loads the messages and their categories from `spam.csv`.
2. **Data Preprocessing:** Removes duplicate records and converts the labels `ham` and `spam` into `Not Spam` and `Spam`.
3. **Data Splitting:** Splits the dataset into training and testing sets.
4. **Feature Extraction:** Uses CountVectorizer to convert text into numerical features and remove common English stop words.
5. **Model Training:** Trains a Multinomial Naive Bayes classifier.
6. **Prediction:** Predicts whether a user-entered message is Spam or Not Spam.
7. **Display:** Shows the prediction in the Streamlit interface.

## 💻 Example

**Input:**
```text
Congratulations! You have won a free prize. Claim now!
```

**Possible Output:**
```text
Spam
```

**Input:**
```text
Hi, are we meeting for the project today?
```

**Possible Output:**
```text
Not Spam
```

These are example predictions; the actual result depends on the trained model.

## 🚀 Deployment

This application can be deployed using Streamlit Community Cloud by connecting the GitHub repository and selecting `spam detection.py` as the main application file.

## 🔮 Future Improvements

- Improve model accuracy using a larger and more diverse email dataset.
- Add model evaluation metrics and a confusion matrix.
- Improve the user interface.
- Test the model with real email data.
- Add support for uploading email files.

## 👩‍💻 Author

Developed as a Machine Learning mini-project using Python.

## 📄 License

This project is intended for educational and learning purposes.

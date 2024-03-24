
#Email Spam Classifier
####This project is an email spam classifier built using machine learning techniques in Python. It distinguishes between spam and ham (non-spam) emails using a logistic regression model trained on a dataset of email content.

Getting Started
To get started with this project, follow these instructions:

Clone the repository to your local machine.
Install the required dependencies listed in requirements.txt.
Run the email_classifier.py script to preprocess the data, train the model, and evaluate its performance.

task3_complete.ipynb
Prerequisites
Before running the project, ensure you have the following dependencies installed:

Python 3.x
pandas
scikit-learn
You can install the dependencies using pip:


pip install -r requirements.txt
Dataset
The dataset used for training the model consists of two categories: spam and ham. It is stored in the enron1 directory, with subdirectories spam and ham, each containing email text files.

Usage
The main script email_classifier.py contains the following functionalities:

Reading and preprocessing the dataset.
Splitting the dataset into training and testing sets.
Vectorizing the text data using CountVectorizer.
Training a logistic regression model.
Evaluating the model's performance using accuracy, confusion matrix, and classification report.
Results
After running the script, you'll see the accuracy score, confusion matrix, and classification report printed in the console. Additionally, the top 10 positive (spam-related) and negative (ham-related) features are displayed, providing insights into the words most indicative of spam and ham emails.


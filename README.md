# Bharat-Intern---SMS-Spam-Classifier
"SMS Spam Classifier is a machine learning project that accurately identifies and filters spam messages from legitimate ones. Utilizing natural language processing techniques, it provides a reliable solution for detecting unwanted messages, ensuring users receive only relevant and safe text communications."

This project aims to develop a robust SMS spam classifier using machine learning techniques. Leveraging Python and popular libraries such as pandas, scikit-learn, and NumPy, this classifier efficiently distinguishes between spam and non-spam (ham) messages, aiding in the filtration of unwanted messages.

Features:

Data Loading and Preprocessing: The project seamlessly loads the SMS dataset and preprocesses it to prepare the data for classification. It maps labels to binary values (0 for ham, 1 for spam) for training.
Text Vectorization: Utilizing the CountVectorizer from scikit-learn, the project transforms text data into numerical vectors, enabling machine learning algorithms to process and analyze textual information effectively.
Model Training: Employing the Multinomial Naive Bayes classifier, the project trains a predictive model on the vectorized SMS dataset, enabling accurate classification of incoming messages.
Model Evaluation and Prediction: The classifier's performance is evaluated using metrics such as accuracy and classification report. Additionally, the project allows users to input SMS messages for real-time prediction, providing immediate feedback on whether the message is likely spam or not.
Usage: This project serves as a valuable tool for filtering spam messages in various applications, including mobile communication platforms, email systems, and social media platforms, contributing to a cleaner and safer messaging environment for users.

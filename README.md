Explainable and Multi-Model Sentiment Analysis for Azerbaijani
This project presents a multi-model sentiment analysis system for Azerbaijani, a low-resource language. The system classifies user comments as either positive or negative, utilizing various machine learning models and providing explainable AI features for enhanced transparency and user trust.





Important Note: Due to file size limitations, this repository does not include the trained model weights or the full datasets. The repository contains the source code for the models, algorithms, and the Flask-based web application.


Project Highlights

Multi-Model Approach: The system evaluates three distinct classification models: TF-IDF + Logistic Regression, LaBSE + BiGRU, and XLM-RoBERTa. This approach allows for a comparative analysis of different model architectures and their respective performances.




Explainable AI (XAI): To provide insight into model decisions, the SHAP method is used. This analysis is applied to the Logistic Regression model, visualizing how individual words contribute to the sentiment prediction and making the decision-making process more transparent.




High Performance: The XLM-RoBERTa model achieved the highest performance with an 85% accuracy and a 0.84 macro F1-score, surpassing the other models. This model particularly stands out for its balanced and successful prediction of the negative class, which is often a challenge in low-resource languages.




Comprehensive Dataset: The project utilized a custom dataset created by combining an open-source, labeled dataset from Hugging Face with approximately 30,000 user reviews scraped from the Google Play Store. This resulted in a robust dataset of over 55,000 examples.




Intuitive Web Interface: A Flask-based web application was developed to provide a user-friendly interface. It allows users to input text and see real-time sentiment predictions from all three models simultaneously, along with the SHAP-based explanation for the Logistic Regression model.



Getting Started
To run the project locally, you need to set up the environment and acquire the necessary data and model files separately.

Clone the repository:

git clone https://github.com/husods/NLP-studies.git
Install dependencies: Navigate to the project directory and install the required libraries.

pip install -r requirements.txt
Run the application:

python app.py
For a detailed explanation of the methodology, model architectures, and performance metrics, please refer to the full Project Report.


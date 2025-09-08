# MonkeyPoxProject
MonkeyPoxProject 🐒

Welcome to the MonkeyPoxProject! This project focuses on analyzing Twitter data related to the Monkeypox outbreak, applying machine learning techniques to process, analyze, and visualize the data. The goal is to extract valuable insights on public sentiment and discussions surrounding this health crisis, which has caught the attention of the world. 🌍

🔍 What You’ll Find in This Project:

Data Preprocessing 🧹:
The first step of any text-based project is to clean the raw data. Tweets often contain noisy elements like URLs, special characters, and irrelevant numbers. In this step, the text data was cleaned, tokenized, and stopwords were removed, leaving a much cleaner, structured dataset.

Text Classification 📊:
A machine learning model was trained to classify the sentiment of each tweet, categorizing them into positive, negative, or neutral. This allows us to gauge how the public is reacting to the Monkeypox outbreak.

Data Visualization 🌈:
Visualizations such as word clouds, bar charts, and confusion matrices were created to highlight trends in the data. Word clouds show the most common terms used in relation to Monkeypox, while confusion matrices help visualize how well our models are performing.

Model Evaluation 🧠:
The performance of the models was evaluated using metrics such as accuracy, precision, recall, and F1-score. The final models were fine-tuned for better accuracy.

📊 Key Results:
1. Sentiment Analysis:

The model was able to classify the sentiment of tweets into positive, negative, and neutral categories. Here’s a breakdown of the average tweet length and sentiment distribution:

Sentiment	Mean Tweet Length	Std. Dev	Min Length	Max Length	Count
Negative	185.30	95.89	33	788	884
Neutral	122.88	77.75	10	807	4303
Positive	179.62	82.54	20	427	600
2. Model Performance:

The project used two machine learning models for sentiment classification: Logistic Regression and Random Forest.

Logistic Regression:

Accuracy: 88.01%

Precision: 0.95 (negative), 0.88 (neutral), 0.86 (positive)

Recall: 0.70 (negative), 0.91 (neutral), 0.64 (positive)

F1-Score: 0.80 (negative), 0.79 (neutral), 0.85 (positive)

Random Forest:

Accuracy: 89.89%

Precision: 0.94 (negative), 0.90 (neutral), 0.91 (positive)

Recall: 0.94 (negative), 0.94 (neutral), 0.80 (positive)

F1-Score: 0.94 (negative), 0.91 (neutral), 0.85 (positive)

Here are the confusion matrices for both models:

Logistic Regression:


Random Forest:


3. Hyperparameter Tuning:

GridSearchCV was used to fine-tune the Logistic Regression and Random Forest models. After optimization, the models performed even better:

Logistic Regression:

Best Cross-Validation Score: 0.93

Best Parameters: {'C': 100, 'max_iter': 100, 'solver': 'liblinear'}

Random Forest:

Best Cross-Validation Score: 0.87

Best Parameters: {'n_estimators': 100, 'max_depth': None, 'min_samples_split': 10}

The tuned models showed a significant improvement in accuracy and consistency.

📌 Why This Matters:

The Monkeypox outbreak has prompted discussions worldwide. By analyzing Twitter data, we gain insights into how social media shapes public perception and how information spreads during a health crisis. The public sentiment detected through machine learning can help health organizations understand public concerns, correct misinformation, and improve communication strategies.

This project highlights how data science and machine learning can be used to analyze real-time data, such as social media posts, to better understand and address public health issues.

🌟 Get Involved!

Explore the Notebook 🧑‍💻: Dive into the Jupyter notebook to see the complete analysis and code.

Run the Code 🚀: You can run the project on your own machine and modify it to fit your needs.

Contribute 🤝: If you have suggestions or improvements, feel free to contribute!

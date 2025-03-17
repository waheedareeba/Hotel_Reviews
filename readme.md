🏨 Sentiment Analysis on Luxury Hotel Reviews

📌 Project Overview
Understanding customer sentiment is crucial for the hospitality industry. This project analyzes luxury hotel reviews and classifies them into three categories:
✔ Positive 😊 – Guests had a great experience
✔ Neutral 😐 – Mixed or average reviews
✔ Negative 😡 – Guests were dissatisfied

Using NLP & Machine Learning, this analysis helps hotels improve their services based on real customer feedback.

🔍 Key Features
✅ Preprocessing & Feature Engineering

Tokenization, Stopword Removal, Lemmatization
TF-IDF,Doc2Vec for feature extraction
✅ Machine Learning Models

Random Forest for sentiment classification
Performance evaluation using Precision, Recall, F1-score
✅ Data Insights & Visualizations

Sentiment distribution plots
Feature importance analysis
✅ Real-World Application
📊 Hotels can use this model to identify pain points, improve guest experience, and enhance customer satisfaction.

🛠️ Technologies Used
Python 🐍
NLP: NLTK, scikit-learn
Machine Learning: Random Forest
Data Visualization: Matplotlib, Seaborn,Plotly
Jupyter Notebook for development
📂 Dataset
📌 The dataset is sourced from Kaggle, containing thousands of real customer reviews of luxury hotels.
🔗 Dataset: The dataset is provided in the repository. 

🚀 How to Run the Project
1️⃣ Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/luxury-hotel-sentiment.git
cd luxury-hotel-sentiment
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook sentiment.ipynb
4️⃣ Load the dataset and execute the notebook step by step.

📊 Results & Performance
🟢 Example Predictions:

Review	Predicted Sentiment
"The hotel was fantastic! Amazing service."	😊 Positive
"It was okay, but could be better."	😐 Neutral
"Terrible experience, rude staff."	😡 Negative
📈 Model Accuracy: 70% 

🖼️ Sample Visualizations:
![Sentiment Analysis](HOTEL_REVIEWS/wordcloud.png)

🎯 Future Improvements
✅ Implement deep learning models (LSTMs, Transformers)
✅ Fine-tune hyperparameters for higher accuracy
✅ Deploy as a web app using Streamlit for real-time predictions

📌 Conclusion
This project provides actionable insights for hotel management by analyzing guest sentiment. With further improvements, it can be deployed as a real-world solution to enhance customer satisfaction in the hospitality industry.

📌 If you found this useful, don’t forget to ⭐ the repo!


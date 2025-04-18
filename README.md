# Sentiment Analysis of Chatbot Conversations using TextBlob, SVM & LSTM

## 🎯 Objective

This project demonstrates the application of **Natural Language Processing (NLP)** techniques for **sentiment analysis** on chatbot conversations. The goal is to compare **rule-based**, **machine learning**, and **deep learning** approaches using real and labeled data.

---

## 📦 Tools & Libraries Used

- `TextBlob` – Rule-based sentiment analysis
- `scikit-learn` – LinearSVC classifier with TF-IDF vectorization
- `Keras/TensorFlow` – LSTM model trained on the IMDB dataset
- `Pandas & Matplotlib` – Data manipulation and visualization
- `Google Colab` – Development environment

---

## 🧠 Skills Demonstrated

- Preprocessing and analyzing textual data
- Training and evaluating NLP sentiment models
- Tokenizing and vectorizing text (TF-IDF & Keras tokenizer)
- Building LSTM models for sequence understanding
- Comparing and visualizing multi-model outputs
- Explaining technical results to a non-technical audience

---

## 📊 Sample Output

| Sentence                                | TextBlob   | LinearSVC | LSTM     |
|-----------------------------------------|------------|-----------|----------|
| "How do I change my flight date?"       | Neutral    | Negative  | Neutral  |
| "I missed my connecting flight."        | Neutral    | Negative  | Negative |
| "Can I add extra baggage?"              | Neutral    | Negative  | Neutral  |

---

## 🚀 How to Run

1. Open each notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `chatbot_data.tsv`
3. Run the cells step-by-step in each notebook: Lab 10, Lab 11, and Lab 12
4. View sentiment predictions and comparison plots

---
## 📊 Sentiment Analysis Comparison (Final Result)
The following chart shows the sentiment distribution of chatbot messages as predicted by:

- 🧠 **TextBlob** – rule-based model
- 🤖 **LinearSVC** – machine learning classifier (scikit-learn)
- 🔬 **LSTM** – deep learning model (Keras with IMDB)

![Sentiment Comparison Chart]:https://github.com/richapatel93/Sentiment-Analysis-of-Chatbot-Conversations-using-TextBlob-SVM-LSTM/blob/main/Screenshot%202025-03-27%20223619.png
:https://github.com/richapatel93/Sentiment-Analysis-of-Chatbot-Conversations-using-TextBlob-SVM-LSTM/blob/main/hi.png




## 📌 Reflection Highlights

- TextBlob is fast and interpretable but limited to surface-level emotion.
- LinearSVC is more scalable but highly dependent on labeled training quality.
- LSTM provided the most balanced and nuanced results, understanding context better.

---
## 🔮 Future Work

Here are some potential extensions and improvements for this project:

- **Fine-tune LSTM on domain-specific data** (e.g., airline chatbot conversations) to improve accuracy for formal/helpful queries.
- **Train on a balanced dataset** that includes more "neutral" examples to help the ML and DL models handle polite requests better.
- **Use BERT or transformer-based models** like RoBERTa or DistilBERT to improve context understanding and sentiment detection.
- **Add emotion classification** (joy, anger, frustration) instead of just sentiment (positive/negative/neutral).
- **Visual dashboard** to interactively explore sentiment flows over conversation timelines using tools like Plotly or Streamlit.
- **Real-time sentiment tracking** for live chatbot integration to detect frustration or satisfaction instantly.

These ideas would further enhance the model's real-world application in chatbot systems.


## 🤝 Looking for Opportunities

I'm actively seeking **internships** or **entry-level roles** in:

- Data Science  
- NLP / AI / ML  
- Data Engineering / Analytics  

📫 Let’s connect www.linkedin.com/in/richa-patel93 or message me through GitHub!

---

## 📁 License

This project is for academic and skill demonstration purposes only.

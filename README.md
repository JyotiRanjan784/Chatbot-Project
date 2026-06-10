# 🎓 Chatbot Project (Task 1 & Task 2)

## 📌 Overview

This project implements two types of chatbots:

* **Task 1:** Rule-Based Chatbot
* **Task 2:** NLP-Based Chatbot using Machine Learning

The goal is to compare traditional pattern-matching approaches with modern NLP techniques.

---

## 🤖 Task 1: Rule-Based Chatbot

* Uses predefined patterns and responses
* Implements:

  * Text preprocessing (lowercase, punctuation removal)
  * Keyword matching
  * Regex-based intent detection
* Simple and fast but limited to known patterns

---

## 🧠 Task 2: NLP Chatbot

* Uses Machine Learning for intent classification
* Techniques used:

  * Tokenization
  * Lemmatization
  * Stopword removal
  * TF-IDF Vectorization
  * Logistic Regression classifier
* Can understand different phrasings of user input

---

## 📁 Files Included

* `chatbot.py` → chatbot project (Task: 1 & 2)
* `screenshot.png` → 6-turn chatbot conversation

---

## ▶️ How to Run

### Run Rule-Based Chatbot

```bash
python chatbot.py
```

## 📊 Model Performance

* Model: Logistic Regression
* Feature Extraction: TF-IDF
* Accuracy: (your result here, e.g. 85%)

---

## 💬 Example Conversation

User: hi
Bot: Hello! How can I help you?

User: what courses do you offer
Bot: We offer various undergraduate and postgraduate programs.

User: what is the fee
Bot: The fee structure varies by course.

---

## 📸 Screenshot

A 6-turn conversation screenshot is included in the repository.

---

## 🆚 Comparison (Task 1 vs Task 2)

The rule-based chatbot is simple and efficient but limited to predefined patterns. It struggles with variations in user input. In contrast, the NLP chatbot uses machine learning to understand intent more flexibly and accurately. It performs better with unseen or differently phrased queries, making it more suitable for real-world applications.

---

## 🚀 Conclusion

The NLP-based chatbot provides better performance and scalability compared to the rule-based approach, although it requires more data and processing.

---

## 👨‍💻 Author

Jyoti Ranjan Barik

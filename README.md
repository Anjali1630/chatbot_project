# 🤖 AI Chatbot using TensorFlow & NLTK

An intelligent chatbot built using **Python**, **TensorFlow**, **Keras**, and **NLTK** for intent classification and natural language processing. The chatbot understands user queries, predicts user intents using a neural network, and generates appropriate responses.

---

## 🚀 Features

* Intent-based conversational AI chatbot
* Natural Language Processing (NLP)
* Neural network-based intent classification
* Text preprocessing using NLTK
* Customizable training dataset
* Interactive command-line chatbot

---

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* NLTK
* NumPy
* Pandas
* Scikit-learn
* Flask

---

## 📂 Project Structure

```text
chatbot_project/
│
├── data/
│   └── intents.json
├── models/
│   ├── chatbot_model.h5
│   ├── words.pkl
│   └── classes.pkl
├── src/
│   ├── chatbot.py
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── __init__.py
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Anjali1630/chatbot_project.git
cd chatbot_project
```

Create a virtual environment:

```bash
python -m venv chatbot_env
```

Activate the environment (Windows):

```bash
chatbot_env\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## 🧠 Train the Model

Run the following command to train the chatbot:

```bash
python main.py --train
```

This generates:

* `chatbot_model.h5`
* `words.pkl`
* `classes.pkl`

inside the `models` folder.

---

## 💬 Run the Chatbot

```bash
python main.py
```

Example:

```text
You: Hello
Bot: Hi! How can I help you today?

You: Thanks
Bot: You're welcome!

You: Bye
Bot: Goodbye! Have a great day!
```

---

## 📈 Future Improvements

* Web-based chatbot interface
* Voice interaction support
* Database integration
* Context-aware conversations
* Integration with Generative AI models
* Deployment using Flask or FastAPI

---

## 👩‍💻 Author

**Anjali**

GitHub: **https://github.com/Anjali1630**

# Chatbot with NLP - Conversational AI

# 🚀 Project Overview

This project showcases a conversational AI chatbot powered by Natural Language Processing (NLP). The chatbot uses machine learning and language processing techniques to recognize user inputs, identify intents, and respond appropriately. The system integrates popular Python libraries to ensure efficiency and simplicity while offering a user-friendly web interface for seamless interactions.

--- 

# Key Features

## ✨ Interactive and Intelligent:

Detects user intents (e.g., greetings, farewells, gratitude, technical queries) using NLP techniques.
Responds dynamically to user inputs with predefined or contextually relevant replies.

## 🖥️ Streamlit Interface:

A real-time, interactive web-based interface built with Streamlit.

## 🛠️ Easy Intent Customization:

Add, edit, or define new intents in a structured JSON file for easy modifications.

## 📊 History Tracking:

Conversation history is stored and viewable via an intuitive sidebar option.

## 🔮 Machine Learning Integration:

Leverages ML models via scikit-learn to map user inputs to intents.

## 🛠️ Built With

The following tools and libraries power this chatbot:

* Python 3.x
* nltk for natural language processing and tokenization.
* scikit-learn for intent classification using machine learning models.
* Streamlit for the user-friendly web interface.
* JSON for managing intent patterns and responses.

## 📥 Installation Instructions

Clone the Repository:
```
git clone <repository-url>
cd <repository-directory>
```

## Set up Your Environment

### Create a Virtual Environment (Recommended):

``` python -m venv venv
source venv/bin/activate  # Use `venv\Scripts\activate` on Windows
```

### Install Required Dependencies:

```
pip install -r requirements.txt
```

### Download Essential NLTK Data

```
import nltk
nltk.download('punkt')
```

## 💬 How to Use

To launch the chatbot interface:

### Start the Streamlit App:

```
streamlit run app.py
```

### Open the Chat Interface:

The default browser will open with the chatbot interface. Input your message and press Enter to get responses.

## 🧠 How It Works

1. User Input: The chatbot receives user messages via the Streamlit interface.
2. NLP Preprocessing: Input is tokenized and processed using the nltk library.
3. Intent Detection: Machine learning models classify user input into predefined intents using scikit-learn.
4. Response Generation: Based on the detected intent, the chatbot retrieves an appropriate response from intents.json.
5. Conversation History: Interactions are logged into chat_log.csv, visible through the web interface's history option.

## 🗂️ Managing Intents

The chatbot's response system relies on the intents.json file. You can edit this file to:

* Add new intents and their patterns/responses.
* Update or remove existing ones.

The structure of each intent follows this example:

```
{
  "tag": "greeting",
  "patterns": [
    "Hi",
    "Hello",
    "Good morning"
  ],
  "responses": [
    "Hello! How can I assist you today?",
    "Hi there! How can I help you?"
  ]
}
```

Make changes to intents.json to customize chatbot behavior easily.

## 🕒 Conversation History

* All user-bot conversations are logged in chat_log.csv.
* View this history using the sidebar option in the Streamlit interface to analyze interactions or debug.

## 🛠️ Contributing

We welcome contributions!
If you have a feature request, bug fix, or enhancement idea:

1. Fork the repository.
2. Create a branch (feature-branch-name).
3. Submit a pull request with a clear description of changes.

## 📜 License

This project is licensed under the MIT License. For more details, see the LICENSE file.

## 🙏 Acknowledgments

* nltk: For natural language preprocessing and tokenization.
* scikit-learn: For enabling intent recognition through machine learning.
* Streamlit: For creating an interactive and intuitive user experience.

## 🔗 Links

* [GitHub Repository](https://chatgpt.com/c/6756f15a-bdb8-8005-a01f-fde6e2779a85)
* [Documentation](https://botpress.com/blog/nlp-chatbot)
* [Community Chat/Forum](https://community.intersystems.com/post/step-step-guide-create-customized-chatbot-using-spacy-python-nlp-library)

# implementation-of-chatbot-using-nlp
## Table of contents :
  1. Introduction
  2. Features
  3. Technologies used
  4. Installation
  5. Required libraries
## INTRODUCTION:
This project implements a simple chatbot that uses NLP to understand and respond to user inputs.the chatbot is designed to simulate human-like conversations and can be extended for various cases.
## FEATURES
* NLP Based chat understanding: The chatbot uses NLP techniques to parse and understand user input.
* content awareness: Keeps track of conversations context to provide more relevant responses. 
* Predefined responses: uses a set of predefined responses based on keyword mathching.
## TECHNOLOGIES USED
* Python
* Ntlk
* Tensor flow
* Flask/FastAPI
## INSTALLATION
*Clone the repoitory
git clone https://github.com/your-username/chatbot-nlp.git
cd chatbot-nlp
*Install dependencies
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
* Download NLP resources:
python -m spacy download en_core_web_sm
python -m nltk.downloader punkt


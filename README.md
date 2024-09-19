Medical Symptom Checker Chatbot
This project is a simple Medical Symptom Checker Chatbot that identifies diseases based on symptoms provided by the user. It uses Natural Language Processing (NLP) with spaCy to extract symptoms from user input and matches them with a predefined symptom-disease mapping. The chatbot can run as a console-based interactive tool or be deployed using a web interface with Flask and Ngrok.

Features
Symptom Recognition: Extracts symptoms from user input using basic NLP techniques.
Symptom-Disease Mapping: Matches recognized symptoms to diseases using a dictionary or dataset.
User Interaction: Allows users to describe their symptoms in natural language and provides disease predictions.
Two Modes: Can be run in a loop-based console mode or deployed as a Flask web service with Ngrok for public access.

Tech Stack
Language: Python 3
Libraries:
Flask: For building a web interface for the chatbot.
spaCy: For natural language processing and extracting symptoms.
pandas: For handling the symptom-disease mapping.
Ngrok: For exposing the Flask app to the web.

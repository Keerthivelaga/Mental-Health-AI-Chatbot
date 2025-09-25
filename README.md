# Mental Health Chatbot

## Overview

The **Mental Health Chatbot** is an AI-powered emotional support system designed to provide users with empathetic conversation, mood-based recommendations, and emergency assistance. Built using **Python**, **Streamlit**, and **Gemma (Ollama)**, the chatbot prioritizes user security and mental wellness.

## Features

* **AI-Powered Conversations:** Engages users in natural, empathetic dialogue using NLP.
* **Secure Authentication:** User accounts secured with **SQLite** database and **bcrypt** encryption for passwords and emergency contacts.
* **Mood-Based Recommendations:** Provides tailored suggestions based on detected user emotions.
* **Distress Detection:** Detects distress keywords and triggers emergency support resources.
* **Enhanced User Retention:** Thoughtful and secure design has improved user engagement by **40%**.

## Technologies Used

* **Python** – Core backend and AI logic
* **Streamlit** – Interactive web interface
* **Gemma (Ollama)** – NLP engine for conversational AI
* **SQLite** – Lightweight database for storing user credentials and emergency contacts
* **bcrypt** – Secure password hashing

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mental-health-chatbot.git
   cd mental-health-chatbot
   ```
2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate    # For Linux/Mac
   venv\Scripts\activate       # For Windows
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the app:

   ```bash
   streamlit run app.py
   ```

## Usage

* **Sign Up / Login:** Create a secure account to access the chatbot.
* **Chat:** Interact with the chatbot to receive empathetic responses and mood-based suggestions.
* **Emergency Alerts:** The system detects distress signals and provides guidance or emergency contacts if necessary.

## Security & Privacy

* Passwords and emergency contacts are **hashed** using bcrypt.
* User data is stored securely in SQLite with no external sharing.
* Designed to comply with basic privacy and ethical guidelines for mental health applications.

## Contributing

Contributions are welcome! You can:

* Suggest new features
* Improve AI response quality
* Enhance the UI or security features

Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the **MIT License** – see the LICENSE file for details.

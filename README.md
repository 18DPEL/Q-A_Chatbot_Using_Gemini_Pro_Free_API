# Gemini LLM Q&A Application
This application utilizes the Google GenerativeAI API to create a question and answer chatbot interface powered by the Gemini Pro model. Users can input questions, and the chatbot will provide responses based on the model's training.

# Features
Interactive Chat Interface: Users can input questions and receive responses from the Gemini Pro model in real-time.
Session Chat History: The application stores the chat history for the current session, allowing users to view past interactions.
Easy Deployment: Built using Streamlit, the application can be easily deployed and accessed through a web browser.
# Requirements
Python 3.9 or higher
Streamlit
Google GenerativeAI Python SDK
A valid API key for accessing the Google GenerativeAI API
# Installation
Clone the repository to your local machine:

# bash
Copy code
git clone https://github.com/your-username/your-repo.git
Install the required Python packages:

# bash
Copy code
pip install -r requirements.txt
Set up your Google GenerativeAI API key as an environment variable named GOOGLE_API_KEY.

# Usage
Navigate to the project directory in your terminal.

# Run the Streamlit app:

# bash
Copy code
streamlit run qachat.py
Access the application through your web browser.

Input questions in the provided text box and click "Ask the Question" to receive responses from the chatbot.

# Django Chatbot App

This is a Retro style  Django-based chatbot web application that integrates with OpenAI models via OpenRouter. It features user registration, login, and a simple chat interface.open coode from livikit 


![image](https://github.com/user-attachments/assets/0c5fc9ab-a86d-4362-98ef-f0831da6aa33)
![image](https://github.com/user-attachments/assets/8a9b2de2-9fb3-4be0-acc8-1d65e4c3aa41)
![image](https://github.com/user-attachments/assets/a585506b-0563-4999-b75b-9af3c1ff7ffe)




## Features
- User registration and authentication
- Chat interface powered by OpenAI (via OpenRouter)
- Stores chat history (if enabled)

## Requirements
- Python 3.10+
- Django 4.x or 5.x
- `openai` Python package

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd DjAI/chatbot
   ```

2. **Create and activate a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install django openai
   ```

4. **Set up environment variables**
   - Set your OpenAI/OpenRouter API key in your environment or directly in `views.py` (not recommended for production).

5. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the app**
   - Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage
- Register a new user account.
- Log in with your credentials.
- Start chatting with the AI in the chat interface.

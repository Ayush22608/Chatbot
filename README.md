# Pandeyji Restaurant ChatBot 🍽️

A chatbot system designed for Pandeyji Eatery that uses FastAPI, MySQL, and Dialogflow to handle customer interactions and automate processes.

---

## Features ✨

- **FastAPI Backend**: A high-performance asynchronous backend powered by FastAPI.  
- **MySQL Database**: Manage eatery data with robust database support.  
- **Dialogflow Integration**: Intelligent chatbot with natural language understanding and training.  
- **Responsive Frontend**: User-friendly frontend using HTML and CSS.  

---

## Installation 🛠️

### Prerequisites
- Python 3.7 or higher  
- MySQL Database  
- Ngrok (optional for HTTPS tunneling)  

### Steps

1. Clone the repository:  
   ```bash
   git clone https://github.com/username/pandeyji-chatbot.git
   cd pandeyji-chatbot
   ```

2. Install required dependencies:  
   ```bash
   pip install -r backend/requirements.txt
   ```

3. Import the MySQL database:  
   ```bash
   mysql -u [username] -p pandeyji_eatery < db/pandeyji_eatery.sql
   ```

---

## Running the Backend Server 🚀

1. Navigate to the backend directory:  
   ```bash
   cd backend
   ```

2. Start the FastAPI server:  
   ```bash
   uvicorn main:app --reload
   ```

---

## Ngrok for HTTPS Tunneling 🌐

1. Download and install ngrok from [ngrok.com/download](https://ngrok.com/download).  
2. Extract and place `ngrok` in a folder accessible via terminal.  
3. Run the following command:  
   ```bash
   ngrok http 8000
   ```


## Frontend 🎨

- Open `frontend/home.html` in your browser.  
- Ensure the backend server is running to fully interact with the chatbot.  

---


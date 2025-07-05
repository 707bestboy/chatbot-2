# Medical Assistant Chatbot

A Medical Assistant Chatbot built with Python and Flask. This chatbot helps users with basic medical queries, provides information about symptoms, medicines, and general health advice. It is designed for demonstration and educational purposes and is **not** a substitute for professional medical advice.

---

## Screenshot 

![image](https://github.com/user-attachments/assets/d838102b-d563-4926-843c-1852ccaac1be)


## Features

- Interactive chatbot interface for users to ask medical questions
- Basic symptom checker and health information
- Modular and extensible Flask backend
- Easy-to-customize intents and responses

---

## Folder Structure

```
chatbot-2/
│
├── app.py                 # Main Flask application entry point
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── static/                # Static files (CSS, JS, images)
│   └── style.css
├── templates/             # HTML templates for Flask
│   └── index.html
          # Chatbot ML/NLP model (if any)

```

---

## Getting Started

### Prerequisites

- Python 3.8+
- `pip` (Python package manager)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/707bestboy/chatbot-2.git
    cd chatbot-2
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application:**
    ```bash
    python app.py
    ```

4. **Open your browser and navigate to:**
    ```
    http://localhost:5000
    ```

---

## How It Works

- Users interact with the chatbot via a web interface.
- Messages are sent to the Flask backend, which uses predefined intents (or a model) to generate responses.
- The chatbot provides informational, non-diagnostic answers.

---

## Disclaimer

This chatbot is for educational and informational purposes only. It is **not** intended for medical diagnosis or treatment. Always consult a licensed healthcare professional for medical concerns.

---

## Contact

For questions and contributions, open an issue or pull request on [GitHub](https://github.com/707bestboy/chatbot-2).

# StudyAssistant

StudyAssistant is an AI-powered study companion designed to help users digest, organize, and query educational content efficiently. It provides a clean, interactive user interface paired with a backend API for seamless study management.

---

## 🚀 Live Demo

Access the live application here:  
👉 **[StudyAssistant Live Server](https://studyassistant-z16z.onrender.com)**

---

## 🛠️ Features & Application Flow

* **Input & Upload:** Users submit study material text and tone through the web interface.
* **Interactive UI:** Users interact with the assistant to query notes, generate quizzes, or ask specific follow-up questions.
* **Response Delivery:** Dynamic responses and study materials are streamed back to the interactive front end in real-time.

---

## 📋 Requirements & Dependencies

To set up and run the project locally, ensure you have **Python 3.8+** installed along with the required libraries:

```text
gradio
requests
python-dotenv
google-genai
```
## ⚙️ Installation & Setup
### Clone the repository:

#### Bash
```text
git clone [https://github.com/shubhams8122/StudyAssistant.git](https://github.com/shubhams8122/StudyAssistant.git)
cd StudyAssistant
```
### Create and activate a virtual environment:

#### Bash
```text
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```
### Install Dependencies:

#### Bash
```text
pip install -r requirements.txt
```
### Environment Configuration:
```text
Create a .env file in the root directory and add your API keys:
```
#### Code snippet
```text
PORT=7860
GENAI_API_KEY=your_api_key_here
```

### Run Application:  

#### Bash
```text
python app.py
```
## 🎨 UI Design 

The user interface is built with Gradio, offering:  

	1. An intuitive web-based interface for interactive input and output.   
	2. Real-time query streaming and responses.  

Zero-configuration deployment compatibility with platforms like Render and Hugging Face Spaces.

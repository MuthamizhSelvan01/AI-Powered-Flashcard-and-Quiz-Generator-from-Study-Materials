# 📚 AI-Powered Flashcard and Quiz Generator from Study Materials

An intelligent, user-friendly web application that automatically generates flashcards and multiple-choice quizzes from uploaded educational PDFs. Designed to simplify revision, improve retention, and support self-paced learning through AI-driven automation.

---

## 🚀 Features

- ✅ Upload PDF documents for processing
- ✅ Automatically generate flashcards based on key concepts
- ✅ Create MCQ-style quizzes from flashcards
- ✅ Real-time quiz scoring and feedback
- ✅ Personalized dashboard with progress tracking
- ✅ Secure login and user data management
- ✅ Local SQLite database for storage

---

## 🧠 How It Works

1. **User uploads a study PDF**
2. **Text is extracted and cleaned**
3. **Flashcards are generated using an integrated AI model**
4. **Quizzes are created based on the flashcards**
5. **User takes quizzes and views results**
6. **Progress is tracked and stored in a database**

---

## 🛠️ Tech Stack

| Component          | Technology         |
|--------------------|--------------------|
| Frontend           | Streamlit          |
| Backend Logic      | Python             |
| AI Integration     | Gemini 1.5 Flash   |
| PDF Parsing        | PyPDF2             |
| Data Storage       | SQLite             |
| Authentication     | Streamlit session state & hashing |

---

## 📦 Installation

1. Clone this repo:
   git clone https://github.com/MuthamizhSelvan01/AI-Powered-Flashcard-and-Quiz-Generator-from-Study-Materials).git
   cd ai-flashcard-quiz-generator
Install dependencies:


pip install -r requirements.txt
Set your Gemini API key:

Create a .env file:

Load the value

Run the app:


streamlit run app.py
📁 Project Structure
├── app.py                  # Main Streamlit app
├── updated.py              # Core logic for PDF processing and generation
├── database.db             # SQLite database file
├── utils/                  # Utility functions (optional)
├── .env                    # API Key (do not share)
└── README.md               # Project documentation
🧪 Example Use Case
Upload a 30-page science textbook PDF, and within seconds, receive 25+ flashcards and an interactive quiz. View your performance on a dashboard and continue learning where you left off.

📈 Future Improvements
Add support for DOCX and TXT formats

Implement spaced repetition for flashcards

Export flashcards as PDF

Add voice-enabled flashcard reading

Real-time collaboration features


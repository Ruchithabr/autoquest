# 🧠 AutoQuest — AI-Based MCQ Generator

AutoQuest is a web-based application that automatically generates Multiple Choice Questions (MCQs) from uploaded documents and images. By combining Optical Character Recognition (OCR) and Natural Language Processing (NLP), it eliminates the manual effort of creating question banks, reducing preparation time by up to 70%.

## ✨ Features

- **Document & Image Upload:** Accepts PDFs and image files as input.
- **OCR Text Extraction:** Uses Tesseract OCR to extract raw text from uploaded files.
- **NLP Processing:** Analyzes extracted text to identify key concepts and generate meaningful questions.
- **Automated MCQ Generation:** Outputs well-structured multiple-choice questions with options.
- **User-Friendly Interface:** A clean, responsive web interface built with Flask.

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **AI/ML & NLP:** Natural Language Processing (NLP), Tesseract OCR
- **Libraries:** Pandas, NumPy, NLTK, PyPDF2
- **Frontend:** HTML, CSS, JavaScript (Jinja2 Templates)

## ⚙️ How It Works

1. **Upload:** The user uploads a document (PDF/Image) via the Flask web interface.
2. **Extract:** Tesseract OCR converts the visual text into machine-readable text.
3. **Process:** The NLP pipeline cleans the text, removes stop words, and identifies key sentences/phrases.
4. **Generate:** The system formulates questions based on the extracted key information and presents them to the user.

## 🚀 Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ruchithabr/autoquest.git
   cd autoquest
   ```

2. **Create a virtual environment (Recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On Mac/Linux:
   source venv/bin/activate
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: Make sure you have Tesseract OCR installed on your system and added to your PATH).*

4. **Run the application:**
   ```bash
   python app.py
   ```

5. **Open in your browser:**
   Navigate to `http://127.0.0.1:5000/`

## 📂 Project Structure

```text
autoquest/
│
├── static/          # CSS, JavaScript, and image files
├── templates/       # HTML files (Flask Jinja2 templates)
├── app.py           # Main Flask application
├── requirements.txt # Python dependencies
├── .gitignore       # Files to ignore in Git
└── README.md        # Project documentation
```

## 📫 Connect with Me

- **LinkedIn:** [linkedin.com/in/ruchitha-br](https://linkedin.com/in/ruchitha-br)
- **Email:** ruchitha.b.r.01@gmail.com
- **GitHub:** [github.com/Ruchithabr](https://github.com/Ruchithabr)

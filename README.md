# ✨ CLARA — Personal AI Assistant

\<p align="center">
&#x20; \<strong>Clarity in every conversation.\</strong>
\</p>

\<p align="center">
&#x20; A simple, interactive AI chatbot built with Python, Google Gemini API, and Gradio.
\</p>

---

## 🌟 About CLARA

**CLARA** is a personal AI assistant designed to make interacting with AI simple and accessible.

Built as my first LLM-powered application, CLARA connects to Google's Gemini model through its API and provides a conversational interface where users can ask questions and receive AI-generated responses.

With a minimal black-and-gold interface, CLARA brings together functionality and visual simplicity.

> This project uses an existing Large Language Model through an API. It does not train an LLM from scratch.

## 🖥️ Interface

**Design philosophy:** Minimal. Elegant. Intuitive.

- Black background with gold accents.
- Gold-colored user messages with dark text.
- Dark AI response messages with light text.
- Simple conversational interface.
- Browser-based local access.

## 🚀 Features

- **AI-powered conversations:** Ask questions and receive responses using Google Gemini.
- **Interactive chatbot:** Chat through a web-based interface built with Gradio.
- **Conversation display:** View messages and responses in the chat interface.
- **Custom UI:** A black-and-gold visual theme.
- **Local execution:** Run the application locally without deploying it to a public server.

## 🛠️ Tech Stack

| Technology        | Purpose                                |
| ----------------- | -------------------------------------- |
| Python            | Core programming language              |
| Google Gemini API | AI response generation                 |
| Google Gen AI SDK | Communication with Gemini              |
| Gradio            | Web-based chatbot interface            |
| Jupyter Notebook  | Development environment                |
| python-dotenv     | Secure environment variable management |

## ⚙️ Getting Started

Follow these steps to run CLARA on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/Bamathi-2007/CLARA.git
cd CLARA
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install google-genai python-dotenv gradio ipywidgets jupyter
```

### 4. Configure your API key

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Get your API key from [Google AI Studio](https://aistudio.google.com/apikey).

**Important:** Never upload your `.env` file or share your API key publicly.

### 5. Run the application

Open the project notebook in Jupyter Notebook or VS Code.

Run the notebook cells in order to:

1. Import the required libraries.
2. Load your Gemini API key.
3. Initialize the Gemini client.
4. Define the AI response function.
5. Create the Gradio interface.
6. Launch CLARA.

The application will be accessible through a local browser address, such as:

```text
http://127.0.0.1:7860
```

## 📁 Project Structure

```text
CLARA/
│
├── .env                  # API credentials (not committed)
├── .gitignore            # Excludes sensitive and unnecessary files
├── README.md             # Project documentation
└── app.ipynb             # Development notebook
```

*Update the notebook filename above if yours is different.*

## 🔐 Security

- API credentials are stored in environment variables.
- `.env` is excluded through `.gitignore`.
- Virtual environments and temporary Python files are excluded from version control.

## 🎯 Learning Outcomes

Through this project, I explored:

- Understanding how Large Language Models can be accessed through APIs.
- Connecting Python applications with Google's Gemini model.
- Sending prompts and processing AI-generated responses.
- Building an interactive chatbot interface using Gradio.
- Managing API credentials using environment variables.
- Creating a local AI-powered web application.

## 🔮 Future Improvements

- Persistent conversation history.
- Improved chat experience and interface responsiveness.
- Streaming AI responses.
- Chat session management.
- Additional AI capabilities.

## 👩‍💻 Author

**Bamathi G.**
---

CLARA — Clarity in every conversation. 💛

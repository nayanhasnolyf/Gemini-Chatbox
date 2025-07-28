# Gemini Python Chatbot

This is a simple Python script that connects to **Google Gemini** (Generative AI) using the official Google Python SDK.  
It lets you ask a question and get an AI-generated response directly in your terminal.

---

## 📌 Features

- Uses the latest **Gemini** models from Google (e.g., `gemini-1.5-pro`)
- Simple command-line interface
- Checks if your API key is set
- Easy to customize and extend

---

## 🚀 Requirements

- Python 3.7+
- `google-generativeai` Python package

---

## ⚙️ Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/yourusername/gemini-python-chatbot.git
   cd gemini-python-chatbot
    ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install google-generativeai
   ```

---

## 🔑 Setup API Key

1. Get your **Gemini API Key** from [Google AI Studio](https://aistudio.google.com/app/apikey).

2. Add your API key as an environment variable:

   ```bash
   export GEMINI_API_KEY="YOUR_API_KEY_HERE"
   ```

   *(On Windows Command Prompt, use `set GEMINI_API_KEY="YOUR_API_KEY_HERE"`)*

---

## 💡 Usage

Run the script:

```bash
python chatbot.py
```

Example output:

```
Gemini API Key exists and begins ABCD1234
Enter a Question: What is Gemini AI?
Question: What is Gemini AI?
Answer: Gemini is Google’s latest generative AI family of models, built for text, code, and more.
```

---

## 📂 File structure

```
gemini-python-chatbot/
 ├── chatbot.py     # The main script
 ├── README.md      # This file
 └── requirements.txt  # (Optional) List of dependencies
```

---

## ✅ `requirements.txt`

```txt
google-generativeai>=0.3.0
```

---

## 📝 License

This project is open-source.
Feel free to use, modify, and share it!

---

## 🤝 Contributing

Pull requests and issues are welcome.
Please open an issue first to discuss any major changes.

---

## 📫 Contact

Made with ❤️ by [Nayan](https://github.com/nayanhasnolyf)

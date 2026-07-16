# 🎙️ ElevenLabs Text-to-Speech App

A simple **Streamlit** application that converts text into natural-sounding speech using the **ElevenLabs Text-to-Speech API**.

## ✨ Features

* Convert text into high-quality speech
* Custom voice support using a Voice ID
* Download generated audio as an MP3
* Clean and simple Streamlit interface
* Secure API key management with `.env`

## 🛠️ Tech Stack

* Python
* Streamlit
* ElevenLabs Python SDK
* python-dotenv

## 📂 Project Structure

```text
.
├── app.py
├── .env
├── .gitignore
├── requirements.txt
├── output/
│   └── output.mp3
└── README.md
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root and add:

```env
ELEVENLABS_API_KEY=your_api_key_here
```

> **Important:** Never commit your `.env` file to GitHub.

## ▶️ Run the Application

```bash
streamlit run app.py
```

## 📖 How to Use

1. Enter the text you want to convert to speech.
2. Enter a valid ElevenLabs Voice ID (or use the default one).
3. Click **Generate Speech**.
4. Listen to the generated audio.
5. Download the MP3 file if desired.

## 📦 Requirements

* Python 3.9+
* Streamlit
* ElevenLabs SDK
* python-dotenv

Install all dependencies using:

```bash
pip install -r requirements.txt
```

## 📄 License

This project is intended for educational and learning purposes.

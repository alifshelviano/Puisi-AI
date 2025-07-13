# Puisi AI ke Suara

A Streamlit web application that generates Indonesian poetry from uploaded text, PDF, or DOCX files using Google Gemini AI, and converts the poem to speech (MP3) using Edge TTS.

## Features

- Upload `.txt`, `.pdf`, or `.docx` files as inspiration.
- Automatically generate a poem in Bahasa Indonesia with Gemini AI.
- Convert the poem to speech with selectable voice, rate, and pitch.
- Listen to and download the generated MP3 audio.

## Requirements

- Python 3.8+
- streamlit
- edge-tts
- python-dotenv
- google-generativeai
- PyPDF2
- python-docx

## Installation

```bash
pip install streamlit edge-tts python-dotenv google-generativeai PyPDF2 python-docx
```

## Setup

1. **Get a Gemini API Key:**  
   Sign up at https://aistudio.google.com/app/apikey and create an API key.

2. **Create a `.env` file** in your project directory:
    ```
    GEMINI_API_KEY=your_gemini_api_key_here
    ```

## Usage

```bash
streamlit run PuisiAI.py
```

- Open the web interface in your browser.
- Upload a file, select voice options, and click the button to generate and listen to your poem.

## Live
https://alifshelviano-aipuisi.streamlit.app/
  
## License

MIT License

---

**Note:**  
This app is for educational and creative purposes. Ensure you comply with the terms of use for Google Gemini and Edge

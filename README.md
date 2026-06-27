# 🌍 Text-to-Speech Studio

A **fast, hybrid, multilingual Text-to-Speech (TTS)** web application that converts text into natural-sounding speech across multiple languages. The application intelligently translates text when required and generates speech using both **online** and **offline** TTS engines for maximum flexibility.

Built with **Python**, **Gradio**, **gTTS**, **pyttsx3**, and **Deep Translator**.

---

## Demo Images 

![demo](https://github.com/Tanmay1112004/Text-to-Speech-Studio/blob/main/Screenshot%202025-08-09%20095523.png)


---

## 🚀 Features

* 🌍 **Multilingual Text-to-Speech**

  * Generate speech in **20+ Indian and international languages**.

* 🔄 **Automatic Translation**

  * Automatically translates input into the selected output language before speech generation.

* ⚡ **Hybrid Processing**

  * Detects when translation is unnecessary and generates speech instantly for faster performance.

* 🗣 **Voice Selection**

  * Choose **Male** or **Female** voice (English Offline Mode).

* 📴 **Offline Speech Synthesis**

  * Generate English speech without an internet connection using **pyttsx3**.

* 🎚 **Speech Rate Control**

  * Adjust the speaking speed in offline mode.

* 💻 **Interactive Web Interface**

  * Simple and responsive UI built with **Gradio**.

---

## 🛠 Tech Stack

| Technology      | Purpose                |
| --------------- | ---------------------- |
| Python          | Backend                |
| Gradio          | Web Interface          |
| gTTS            | Online Text-to-Speech  |
| pyttsx3         | Offline Text-to-Speech |
| Deep Translator | Language Translation   |

---

## 📂 Project Structure

```text
Text-to-Speech-Studio/
│── app.py
│── requirements.txt
│── README.md
│── assets/
│── outputs/
└── ...
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Tanmay1112004/polyglot-voice.git
cd polyglot-voice
```

### 2. Create a virtual environment (Recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Gradio will launch a local web server.

Open your browser and visit:

```
http://127.0.0.1:7860
```

---

## 🌐 Supported Features

* English
* Hindi
* Marathi
* Gujarati
* Bengali
* Tamil
* Telugu
* Kannada
* Malayalam
* Punjabi
* Urdu
* French
* German
* Spanish
* Italian
* Portuguese
* Japanese
* Korean
* Chinese
* Russian
* And many more...

---

## 📸 Demo

> Add screenshots or a GIF here.

```
assets/demo.gif
```

---

## 📌 Future Improvements

* 🎙 Multiple voice providers
* 🤖 AI-powered natural voices
* 📄 PDF & DOCX text reading
* 🎧 Audio download history
* ☁ Cloud deployment
* 🔊 Voice cloning support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Tanmay Kshirsagar**

* GitHub: https://github.com/Tanmay1112004

If you found this project helpful, consider giving it a ⭐ on GitHub!

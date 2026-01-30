# AI-Voice-AssisSure 👍
Here is a **professional, clean README.md** for your project.
You can **directly copy–paste** this into a file named **`README.md`** in your project folder or GitHub repo.

---

# 🤖 AI Voice Assistant – Agent Riya 9.0

Agent Riya 9.0 is a **Python-based desktop AI Voice Assistant** that allows users to interact with their system using voice commands.
It provides real-time responses, automates basic tasks, manages to-do lists, and retrieves information using online sources—all through a modern graphical user interface.

---

## 📌 Features

* 🎙️ Voice-controlled interaction
* 🔊 Text-to-Speech responses
* 🖥️ Modern desktop GUI using Tkinter
* 📋 To-Do Task Management (Add, Remove, Complete, Clear)
* 🌐 Open websites like YouTube, Google, Gmail
* 📚 Fetch information using Wikipedia
* 🔄 Multithreaded execution for smooth performance
* 💾 Persistent task storage using JSON

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **GUI Framework:** Tkinter
* **Speech Recognition:** SpeechRecognition (Google API)
* **Text-to-Speech:** pyttsx3
* **Data Storage:** JSON
* **Image Processing:** Pillow (PIL)
* **Concurrency:** Multithreading
* **APIs:** Wikipedia API

---

## 📂 Project Structure

```
AgentRiya/
│
├── main.py           # Main application file
├── tasks.json        # Stores user tasks (auto-created)
├── README.md         # Project documentation
└── assets/           # (Optional) Images or icons
```

---

## ⚙️ Requirements

### Software Requirements

* Python 3.9 or above
* Visual Studio Code (recommended)
* Working Microphone
* Internet Connection

---

## 📦 Required Python Libraries

Install the required libraries using:

```bash
pip install SpeechRecognition pyttsx3 wikipedia pillow pyaudio
```

> ⚠️ **Note (Windows users):**
> If `pyaudio` fails to install, download the appropriate `.whl` file from:
> [https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

---

## ▶️ How to Run the Project

1. Clone or download the project folder
2. Open the folder in **VS Code**
3. Open the terminal and run:

```bash
python main.py
```

4. Speak commands like:

   * “Open YouTube”
   * “Add task buy milk”
   * “What is artificial intelligence”
   * “Remove task 1”
   * “Exit”

---

## 🧠 How It Works

1. The user gives voice input through a microphone.
2. SpeechRecognition converts audio to text.
3. The command processor analyzes the input.
4. Actions such as task management, web browsing, or information retrieval are executed.
5. The assistant responds using text-to-speech and updates the GUI in real time.

---

## 🚧 Challenges & Solutions

**Challenges**

* Handling real-time voice input without freezing the UI
* Avoiding microphone conflicts during speech output

**Solutions**

* Implemented multithreading to separate UI and voice processing
* Temporarily disabled microphone while speaking

---

## 🚀 Future Enhancements

* Integration with ChatGPT or AI APIs
* Multi-language support
* Voice authentication
* Mobile and cloud-based versions

---

## 👨‍💻 Developer

**Sangamesh Sajjan**
Computer Science Engineer
Python | GUI Development | Voice Applications

---

## 📄 License

This project is for **educational and learning purposes**.

---

If you want, I can:

* ⭐ Make this **GitHub-optimized**
* 🎯 Add **badges & screenshots**
* 🧾 Create a **requirements.txt**
* 📦 Help convert it into an **EXE file**

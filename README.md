# 🧠 Voice & Eye-Controlled Accessibility System

A **Python-based accessibility solution** that enables users with physical disabilities to control their computer **without using a mouse or keyboard**. This system uses **eye-tracking** for cursor control and **voice commands** for keyboard input — making the experience intuitive, hands-free, and fully accessible.

It includes a smart **Natural Language Processing (NLP) module** that converts **free-form speech** into system-level commands (like opening apps or typing text), allowing disabled users to navigate their computer with ease.

---

## 💡 Features

- 👁️ **Eye Tracking**  
  Real-time tracking of the user's eye movements to control the mouse cursor.

- 🎤 **Voice Command System**  
  Issue system-level commands or type via speech using offline voice recognition.

- 🧠 **NLP-Powered Command Parsing**  
  Understands free-form natural language and maps it to specific OS actions.

- 🧩 **Voice Command Categories**  
  Supports categories like typing, navigation, app launching, file interaction, and more.

- 📶 **Offline Support**  
  Works without an internet connection using local models for speech recognition.

---

## 🛠️ Tech Stack

- **Python** – Core development language
- **Vosk** – Offline speech recognition engine
- **OpenCV** – For video stream capture and image processing
- **Mediapipe** – For facial and eye landmark detection

---

## ⚙️ How It Works

1. **Eye Tracking**  
   Uses Mediapipe and OpenCV to track the user's gaze direction and eye position to move the mouse pointer on screen.

2. **Voice Recognition**  
   Captures voice input via microphone, and transcribes it using Vosk’s offline models.

3. **Command Processing**  
   A rule-based or NLP-enhanced parser converts recognized speech into executable actions.

---

## 📦 Installation

### Prerequisites

- Python 3.7+
- Webcam and microphone
- Virtual environment (recommended)

### Dependencies

Install the required packages:

```bash
pip install opencv-python mediapipe vosk pyttsx3

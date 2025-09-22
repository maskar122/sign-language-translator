# ✋🤟 Sign Language Translator

## 📌 Overview

The **Sign Language Translator** is a machine learning/computer vision project that detects and translates sign language gestures into text or speech.
It aims to help bridge the communication gap between people with hearing or speech impairments and the general public.

This project uses:

* **Computer Vision (OpenCV/MediaPipe)** to detect hand landmarks.
* **Deep Learning Models (CNN/RNN/Transformer depending on implementation)** for gesture classification.
* **Text-to-Speech (TTS)** to convert predictions into spoken language.

---

## 🎥 Demo
![Sign Language Demo](https://github.com/maskar122/sign-language-translator/blob/ee6f3170f635c81cf593bc7c82f938033ca382d8/images/output1.png)
![Sign Language Demo](https://github.com/maskar122/sign-language-translator/blob/ee6f3170f635c81cf593bc7c82f938033ca382d8/images/output2.png)
![Sign Language Demo](https://github.com/maskar122/sign-language-translator/blob/ee6f3170f635c81cf593bc7c82f938033ca382d8/images/output3.png)
![Sign Language Demo](https://github.com/maskar122/sign-language-translator/blob/ee6f3170f635c81cf593bc7c82f938033ca382d8/images/output4.png)
![Sign Language Demo](https://github.com/maskar122/sign-language-translator/blob/ee6f3170f635c81cf593bc7c82f938033ca382d8/images/output5.png)



--

## ⚙️ Features

* Real-time **hand gesture detection** via webcam.
* Translate gestures into **English/Arabic text**.
* Optional **voice output** for accessibility.
* Custom dataset support for training new gestures.

---

## 🛠️ Tech Stack

* **Python 3.9+**
* **TensorFlow / PyTorch** (for model training)
* **OpenCV** (image capture and preprocessing)
* **MediaPipe** (hand detection & landmarks)
* **NLTK / SpeechRecognition / pyttsx3** (for speech/text modules)
* **Streamlit / PyQt5** (for GUI, if included in your project)

---

## 📂 Project Structure

```
sign-language-translator/
│── data/                # Dataset of sign language images/videos
│── models/              # Trained models (CNN, RNN, etc.)
│   │── gui.py           # (Optional) GUI application
│── README.md            # Project documentation
```

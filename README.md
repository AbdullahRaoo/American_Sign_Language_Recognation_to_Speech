# American Sign Language Recognition to Speech

This project is a complete system for recognizing sign language from hand gestures captured via webcam and converting it into text and speech. The project involves four major steps: Data Collection, Data Preprocessing, Model Training, and GUI-based Prediction.

## Dataset
The dataset used for model creation was created by ourselves. It consists of images of hand gestures corresponding to the 26 letters of the English alphabet.

## Objective
1. To develop a system capable of recognizing American Sign Language (ASL) hand gestures in real-time using a webcam.
2. To accurately translate recognized hand gestures into corresponding text.
3. To provide a text-to-speech conversion of the recognized gestures for auditory feedback.

## Project Structure

1. **Data Collection:**
    - The first step involves collecting images of hand gestures using a webcam. The images are saved in a directory structure where each folder corresponds to a different class (i.e., a different letter of the alphabet).
  
2. **Data Preprocessing:**
    - The collected images are processed using MediaPipe to extract hand landmarks. These landmarks are normalized and used as features for model training.
  
3. **Model Training:**
    - A RandomForestClassifier is trained on the preprocessed hand landmarks to recognize the corresponding letter of the alphabet.
  
4. **Predictor GUI:**
    - A graphical user interface (GUI) built with Tkinter is used to capture real-time hand gestures, predict the corresponding letter, and convert the recognized text into speech.

## Technologies Used

### Programming Language
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Libraries and Frameworks
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?style=for-the-badge&logo=google&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FF6F00?style=for-the-badge&logo=python&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white)
![customtkinter](https://img.shields.io/badge/customtkinter-FF6F00?style=for-the-badge&logo=python&logoColor=white)
![pyttsx3](https://img.shields.io/badge/pyttsx3-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- scikit-learn
- Tkinter
- PIL (Pillow)
- customtkinter
- pyttsx3

## License
This project is free to use. However, I encourage you to learn from it and not just copy-paste and run it.

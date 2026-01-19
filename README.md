# Sign Language to Speech Conversion System

## 📌 Overview
The **Sign Language to Speech Conversion System** is a machine learning–based application designed to help bridge the communication gap between **hearing-impaired, speech-impaired, and normal individuals**. The system recognizes hand gestures used in sign language and converts them into **audible speech** in real time.

By using computer vision and deep learning techniques, this project enables natural and interactive communication through a webcam-based gesture recognition system.

---

## 🎯 Project Objectives
- To recognize sign language hand gestures accurately
- To convert recognized gestures into readable text
- To transform text output into audible speech
- To enable real-time interaction using a webcam
- To improve accessibility for differently-abled individuals

---

## 🧠 Working Principle
The system works in the following stages:

1. **Gesture Capture**  
   Hand gestures are captured in real time using a webcam.

2. **Image Processing**  
   The captured frames are processed using OpenCV to prepare them for prediction.

3. **Gesture Recognition**  
   A deep learning model trained using **Google Teachable Machine** and implemented with **Keras** classifies the hand gestures.

4. **Text Mapping**  
   Each recognized gesture is mapped to its corresponding text representation.

5. **Speech Output**  
   The text output is converted into audible speech using a text-to-speech module.

---

## 🏗️ System Architecture
- **Input:** Webcam (hand gesture images)
- **Processing:** OpenCV for image handling
- **Model:** Keras-based deep learning model
- **Output:** Text display and voice output

---

## ⚙️ Technology Stack

### Programming Language
- Python

### Libraries & Frameworks
- Keras
- TensorFlow
- OpenCV
- NumPy
- Text-to-Speech (TTS)

### Tools
- Google Teachable Machine
- Google Colab
- GitHub

---

## 📁 Project Structure
├── training_data/ # Training images for sign language gestures
├── new_data/ # New gesture samples for testing
├── datacollection.py # Script to collect gesture images
├── text_test.py # Gesture recognition with text output
├── voice_test.py # Gesture recognition with speech output
├── *.h5 # Trained Keras model file
├── README.md # Project documentation

---

## 🚀 Key Features
- Real-time sign language recognition
- Deep learning-based gesture classification
- Webcam-based live detection
- Conversion of gestures into speech
- Simple and easy-to-use system

---

## 🧪 Testing
The system was tested under:
- Different lighting conditions
- Various hand orientations
- Real-time webcam input

The model showed reliable performance for gestures included in the training dataset.

---

## 📊 Results
- Accurate recognition of trained sign language gestures
- Real-time text and speech output
- Effective communication support for differently-abled users

---

## 🔮 Future Enhancements
- Support for complete sentences in sign language
- Multi-language speech output
- Improved accuracy using advanced CNN models
- Mobile and web application deployment
- Integration with assistive devices

---

## 👨‍💻 Author
**Bhargav C**  
Bachelor of Engineering – Computer Science & Engineering  
Bengaluru, India  

---

## 📄 License
This project is developed for academic and educational purposes.

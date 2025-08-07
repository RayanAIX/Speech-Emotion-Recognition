# 🎙️ Speech Emotion Recognition using CNN & Librosa

This deep learning project detects human **emotions** from audio speech samples using **Convolutional Neural Networks (CNN)** and **MFCC features** extracted with **Librosa**. It classifies audio into emotions such as **happy**, **sad**, **angry**, and more — making it a core module in affective computing systems.

---

## 🗣️ Audio Emotion Examples

### 🔊 Sample Audio Input  
<video src="https://github.com/user-attachments/assets/your_audio_input_placeholder.mp3" width="400" controls></video>

### 🤖 Predicted Emotion Output  
`Prediction: Happy 😊`

> 🎧 Dataset: [RAVDESS - Ryerson Audio-Visual Database of Emotional Speech and Song](https://zenodo.org/record/1188976)

---

## ⚙️ How It Works

1. Load RAVDESS speech audio files
2. Extract **MFCC (Mel-frequency cepstral coefficients)** using Librosa
3. Normalize and reshape data
4. Train a **Convolutional Neural Network (CNN)** to classify emotions
5. Evaluate and save the model for inference

---

## 🧠 Emotions Recognized

- Neutral 😐  
- Calm 😌  
- Happy 😀  
- Sad 😢  
- Angry 😠  
- Fearful 😨  
- Disgusted 🤢  
- Surprised 😲

---

## 🧠 Technologies Used

- Python 3  
- Librosa  
- NumPy  
- TensorFlow / Keras  
- Matplotlib  
- Sklearn  

---

## 📦 Requirements

```bash
librosa
numpy
tensorflow
scikit-learn
matplotlib
Install them using:
pip install -r requirements.txt

📁 Project Structure
File / Folder	Description
speech_emotion_recognition.py	Main script for model training and evaluation
predict_emotion.py	Script to load a model and predict emotion from new audio
Audio_Speech_Actors_01-24/	Extracted RAVDESS dataset folder
model.h5	Saved trained Keras model
requirements.txt	Required Python packages
README.md	Project documentation

🚀 How to Run
bash
Copy
Edit
pip install -r requirements.txt
python speech_emotion_recognition.py
Make sure the Audio_Speech_Actors_01-24/ folder is in the same directory after extracting the RAVDESS dataset.

To make predictions:

bash
Copy
Edit
python predict_emotion.py --file path_to_your_audio.wav
🧪 Sample Results
Audio File Name	Actual Emotion	Predicted Emotion
03-01-05-01-01-01-01.wav	Angry	Angry
03-01-02-01-02-01-05.wav	Calm	Neutral
03-01-06-02-01-02-03.wav	Fearful	Fearful

🔭 Future Enhancements
Add real-time microphone input emotion detection

Improve model with RNNs/LSTMs for better temporal analysis

Support multi-language speech recognition

Build a web app or REST API for deployment

👨‍💻 Author
Muhammad Rayan Shahid
AI & ML Enthusiast | LinkedIn | GitHub

⭐ If you found this project useful, please consider starring the repository!

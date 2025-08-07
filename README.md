# Emotion Detection from Speech using RAVDESS Dataset 🎤😄😢

This project is a deep learning-based Emotion Classifier that classifies emotions from speech using the **RAVDESS** dataset. It processes `.wav` audio files, extracts MFCC features, and uses a CNN-LSTM hybrid model for emotion classification.

---

## 📁 Dataset

- **Name:** RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- **Classes:** 
  - neutral, calm, happy, sad, angry, fearful, disgust, surprised
- **Format:** `.wav` audio files organized by actor folders
- **Download:** Already uploaded as `Audio_Speech_Actors_01-24.zip`

---

## 🧠 Model Architecture

- **Feature Extraction:** MFCC (Mel-frequency cepstral coefficients)
- **Model:** CNN + LSTM
- **Loss:** Categorical Crossentropy
- **Optimizer:** Adam

---

## 🛠️ Requirements

Install required Python libraries using:

```bash
pip install librosa numpy matplotlib scikit-learn tensorflow
```

---

## ▶️ How to Run

1. **Upload & Extract Dataset**
   - Upload `Audio_Speech_Actors_01-24.zip` to your environment
   - Extract it using:
     ```python
     import zipfile
     with zipfile.ZipFile("Audio_Speech_Actors_01-24.zip", 'r') as zip_ref:
         zip_ref.extractall("/mnt/data/Audio_Speech_Actors_01-24")
     ```

2. **Load and Preprocess Data**
   - Uses MFCC features
   - Encodes labels

3. **Train the Model**
   - Split into train and test sets
   - Train CNN + LSTM model

4. **Evaluate**
   - Accuracy and loss metrics
   - Visualize using confusion matrix

---

## 📊 Results

- **Training Accuracy:** ~XX% (Replace with actual value)
- **Test Accuracy:** ~YY% (Replace with actual value)

---

## 📈 Visualizations

- **Confusion Matrix**
- **Model Accuracy & Loss Graphs**

---

## 🔍 Future Improvements

- Add real-time microphone input prediction
- Integrate with a chatbot/emotion-aware system
- Improve model generalization

---

## 🤖 Author

**Muhammad Rayan Shahid**  
AI Enthusiast | YouTuber at [ByteBrilliance AI](https://www.youtube.com/@ByteBrillianceAI)

---

## ⭐ GitHub Repo

Stay tuned for more projects on AI, ML, DL, and Computer Vision!

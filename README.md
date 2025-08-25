# Emotion Detection 🎭

Detects **facial emotions** using **MobileNet (TensorFlow/Keras)** and **OpenCV**.



### Emotions Detected
😡 Angry | 🤢 Disgust | 😨 Fear | 😃 Happy | 😢 Sad | 😲 Surprise | 😐 Neutral  

---



## Project Structure

emotion-detection/  
├── emotion_detection.ipynb      Training & evaluation  
├── live_emotion_detection.py    Real-time webcam detection  
├── requirements.txt             Dependencies  
├── README.md                    Project documentation  
└── train/                       Dataset folder (place extracted dataset here)  



---

## Setup

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
pip install -r requirements.txt
```



## Dataset

train/
 ├── Angry/
 ├── Disgust/
 ├── Fear/
 ├── Happy/
 ├── Sad/
 ├── Surprise/
 └── Neutral/



## Training the Model

Run the Jupyter Notebook:

```bash
jupyter notebook emotion_detection.ipynb
```

- Trains MobileNet-based CNN model
- Uses EarlyStopping & ModelCheckpoint
- Saves best model as best_model.keras



## Live Emotion Detection

Run:

```bash
python live_emotion_detection.py
```

- Opens webcam feed
- Detects faces with Haar Cascade
- Displays predicted emotion on screen
- Press x to exit



 

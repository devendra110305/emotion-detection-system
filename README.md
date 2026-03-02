#  Real-Time Emotion Detection System

A real-time facial emotion recognition application that uses a webcam to detect human emotions and respond with visual and voice feedback.

This project combines computer vision, deep learning, and a graphical user interface to create an interactive system that recognizes facial expressions and communicates emotional responses.

## Features

- Real-time webcam face detection
- Emotion recognition using deep learning
- Voice feedback using text-to-speech
- Interactive GUI (Start / Stop camera)
- Smooth emotion prediction across frames
- FPS performance display
- Non-blocking speech processing
- Multi-face detection support

## Supported Emotions

- Happy  
- Sad  
- Angry  
- Surprise  
- Fear  
- Disgust  
- Neutral  

---

##  Tech Stack

- Python
- OpenCV
- DeepFace
- Tkinter
- pyttsx3
- Pillow
- NumPy


##  Installation

### 1. Clone the repository

git clone (https://github.com/devendra110305/emotion-detection-system.git)  
cd emotion-detection

### 2. Install dependencies

pip install -r requirements.txt

##  How to Run

python emotion_app.py

Steps:

1. Launch the application
2. Click Start Camera
3. Look at your webcam
4. Emotion appears on screen
5. System speaks a response
6. Click Stop Camera to exit

## How It Works

1. Webcam captures live video
2. Face detection identifies faces
3. Deep learning model predicts emotion
4. Predictions are smoothed across frames
5. GUI displays emotion and FPS
6. Text-to-speech provides audio feedback

##  System Requirements

- Python 3.8 – 3.11 recommended
- Webcam
- Minimum 4GB RAM
- Windows / Linux / macOS

GPU support improves performance but is optional.

## Common Issues

Camera not opening  
→ Ensure no other application is using the webcam.

Module not found error  
→ Install dependencies using requirements.txt.

Slow performance  
→ Reduce camera resolution or close background apps.

##  Future Improvements

- Emotion history tracking
- Emotion graphs and analytics
- Face recognition (identify person)
- Dark mode UI
- Mobile camera streaming
- CSV emotion logging
- Stress detection alerts

##  Contributing

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Open a pull request

## License

This project is open-source and available for educational and research purposes.

##  Author

Mahalinga Devendra Kumar


Sri Mittapalli College of Engineering


2026

## Support

If you like this project, please give it a star on GitHub.

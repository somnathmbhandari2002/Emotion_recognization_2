# Emotion_recognization_2
This code uses DeepFace and OpenCV to perform real-time emotion recognition from webcam video by analyzing each frame and displaying the detected dominant emotion on the screen with live camera feed.

# Real-Time Emotion Recognition with DeepFace and OpenCV

This project performs **real-time emotion recognition** using your webcam. It utilizes the [DeepFace](https://github.com/serengil/deepface) library for facial analysis and [OpenCV](https://opencv.org/) for video capture and display. The system detects the dominant emotion in each video frame and displays it on the screen.

## 🔍 Features

- Real-time webcam feed analysis
- Emotion recognition using DeepFace (anger, happy, sad, surprise, etc.)
- Live display of detected emotions on screen
- Runs locally on CPU (no GPU required)
- Break the detection loop with `q` key

## 📦 Requirements

Before running the project, ensure you have the following packages installed:

```bash
pip install deepface opencv-python
Note: deepface may also install tensorflow, keras, mtcnn, and other dependencies automatically.

🛠 Setup Instructions
Clone the repository or copy the script to your local system.

Ensure Python 3.7–3.10 is installed. (Recommended: Use a virtual environment.)

Install required packages:

pip install deepface opencv-python
Run the script:

🎯 Use Cases
AI-powered interviews for emotion analysis

Real-time mood monitoring

Research in human-computer interaction

Emotion-based adaptive UI systems

⚠️ Notes
enforce_detection=False ensures the system does not crash if no face is detected.

The model works best under good lighting and a clear frontal face view.

Accuracy may vary depending on webcam quality and lighting conditions.

📷 Screenshot

1 Neutral
![image](https://github.com/user-attachments/assets/2b34e64f-7a8f-48fc-a0b8-5201b8437a12)

2 Happy
![image](https://github.com/user-attachments/assets/6981c053-7733-46cc-97dc-52e566afcbad)

3 Surprise
![image](https://github.com/user-attachments/assets/53028c70-dcb9-4321-b0ce-5d0569a95fc9)

4 Angry
![image](https://github.com/user-attachments/assets/714888a9-39df-4ac7-a4f4-d44cac289743)

5 Sad


6 Disgust


📜 License
This project is open-source and uses the MIT License.

Emotion-Based-Music-Recommendation

Project Overview

The Emotion-Based Music Suggestor is a Python-based application that captures an image of your face using your webcam, detects your emotional state using the DeepFace module, and recommends YouTube music videos that match your current emotion. The project leverages OpenCV for face detection and DeepFace for emotion analysis. Once the emotion is identified, the application fetches a list of relevant YouTube music videos.

Features

Capture a live image using a webcam via OpenCV.

Detect facial emotions using the DeepFace module.

Suggest relevant YouTube music videos based on the detected emotion.

Provide a simple, interactive UI displaying music suggestions.

Requirements

Before you start, ensure you have the following software and libraries installed:

Prerequisites

Python 3.x

OpenCV (cv2)

DeepFace

Flask (for the web interface)

Requests

Other dependencies mentioned in requirements.txt

Customization

You can customize this project by:

Adjusting the music suggestions for each emotion.

Adding more functionality, like personalized playlists based on user preferences.

Integrating Spotify or other music platforms for enhanced recommendations.

Troubleshooting

Webcam Issues:

Ensure your webcam is functional.

If OpenCV cannot access your webcam, check that no other application is using it and that browser permissions are enabled.

DeepFace Errors:

Ensure you have installed all dependencies of DeepFace (tensorflow, keras, etc.).

If emotion detection fails, check the captured image quality. Poor lighting conditions may affect results.

Future Enhancements

Improved Emotion Detection: Enhance the detection algorithm by training it on a more diverse dataset for better accuracy.

Music Platform Integration: Extend support to Spotify or Apple Music for personalized music recommendations.

Mobile Version: Develop a mobile-friendly version of the app.

# speech_recognition_on_live_call

Speech Emotion Recognition on Live Calls for Cybercrime Police
Overview
This project aims to support cybercrime police by detecting the emotional state of individuals during live phone calls. By analyzing a caller’s voice in real time, the system can identify emotions such as fear, anger, sadness, nervousness, or calmness. This helps law enforcement officers respond quickly to high-risk cases and provide better support to victims.

Features
Real-time speech emotion recognition from live phone calls

Alerts triggered for critical emotions such as fear or distress

Audio pre-processing for enhanced emotion detection

Combined CNN and NLP models using ensemble learning

Dashboard interface for emotion visualization and alerts

System Workflow
Call Reception

Incoming calls are routed through an Asterisk VoIP server using the SIP protocol.

Audio Recording and Processing

Calls are recorded in WAV format and enhanced using FFmpeg for noise reduction and clarity.

Emotion Detection

CNN is used to detect emotions from raw audio signals.

NLP is optionally used to analyze text transcripts (if available).

Predictions are combined using ensemble learning for higher accuracy.

Dashboard Display

Emotions are displayed in real time to the police on a web-based dashboard.

Tech Stack
Call Handling:

Asterisk VoIP Server

SIP Protocol

Audio Processing:

FFmpeg

Librosa

PyDub

Machine Learning & Development:

Python

TensorFlow / PyTorch

Scikit-learn

Google Colab (Model Training)

Web Dashboard:

Flask or Django (Backend)

HTML, CSS, JavaScript (Frontend)

Use Cases
Cybercrime emergency response centers

Women and child safety helplines

Government or private emergency call services

Future Improvements
Multilingual emotion detection

Mobile app integration

Voice-activated emergency triggers

Support for background noise handling

If you have any questions or suggestions, feel free to reach out via email or LinkedIn.

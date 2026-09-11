# DefenSys — Intelligent Personal Safety & Emergency Response System

DefenSys is an interactive prototype for a comprehensive personal safety platform that combines real-time risk assessment, multi-trigger emergency detection, and automated incident response. Built as a responsive web application, it demonstrates how users can activate emergencies through intuitive UI buttons, voice code words, or device shake gestures—while maintaining live location tracking, health vitals monitoring, and audio evidence collection.

## What This Is

**DefenSys** is a single-page web application designed to empower individuals with intelligent, immediate access to emergency response. The system detects distress through multiple channels (SOS button, voice command "AEGIS", triple-shake gesture), calculates real-time risk levels from biometric and behavioral data, and orchestrates a coordinated incident response that includes automated contact notification, live geolocation tracking, and encrypted evidence storage.

## Stack

- **Languages:** HTML5, CSS3, JavaScript (vanilla)
- **Backend:** Firebase v10 (Firestore, Authentication)
- **Key APIs:** Web Speech API, Geolocation API, DeviceMotion API, MediaDevices API

## How to Run

1. **Serve over HTTPS** (required for microphone/camera):
   ```bash
   python3 -m http.server 8000 --bind 127.0.0.1

FEATURES:-
Multi-trigger emergency: SOS button, voice code word, shake gesture
Real-time risk levels: Low → Moderate → High → Critical
Grace period: 5-second countdown to cancel false alarms
Live incident tracking: Location updates every 5 seconds
Audio/video evidence: Automatic recording during active emergency
Wearable integration: Heart rate, steps, movement monitoring
Contact management: Pre-configured emergency contacts
Firestore persistence: All incidents logged with timestamps

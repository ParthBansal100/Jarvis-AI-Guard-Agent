# Jarvis-AI-Guard-Agent
JARVIS: The AI Guard Agent is a fully autonomous, offline security assistant designed to monitor and protect a
 hostel room. It integrates robust face recognition, speech-based command interpretation, and structured
 intruder handling to provide reliable real-time monitoring.
 
 Key highlights:
 
 • Offline Operation: No LLMs or internet dependency. Operates without calls to online models
 like Gemini.
 
 • Autonomous and Edge-Friendly: Runs on standard laptops without GPU acceleration.
 
 • Multi-Modal Security: Combines vision and audio cues for robust monitoring.
 
 • Structured Escalation: Multi-tier intruder handling prevents false alarms and ensures security.
 
 • Logging and Robustness: Snapshot capture, temporary unknown tracking, and thread-safe
 audio handling

# Python libraries you used are:

cv2 (OpenCV) → for face detection, image handling, and snapshot capture.

face_recognition → for generating face embeddings and matching with trusted users.

vosk → for offline speech recognition (wake word and commands).

numpy → for numerical operations, handling embeddings and tracking.

queue → for thread-safe communication between audio and main logic.

threading → for concurrent execution of audio and face recognition.

datetime → for timestamping snapshots and logs.

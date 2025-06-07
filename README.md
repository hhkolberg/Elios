# Elios

# Code Structurte

/Elios-AI-Companion/
├── main.py
├── face_recognition/
│   ├── known_faces/
│   └── recognize.py              # Detect and identify faces
├── voice/
│   ├── wake_word.py              # Wake word detection (e.g., "Hey Picar")
│   ├── tts.py                    # Text-to-speech for responses
│   └── stt.py                    # Speech-to-text for commands
├── gpt/
│   ├── chat.py                   # GPT-powered conversation engine
│   └── family_profiles.json      # Hobby, work, political info, etc.
├── movement/
│   ├── patrol.py                 # Autonomous patrolling logic
│   ├── navigation.py             # Move to charging station or people
│   └── charging.py               # Auto-docking and charging logic
├── sensors/
│   ├── fall_detection.py         # Fall or sudden movement detection
│   ├── medical_alert.py          # Health emergency monitoring
│   └── proximity.py              # Avoid bumping into people/furniture
├── event_handler/
│   ├── greet_on_recognition.py  # Greet family members by name
│   ├── emergency_handler.py     # React to detected falls or calls for help
│   └── idle_behavior.py         # Idle behaviors while waiting for wake word
├── config/
│   └── settings.json             # Configuration options
├── utils/
│   ├── logger.py                 # Logging system
│   └── battery_monitor.py        # Monitor battery level and status
└── assets/
    ├── sounds/                   # Audio feedback (greetings, alerts, etc.)
    └── models/                   # Trained models (face, voice, fall detection)

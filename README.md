# Smart-Voice-Assistant
An AI-powered voice assistant that listens to user commands and performs tasks like opening applications, setting reminders, fetching weather updates, and managing daily activities through voice interaction.

## Features
 Voice recognition using speech input
 
 Text-to-speech response system
 
 Real-time weather updates
 
 Alarm & reminder system
 
 Note-taking functionality
 
 Clipboard reader
 
 Open websites & applications
 
 Tell jokes & quotes
 
 Wikipedia search integration
 
 System performance monitoring
 
 Background listening with wake word
 
 System tray support


## How It Works
The assistant runs in background mode

Waits for the wake word:

 "assistant"
 
Listens for your command

Processes it and responds with voice output

## Technologies Used
Python 

SpeechRecognition

pyttsx3 (Text-to-Speech)

Wikipedia API

OpenWeather API

PyJokes

Pyperclip

Psutil

PyStray (System tray)

## Installation

git clone https://github.com/your-username/voice-assistant.git  
cd voice-assistant  

pip install -r requirements.txt 

python main.py


## Example Commands
"Assistant, open YouTube"

"Assistant, what is the weather in Bangalore"

"Assistant, set alarm for 14:30"

"Assistant, take note buy milk"

"Assistant, tell joke"

"Assistant, search Python programming"

## Project Structure

voice-assistant/

│── main.py

│── assets/

│   └── music/

│── notes/

│── reminders/

│── voice_assistant.log

│── README.md

## Future Improvements
AI-based conversation (ChatGPT integration)

 Mobile app version

 Multi-language support
 
 Smarter command understanding (NLP)

 User authentication

## Challenges

Speech Recognition Accuracy – Difficulty understanding different accents, noise, and unclear speech

PyAudio Installation Issues – Complex setup, especially on Windows systems

Background Listening Stability – Managing continuous listening without crashes or high CPU usage

Wake Word Detection – Ensuring reliable detection without false triggers

API Integration – Handling errors, delays, and invalid responses from external services (weather, Wikipedia)

Thread Management – Running alarms, reminders, and listeners simultaneously without conflicts

System Compatibility – Ensuring the assistant works across different devices and environments

Performance Optimization – Balancing responsiveness with system resource usage

 

 ## Conclusion
The Voice Assistant simplifies everyday tasks by converting voice commands into actions. It enhances productivity, saves time, and provides a hands-free computing experience, making it a powerful beginner-to-intermediate level AI project.

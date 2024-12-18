**Weather Assistant Application**
*Overview*
This project is a voice-controlled weather assistant that provides real-time weather updates based on user input.
It uses the Weather API to fetch weather data and provides information such as temperature, wind speed, wind direction, humidity, and more.
The assistant uses text-to-speech and speech recognition for interaction.
___________________________________________________________________________________________________________________________________________________
**Features**
•	Voice-controlled input for city name and weather queries.
•	Text-to-speech output for user interaction.
•	Real-time weather data retrieval.
•	Flexible responses for various weather-related questions such as:
  o	Wind speed
  o	Temperature
  o	Humidity
  o	Pressure
  o	UV Index
___________________________________________________________________________________________________________________________________________________
**Requirements**

Python Version
  •	Python 3.8 or later
**Dependencies**
The required Python packages are listed in the requirements.txt file. Install them using:
  pip install -r requirements.txt
  
**Key Dependencies**
•	requests: To fetch weather data from the Weather API.
•	SpeechRecognition: For voice input recognition.
•	pywin32: For text-to-speech functionality on Windows.
•	python-dotenv: For managing API keys securely.
•	pyaudio: For microphone access (ensure proper installation for your platform).


# TalkBot
TalkBot is a program through which we can directly interact with the system through microphone.

In the above program , the microphone() in speechrecognition is used to listen the voice. listen() in the recogniser() is used to listen. adjust_for_ambient_noise() in recognizer() is used to remove noice from audio. It is then translated to text using recognize_google() built in recognizer() which requires internet to work. Later the model
learns the answer and returns in the form of text which is then converted to speech using engine.say()(comment: engine = pyttsx3.init() already defined)
Requirements:

----> Python Version - 3.7 is suitable for all packages used in the program

----> packages required - SpeechRecognition, PyAudio, pyttsx3 , chatterbot

----> installation - !pip install SpeechRecognition
                     !pip install PyAudio
                     !pip install pyttsx3
                     !pip install chatterbot==0.8.6

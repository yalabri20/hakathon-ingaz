# Service Monitoring System with Face Emotion Detection

This project demonstrates a service monitoring system using **YOLO (You Only Look Once)** for object detection and **face emotion recognition**. The system analyzes a video for detecting persons entering and exiting a specified area, tracking their time inside the area, and analyzing their facial expressions. A Telegram bot is integrated to send notifications about the events and emotions detected.

## About

This project is a part of a competition, where we achieved 30th place out of 800 participating teams. I, as an AI Developer, played a key role in developing the AI system for object detection and emotion recognition using YOLO and facial recognition models. The system aims to monitor specific areas, analyze emotions, and send notifications via Telegram.

The project showcases our team's ability to integrate multiple AI technologies into a seamless application for real-time use cases.

## Project Details

- **Position:** AI Developer
- **Competition:** Achieved 30th place out of 800 teams
- **Technologies Used:** YOLO (for object detection), Keras (for emotion recognition), OpenCV (for video processing), Telegram API (for notifications)




## Features

- **Object Detection with YOLO**: Detects persons in a video stream using YOLOv8.
- **Face Emotion Detection**: Detects facial emotions using a pre-trained emotion recognition model.
- **Area Monitoring**: Tracks the entry and exit of persons from a defined area in the video and logs the time spent inside the area.
- **Telegram Integration**: Sends notifications to a Telegram bot about person movements and detected emotions.
- **Real-time Video Processing**: Processes video frames in real-time and outputs a new video with annotations.

## Prerequisites

Make sure to have the following installed:

- Python 3.x
- TensorFlow
- OpenCV
- Keras
- Ultralitycs YOLO (YOLOv8)
- Telegram API

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yalabri20/hakathon-ingaz.git
   cd hakathon-ingaz
## Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # For Linux/macOS
.\venv\Scripts\activate  # For Windows

## Install the required dependencies
pip install -r requirements.txt


## Install any other necessary libraries:

pip install nest_asyncio opencv-python keras ultralytics numpy


## Setup Telegram Bot
To use the Telegram bot, you need to create a bot on Telegram:

Go to BotFather on Telegram and create a new bot.

Get the API token provided by BotFather.

Add your chat_id to the script where the bot sends messages.



## Video Demo

Here is a demo video of the prototype:

You can download and watch the prototype video from the repository:

[Prototype Video](./wahaj_prototype_video.mp4)



## Conclusion

This project demonstrates the use of AI technologies, particularly object detection and emotion recognition, to monitor specific areas and assess customer service based on emotional responses. The system combines video analysis with real-time alerts sent via Telegram, showcasing an innovative approach for service evaluation and area monitoring.

With YOLO for object detection, face recognition for emotion analysis, and integration with Telegram for notifications, the project can be further expanded for various real-world applications such as customer service assessment, security, and surveillance.

Feel free to explore and contribute to the project, or adapt it for your use cases. If you have any questions, suggestions, or issues, don’t hesitate to open an issue or pull request.

Thank you for checking out the project!



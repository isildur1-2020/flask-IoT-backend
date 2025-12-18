# Flask IoT Backend

A backend application built with Flask to receive, store, and display data from an Arduino-based IoT device equipped with multiple sensors such as humidity and motion sensors.

This project was created to explore backend development in Python and the integration between IoT hardware and web services.

## Overview
The backend provides endpoints to collect sensor data sent by an Arduino device and allows retrieving or displaying the stored information.

## Features
- Receives data from an Arduino IoT device
- Stores sensor readings such as humidity and motion
- Displays or exposes stored data through a Flask backend
- Simple and lightweight backend architecture

## Tech Stack
- Python
- Flask
- Arduino (IoT data source)

## Project Structure
mi_proyecto/
├── venv/
├── main.py
├── requirements.txt
├── README.md
└── mi_modulo/
    └── __init__.py

## Getting Started

### Create and activate virtual environment
mkdir mi_proyecto
cd mi_proyecto
python -m venv venv
source venv/bin/activate

### Install dependencies
pip install flask
pip freeze > requirements.txt
pip install -r requirements.txt

### Run the application
python main.py

## Purpose
This project was built as a learning exercise to understand how to build a backend service using Flask and how to integrate it with IoT devices such as Arduino.

## Notes
This is a learning-focused project and is not intended to be a production-ready IoT solution.

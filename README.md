# Environmental-Air-quality-monitoring-control-edge-AI
An Edge AI–based environmental air quality monitoring and control system that collects sensor data, processes it locally using machine learning models, and enables real-time analysis and intelligent responses to changing air quality conditions.
an intelligent IoT-based system that monitors environmental air quality in real time using Edge AI and cloud integration. The project combines environmental sensors, embedded systems, machine learning, and cloud dashboards to analyze air quality parameters and enable intelligent control actions with low latency.

The system leverages Blynk for edge-to-cloud communication, Google Colab for training machine learning models, and Wokwi for prototyping and simulation.

 Features

Real-time air quality monitoring using environmental sensors

Edge AI–based local data processing and inference

Cloud visualization and remote control via Blynk

Machine learning model training using Google Colab

Virtual prototyping and testing using Wokwi

Low-latency decision-making with reduced cloud dependency

Scalable design suitable for smart cities and industrial applications

 System Architecture

Sensors Layer
Collects environmental parameters such as gas concentration, temperature, humidity, and air quality indices.

Edge Layer
A microcontroller processes sensor data locally and runs a trained machine learning model for air quality classification or prediction.

Cloud Layer (Blynk)

Real-time data visualization

Alerts and notifications

Remote monitoring and control

AI Model Training (Google Colab)

Data preprocessing

Model training and evaluation

Export of trained model for edge deployment

Simulation & Prototyping (Wokwi)

Virtual testing of hardware and logic

Validation before physical implementation

🛠️ Technologies Used

Programming: Python, C/C++ (Arduino)

Edge AI: Embedded ML inference

Cloud Platform: Blynk

Model Training: Google Colab

Simulation: Wokwi

Hardware (Prototype): ESP32 / Arduino-compatible microcontroller, air quality sensors

 Workflow

Environmental sensors collect air quality data

Edge device preprocesses data

Trained ML model performs local inference

Results are displayed on the Blynk dashboard

Alerts or control actions are triggered when thresholds are exceeded

 Prototype & Simulation

The system is prototyped and tested using Wokwi, allowing simulation of:

Microcontroller behavior

Sensor readings

Edge AI logic

Cloud communication via Blynk

This reduces hardware dependency during early development.

 Machine Learning Model

Model trained using Google Colab

Includes data preprocessing, training, and validation

Optimized model deployed to the edge device for real-time inference

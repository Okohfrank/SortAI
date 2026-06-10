# SortAI
AI-powered waste classification and pneumatic sorting system using MobileNet transfer learning, computer vision, and intelligent process control.

## Overview

The ChemXAI Smart Waste Sorting System is an AI-powered waste characterization and automated sorting platform that combines computer vision, machine learning, and process control engineering to classify and sort waste materials efficiently.

The system uses a fine-tuned MobileNet convolutional neural network (CNN) to classify waste into organic and recyclable categories. Computer vision techniques are further used to estimate physical properties of waste materials, enabling intelligent prediction of pneumatic sorting parameters.

## Features

- Waste classification using MobileNet transfer learning
- Computer vision-based property estimation
- Automated compartment selection
- Air-jet pressure prediction
- Air-jet pulse duration prediction
- Real-time decision support
- Industrial dashboard integration
- Data logging and performance monitoring

## System Architecture

Image Capture

↓

Computer Vision Model

↓

Material Property Estimation
- Material Type
- Density
- Drag Coefficient
- Size
- Mass
- Moisture Content
- Shape Factor

↓

AI Decision Engine
- Compartment Selection
- Pressure Prediction
- Pulse Duration Prediction

↓

Pneumatic Sorting System

↓

Monitoring Dashboard

## Machine Learning Models

### Waste Classification Model

Model: MobileNet (Transfer Learning)

Task:
- Organic Waste Classification
- Recyclable Waste Classification

Performance:
- Validation Accuracy: 96%
- Fine-tuned using 20,000+ augmented images

### Pneumatic Sorting Model

Input Features:
- Material
- Density
- Drag Coefficient
- Size
- Mass
- Moisture Content
- Shape Factor

Predicted Outputs:
- Target Compartment
- Air Pressure
- Pulse Duration

The regression model demonstrates strong agreement between predicted and actual sorting parameters, enabling accurate waste segregation.

## Applications

- Smart recycling facilities
- Automated waste management systems
- Industrial material sorting
- Sustainable waste processing
- Smart city infrastructure

## Future Development

- Multi-class waste classification
- Real-time sensor integration
- IoT-enabled monitoring
- Cloud deployment
- Digital twin implementation
- Industrial-scale deployment

## Tech Stack

- Python
- TensorFlow / Keras
- MobileNet
- OpenCV
- NumPy
- Pandas
- Scikit-Learn

## ChemXAI

This project is developed under ChemXAI, an initiative focused on integrating Artificial Intelligence with Chemical Engineering and industrial systems to create intelligent, scalable, and sustainable engineering solutions.

## Author

Frank Okoh

Chemical Engineering | AI Developer | Founder, ChemXAI

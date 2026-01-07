# AI-Based Diagnostic Tool for Detection of Osteoporosis
 A Multimodal Approach integrating Medical Imaging (CNN) and Clinical Data

📌 Project Overview
Osteoporosis is a progressive skeletal disorder that results in reduced bone density and structural deterioration, significantly increasing the risk of fractures. While DEXA scans are the current gold standard for diagnosis, their high cost and limited availability in rural areas often lead to delayed treatment.

This project, presents a hybrid diagnostic solution that leverages both Deep Learning and Machine Learning to provide a cost-effective, scalable, and accurate tool for early detection.

🏗️ System Architecture
The system utilizes a dual-modality approach to enhance prediction accuracy. It consists of three primary modules integrated into a single user-friendly platform:


Image Classification Module: Analyzes spine and knee X-rays.


Clinical Predictor Module: Evaluates risk from patient-specific metrics.


Severity Grading Module: Specifically assesses the stage of knee osteoporosis.

<img width="1073" height="600" alt="Architecture 1" src="https://github.com/user-attachments/assets/cc963e20-1a78-4f01-9008-d00fb0873ce2" />

🚀 Key Modules & Methodology
1. Convolutional Neural Network (CNN) for Imaging

Purpose: Classify radiographs as Normal, Spine Osteoporosis, or Knee Osteoporosis.


Architecture: Multi-layered CNN designed for medical anomaly recognition and image classification.


Performance: The best-performing model achieved a validation accuracy of ~95%.

2. Machine Learning Clinical Predictor

Algorithm: Gradient Boosting Classifier.


Features Analyzed: Age, gender, lifestyle, hormonal conditions, medical history, and dietary factors.


Performance: Reached a predictive accuracy of 92.01%.

<img width="1243" height="742" alt="Accuracy" src="https://github.com/user-attachments/assets/bc391bad-8069-48a9-ba0d-6299f77f27cc" />

3. Knee Severity Grading System

Scale: Capable of determining disease progression across five distinct stages: Normal, Mild, Moderate, Severe, and Most Severe.

💻 Web Deployment & Interface
The system is deployed using a Flask-based web application.


Secure Access: Features a login system for personalized user experiences.


Actionable Insights: Provides treatment recommendations including exercise routines, dietary plans, and medication suggestions.


Consultation Support: Includes links to medical specialists for further consultation.

<img width="502" height="742" alt="Interface 1" src="https://github.com/user-attachments/assets/8e8c2647-e1c3-47a2-ad03-e5239c7a05ea" />

<img width="532" height="754" alt="Interface 2" src="https://github.com/user-attachments/assets/2305f172-4198-4844-be67-08b4b65d0a94" />

<img width="569" height="848" alt="Interface 3" src="https://github.com/user-attachments/assets/0c5b55a0-f2e3-4f20-b27c-de4d50bb55c7" />

📊 Evaluation & Results

High Precision: The hybrid approach reduces dependency on high-cost imaging.


Validation: The system was tested to ensure reliable performance across both image and clinical datasets.

<img width="787" height="833" alt="Results" src="https://github.com/user-attachments/assets/b6d27a7c-3750-4a57-836c-db5898fa1985" />

🛠️ Tech Stack
Languages: Python 3.x

Deep Learning: CNN (TensorFlow/Keras)

Machine Learning: Gradient Boosting (Scikit-Learn)

Backend: Flask Framework

Hardware: Standard PC requirements for processing and deployment.

Note: This repository contains the project's documentation and architectural design. The full source code is maintained privately for academic evaluation purposes.

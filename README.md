# Plant-Disease-Detection-from-Images

Overview
This project aims to develop a user-friendly Streamlit application that allows users to upload images of plant leaves and predicts the presence and type of plant diseases. Leveraging Convolutional Neural Networks (CNNs), this solution integrates machine learning, computer vision, and intuitive UI design to address real-world agricultural challenges.

Features
Image Upload Interface: Users can upload leaf images directly via a Streamlit-powered web interface.
Disease Detection: Predicts the type of plant disease using a CNN model.
Model Comparison: Evaluates and compares custom CNN models with state-of-the-art pre-trained models (MobileNetV2, EfficientNetB0, and InceptionV3).
Real-World Applications: Assists farmers and gardeners in identifying plant diseases for timely interventions.
Key Components
1. User Interface
Streamlit Application: A web-based UI for uploading images and displaying predictions.
Usability: Clear instructions and feedback for a seamless user experience.
2. Image Preprocessing
Data Preparation: Includes resizing, normalization, and augmentation of leaf images to enhance model accuracy.
Dataset: Utilizes the New Plant Diseases Dataset from Kaggle.
3. Disease Classification
Custom CNN Model: Designed and trained to classify plant diseases.
Pre-Trained Models: Performance compared with MobileNetV2, EfficientNetB0, and InceptionV3.
4. Performance and Optimization
Evaluation Metrics: Assessed using accuracy, precision, recall, and latency.
Optimization: Ensures real-time predictions with minimal delay.
5. Deployment
Accessible Application: Deploys the Streamlit app for end-user interaction.
Testing: Extensive testing to handle diverse image inputs effectively.
Expected Outcomes
Functional Web Application: A Streamlit-based app for disease detection from leaf images.
Performance Report: Analysis of the CNN and pre-trained models, with accuracy metrics.
User Guide: Comprehensive instructions for using the application.
Tools and Technologies
Programming Language: Python
Libraries and Frameworks: Streamlit, OpenCV, TensorFlow/Keras, PyTorch
Dataset: New Plant Diseases Dataset
Deliverables
Streamlit Application: A user-friendly tool for plant disease detection.
Codebase: Documented Python scripts for model training, preprocessing, and deployment.
Trained Models: Fine-tuned CNN and comparisons with pre-trained models.
Project Report: Detailed documentation on implementation, performance, and results.
User Guide: Instructions for setup and usage.

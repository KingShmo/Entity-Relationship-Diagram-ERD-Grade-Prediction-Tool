ERD Grade Prediction Tool
Overview
This project focuses on developing a Machine Learning-powered tool to automatically detect and annotate components in Entity Relationship Diagrams (ERDs), and predict grades for ERD submissions based on a dataset of previously graded submissions. The tool utilizes object detection, optical character recognition (OCR), and grading prediction algorithms to assist with the grading process.

Key Features
ERD Annotation: Utilized Roboflow to annotate and prepare datasets of ERD images.
Object Detection: Leveraged YOLOv8 to detect ERD components, such as entities, relationships, and attributes, with high precision and recall.
OCR Integration: Used EasyOCR to extract text from detected components in the ERD images.
Grade Prediction: Predicted grades for ungraded ERDs by comparing with previously graded ERDs using machine learning techniques.
Cloud-based Model Training: Deployed and trained models using Google Colab for efficient GPU support and easy collaboration.
Tech Stack
Roboflow: Image annotation and dataset preparation.
YOLOv8: Object detection framework used for detecting ERD components.
EasyOCR: Optical Character Recognition library for extracting text from ERD components.
Google Colab: Platform for running machine learning experiments and training models.
Python: Main programming language for implementing object detection, OCR, and grade prediction logic.

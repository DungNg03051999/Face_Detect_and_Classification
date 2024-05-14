# Face_Detect_and_Classification

## This project involves developing a comprehensive pipeline for detecting whether individuals in images are wearing masks, leveraging advanced techniques in data processing, model training, and real-time video analysis.

Data Collection and Preparation:

Data Source: Collect image datasets from various sources on Kaggle.
Data Cleaning: Implement a function to identify and delete duplicate images to ensure data integrity and enhance model performance.
Model Training:

Base Model: Utilize a pre-trained EfficientNet model for its robust feature extraction capabilities.
Custom Layers: Build additional layers on top of the EfficientNet architecture to fine-tune the model specifically for the mask detection task.
Face Alignment:

Alignment Function: Develop a function to align faces in the images. This step is crucial for improving the accuracy of the mask detection model by standardizing the input data.
Mask Detection:

Model Application: Apply the trained model to determine whether the faces in the images are wearing masks or not.
Real-Time Mask Detection with OpenCV:

Video Streaming Integration: Use OpenCV to integrate the mask detection model with video streaming. This allows for real-time detection of mask-wearing conditions on live video feeds.
By following these steps, the project aims to create a reliable and efficient system for mask detection, applicable both to static images and dynamic video streams.

# CV-Based-Attendance-System

This project is an AI-powered face recognition attendance system that uses MTCNN for face detection and FaceNet for generating embeddings, combined with a deep learning classifier for recognizing individuals. It automates attendance marking by capturing images via webcam and logging attendance details into a CSV file.

# 🚀 Features

Face Detection: Uses MTCNN to detect faces from images or webcam feed.

Face Embeddings: Extracts high-dimensional embeddings using FaceNet.

Data Augmentation: Improves robustness with random transformations (rotation, zoom, shift, flip).

Classifier: Trains a neural network model on embeddings to recognize individuals.

Real-Time Capture: Integrates with webcam to capture live images for recognition.

Attendance Logging: Saves predictions (Name, Time, Date, Status) to a CSV file.

# ⚙️ Tech Stack

Python, TensorFlow/Keras, OpenCV, MTCNN, FaceNet, Pandas, Matplotlib

# 📝 Workflow

Load dataset and labels from CSV.

Detect faces using MTCNN and crop them.

Generate embeddings with FaceNet.

Augment data for better generalization.

Train classifier (Dense Neural Network).

Capture live images using webcam.

Recognize faces and mark attendance in CSV.


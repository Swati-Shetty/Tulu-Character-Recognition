##Digitizing Tulu

A deep learning project for handwritten Tulu script recognition using Vision Transformers (ViT) to support cultural preservation and digital accessibility.
________________________________________
##Overview

This project builds an AI system that can recognize handwritten Tulu characters from images.
It uses a Vision Transformer (ViT) model trained on a custom dataset of Tulu and similar Dravidian scripts (Kannada, Telugu, Malayalam).
________________________________________
⚙ Features
•	Vision Transformer-based character recognition
•	Custom dataset of Tulu and Non-Tulu images
•	Preprocessing and augmentation with Roboflow
•	Achieved 98% accuracy
•	Deployed with Gradio and Hugging Face for real-time testing
________________________________________
🧠 Method
1.	Data Preparation
o	Images collected from multiple writers
o	Grayscale conversion, normalization, and resizing to 224×224
o	Augmentations: small rotations, brightness change, and noise addition
2.	Model Training
o	Vision Transformer (ViT-Base/16)
o	Learning rate scheduling with cosine annealing
o	Trained for 50 epochs with early stopping
3.	Evaluation
o	Accuracy: 98%
o	Precision: 98.3%
o	Recall: 96.6%
o	F1-score: 97.1%
________________________________________
🖥 Deployment
•	Model hosted on Hugging Face
•	Interactive Gradio interface for uploading handwritten images and getting predictions instantly
________________________________________
🔮 Future Improvements
•	Expand dataset with more handwriting samples
•	Add word-level OCR (sequence recognition)
•	Create lightweight mobile-friendly models
•	Extend to other South Indian scripts

# Brain Tumor Detection from CT Scans

This project is a deep learning-based image classification system designed to detect brain tumors in CT scan images. It uses image preprocessing techniques and compares multiple models, including Gaussian filtering, Adaptive Median Filtering, and AMF Gradient Boosting. The goal is to assist radiologists by providing accurate and fast classification of CT scans into normal (no tumor) and abnormal (tumor present) categories.

## 🧠 Project Overview

Brain tumors pose serious health risks and require early diagnosis for effective treatment. Manual analysis of CT scans by radiologists can be time-consuming and prone to variability based on expertise. This project provides an automated, GUI-based diagnostic support system to improve reliability and speed in tumor detection.

## 💡 Problem Statement

- Manual CT scan analysis is time-intensive and subject to human error.
- Tumor appearance varies widely across patients, making detection difficult.
- An automated classification model is required for consistent and accurate diagnosis.

## 🧪 Proposed System

- Image preprocessing using:
  - Gaussian Filtering
  - Adaptive Median Filtering (AMF)
- Classification using Gradient Boosting (AMF GB)
- Comparison of accuracy and error rate across methods
- GUI implementation using `Tkinter` for user interaction
- Output: Classification of CT scan as **Normal** or **Abnormal**

## 🔧 Technologies Used

- **Python**
- **OpenCV** for image processing
- **Tkinter** for GUI interface
- **Gradient Boosting Classifier**
- **Matplotlib** for graph plotting

## 📈 Results

- AMF Gradient Boosting achieved the highest classification accuracy.
- Performance visualized through:
  - Accuracy graph
  - Error rate comparison chart

## 📚 References

- [Brain MRI Dataset on Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- [Image Classification using Keras – GeeksforGeeks](https://www.geeksforgeeks.org/python-image-classification-using-keras/)
- [Tkinter GUI Programming Guide – Tutorialsteacher](https://www.tutorialsteacher.com/python/create-gui-using-tkinter-python)
- [Brain Tumor Classification – DataFlair](https://data-flair.training/blogs/brain-tumor-classification-machine-learning/)
- [IRJET Research Paper on Brain Tumor Detection](https://www.irjet.net/archives/V6/i10/IRJET-V6I10148.pdf)
- [Gaussian Filtering – University of Auckland](https://www.cs.auckland.ac.nz)

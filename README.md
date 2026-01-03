# Prototype for Multiclass Stress Detection Using WESAD Motion Data 🧠

## Overview
Full-scale stress detection systems often require large datasets, heavy
computational resources, and long training times.  
This project presents a **lightweight prototype** for **multiclass stress
detection** using a **small subset of the WESAD dataset**, focusing on wearable
motion signals (accelerometer and gyroscope data).

The goal is to demonstrate the feasibility of early-stage stress recognition
using deep learning without relying on full-scale datasets.

---

## Objectives
- Build a fast-training prototype for stress classification
- Explore motion-based physiological signals for stress detection
- Apply feature engineering and data augmentation techniques
- Design and evaluate a deep learning model for multiclass classification

---

## Dataset
- **WESAD (Wearable Stress and Affect Detection) Dataset**
- Subset of motion sensor signals:
  - Accelerometer
  - Gyroscope
- Multiclass stress labels

---

## Technologies Used
- **Python**
- **NumPy, Pandas**
- **Scikit-learn**
- **TensorFlow / Keras**
- **Matplotlib / Seaborn**

---

## Project Structure
The project follows a structured deep learning pipeline:

1. **Library Import & Environment Setup**  
   Preparing the environment and required libraries.

2. **Data Loading**  
   Loading a small subset of WESAD motion sensor data.

3. **Data Preprocessing**  
   Signal cleaning, normalization, and segmentation.

4. **Feature Engineering & Data Augmentation**  
   Extracting meaningful features and enhancing data diversity.

5. **Deep Learning Model Architecture**  
   Designing a neural network suitable for stress classification.

6. **Model Training & Validation**  
   Training the model and validating performance on unseen data.

7. **Comprehensive Model Evaluation**  
   Evaluating performance using multiple metrics and visual analysis.

---

## Key Features
- Multiclass stress classification
- Lightweight and fast-training prototype
- Motion-based physiological signal analysis
- End-to-end deep learning workflow

---

## Results
The prototype demonstrates that meaningful stress classification can be achieved
using a limited subset of wearable motion data, supporting the feasibility of
early-stage stress detection systems.

---

## Future Work
- Integrate physiological signals such as EEG
- Explore advanced deep learning architectures
- Extend the prototype toward real-time stress detection
- Adapt the pipeline for BCI-related applications

---

⭐ This project highlights the potential of combining machine learning and
wearable sensor data for neuro-related and affective computing applications.

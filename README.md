# Automated Menu Digitization System Using OCR and CRNN

Handwritten quantity recognition for restaurant order form digitization.

---

## Project Overview

This project aims to automate the digitization of restaurant order forms by recognizing handwritten quantity fields and converting them into structured digital records.

The project was developed to address real-world challenges in handwritten quantity recognition, where traditional OCR and CNN-based approaches often fail due to small writing areas and incomplete datasets.

---

## Problem Identification

The handwritten quantity fields on restaurant order forms are extremely small and difficult to recognize accurately.

Several challenges were identified:

- Extremely small handwritten quantity fields
- Blank quantity fields
- Two-digit quantities
- Lack of suitable public datasets for real-world restaurant order forms

Traditional OCR techniques and CNN-based models produced significant recognition errors under these conditions.

---

## Sample Images

### Original Restaurant Order Form

![Original Order Form](images/original_order_form.png)

### Order Form with Handwritten Quantities

![Handwritten Order Form](images/handwritten_order_form.png)

---

## Methodology

### Dataset Construction

A custom dataset containing **8,830 handwritten quantity samples** was constructed to address the limitations of existing handwritten digit datasets.

Dataset categories include:

- Blank Fields
- Single-Digit Quantities
- Two-Digit Quantities

### Image Processing

The following preprocessing techniques were applied before model training:

- Image Cropping
- Segmentation
- Noise Reduction
- OpenCV Preprocessing

### Model Development

Two deep learning approaches were evaluated:

1. CNN (Convolutional Neural Network)
2. CRNN (Convolutional Recurrent Neural Network)

The CNN model was used as a baseline for comparison, while the CRNN model was implemented to better capture sequential characteristics in handwritten quantity recognition.

---

## Results

| Model | Accuracy |
|---------|---------|
| CNN | 65.18% |
| CRNN | 98.38% |

The CRNN model significantly outperformed the CNN model, improving recognition accuracy from **65.18%** to **98.38%**.

---

## Technologies

- Python
- OpenCV
- CNN
- CRNN
- Deep Learning
- Computer Vision

---

## Future Work

Potential future improvements include:

- Expanding the dataset with additional handwriting styles
- Improving recognition robustness under challenging image conditions
- Exploring Transformer-based architectures for handwritten text recognition
- Deploying the system as a real-time restaurant digitization solution

---

## Author

**Joe Lee**

Computer Vision and Data Analytics Enthusiast

Chung Yuan Christian University

# Automated Menu Digitization System Using OCR and CRNN

Handwritten Quantity Recognition for Automated Menu Digitization using OCR and CRNN


## Project Overview

This project aims to automate the digitization of restaurant order forms by recognizing handwritten quantity fields and converting them into structured digital records.

The project was developed to address real-world challenges in handwritten quantity recognition, where traditional OCR and CNN-based approaches often fail due to small writing areas and incomplete datasets.

---

## Problem Identification

The handwritten quantity fields on restaurant order forms are extremely small and difficult to recognize accurately.

Several challenges were identified:

- Small handwritten digits
- Blank quantity fields
- Two-digit quantities
- Limited availability of suitable public datasets

Traditional OCR techniques and CNN-based models produced significant recognition errors under these conditions.

---

## Methodology

### Dataset Construction

A custom dataset containing 8,830 handwritten quantity samples was constructed.

Dataset categories include:

- Blank fields
- Single-digit quantities
- Two-digit quantities

### Image Processing

- Image Cropping
- Segmentation
- Noise Reduction
- OpenCV Preprocessing

### Model Development

Two approaches were evaluated:

1. CNN
2. CRNN

---

## Results

| Model | Accuracy |
|---------|---------|
| CNN | 65.18% |
| CRNN | 98.38% |

The CRNN model significantly outperformed the CNN model in handwritten quantity recognition tasks.

---

## Technologies

- Python
- OpenCV
- CRNN
- Deep Learning
- Computer Vision

# pneumonia-detector-gradcam
AI-powered chest X-ray classifier for Pneumonia detection with visual explanations using Grad-CAM. Built with PyTorch and Gradio.
# Pneumonia Detection with Grad-CAM

This project is a deep learning-based diagnostic tool that classifies chest X-ray images into two categories: Normal or Pneumonia. It also provides visual explanations for predictions using Grad-CAM (Gradient-weighted Class Activation Mapping).

## Features

- Pneumonia vs. Normal classification using DenseNet121.
- Visual explanations via Grad-CAM.
- Works well on small datasets.
- Interactive interface using Gradio.

## Dataset

The model was trained using a subset of the Chest X-ray (Pneumonia) dataset available on Kaggle:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Dataset structure:
chest_xray/
├── train/
├── val/
└── test/

## Installation & Usage

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/pneumonia-detector.git
cd pneumonia-detector
pip install -r requirements.txt
python app.py
Model Architecture

The model uses DenseNet121, a convolutional neural network pretrained on ImageNet, and fine-tuned for binary classification (Pneumonia/Normal).
Author

This project was developed by Godswill for a showcase in the 3MTT Advanced AI and Visualization track.

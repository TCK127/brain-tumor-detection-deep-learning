# brain-tumor-detection-deep-learning
Brain tumor segmentation project using Attention U-Net, PyTorch, and MONAI with medical image preprocessing, training, and evaluation on Brats MRI datasets.
# Brain Tumor Segmentation using Attention U-Net

This project focuses on brain tumor segmentation using deep learning techniques with Attention U-Net, PyTorch, and MONAI on MRI image datasets.

## Project Overview

The goal of this project is to improve brain tumor segmentation accuracy using Attention U-Net architecture combined with medical image preprocessing and custom loss functions.

## Technologies Used

- Python
- PyTorch
- MONAI
- NumPy
- Matplotlib
- OpenCV

## Features

- MRI image preprocessing
- Attention U-Net implementation
- Focal Tversky Loss for class imbalance handling
- Model training and evaluation
- Segmentation performance visualization

## Dataset

MRI brain tumor image datasets were used for training and evaluation purposes.

## Results

The model was trained to improve segmentation performance and reduce class imbalance issues in medical imaging tasks.

## How to Run

```bash
pip install -r requirements.txt
python train.py

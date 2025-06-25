# Retinal Hard Exudate Segmentation with MONAI

![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.12%2B-orange)
![MONAI](https://img.shields.io/badge/MONAI-1.1%2B-brightgreen)

This project implements a deep learning pipeline for segmenting hard exudates (pathological lipid deposits) in retinal fundus images. Built with MONAI, it features a residual U-Net architecture trained with medical imaging-specific augmentations and a class-weighted loss function to address foreground sparsity.

# Installation
1. Clone repoository
   git clone https://github.com/yourusername/retinal-exudate-segmentation.git
   cd retinal-exudate-segmentation
3. Install dependencies
   pip install -r requirements.txt

# Dataset Preparation
Folder Structure
/hard_exudate
   ├── images_hard_exudate/  # RGB .jpg fundus images
   └── masks_hard_exudate/   # Binary .png masks

# 🌿 Plant Species Classification System

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.8%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A deep learning-based computer vision system for automatic classification of 18 different plant species from images.

## 📌 Features

- **18 plant species classification** including medicinal, flowering, and fruit-bearing plants
- **Transfer learning** with pretrained CNN architectures (ResNet, etc.)
- **Data augmentation** for improved model generalization
- **Complete training pipeline** with validation and testing
- **High accuracy** (>90% validation accuracy)
- **Modular code structure** for easy extension

## 🌱 Supported Plant Species

| Medicinal Plants | Flowering Plants | Fruit Plants | Other Species |
|------------------|------------------|--------------|---------------|
| Tulsi           | Rose             | Guava        | Pepper        |
| Neem            | Jasmine          | Mango        | Pipal         |
| Mint            |                  | Lemon        | Eucalyptus    |
| Aloevera        |                  | Papaya       | Ashoka        |
| Ashwagandha     |                  | Amla         | Amruthaballi  |
|                 |                  |              | Bamboo        |

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/plant-detection.git
cd plant-detection
2.install dependencies:
```bash
pip install -r requirements.txt```
##🚀 Usage
**Training the Model**
```bash
python src/train.py --config configs/train_config.yaml
**Running Inference**
```bash
python src/predict.py --image_path samples/test_image.jpg
**Jupyter Notebooks**
```bash
jupyter notebook notebooks/
## 📊 Dataset
- Total images: 2,040
- Train/Valid/Test split: 70%/15%/15%
- Image types: High-resolution photos of leaves, flowers, and full plants

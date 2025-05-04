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
```
2.install dependencies:
```bash
pip install -r requirements.txt
```
##🚀 Usage
**Training the Model**
```bash
python src/train.py --config configs/train_config.yaml
```
**Running Inference**
```bash
python src/predict.py --image_path samples/test_image.jpg
```
**Jupyter Notebooks**
```bash
jupyter notebook notebooks/
```
## 📊 Dataset
- Total images: 2,040
- Train/Valid/Test split: 70%/15%/15%
- Image types: High-resolution photos of leaves, flowers, and full plants
  Sample distribution:
```
Rose: 138    Tulsi: 162    Guava: 82     Mango: 126
Lemon: 148   Pepper: 78    Neem: 140     Papaya: 142  
Mint: 145    Pipal: 95     Eucalyptus:45 Jasmine:119
Ashoka:115   Aloevera:122  Amruthaballi:129 Bamboo:92
Ashwagandha:74 Amla:88
```
##📈 Performance
|Model	     | Accuracy|Precision	|Recall	|F1-Score
|ResNet18	   | 92.5%	 |0.93	    |0.92	  |0.92
|EfficientNet|	94.1%	 |0.94	    |0.94	  |0.94
##🏗️ Project Structure
```plant-detection/
├── data/                # Dataset directories
├── configs/             # Configuration files
├── models/              # Saved model weights
├── notebooks/           # Jupyter notebooks
├── src/                 # Source code
│   ├── data/            # Data processing
│   ├── models/          # Model definitions
│   ├── utils/           # Helper functions
│   └── visualization/   # Plotting scripts
├── tests/               # Unit tests
├── requirements.txt     # Dependencies
└── README.md            # This file
```
##🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

##📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

##🙏 Acknowledgments
- Dataset collectors and annotators
- PyTorch development team
- Open-source computer vision community

```
This README includes:

1. Eye-catching header with badges
2. Clear feature list
3. Table of supported species
4. Installation and usage instructions
5. Dataset statistics
6. Performance metrics
7. Project structure visualization
8. Contribution guidelines
9. License information

The formatting uses:
- GitHub-flavored Markdown
- Emojis for visual organization
- Tables for structured data
- Code blocks for commands
- Clear section headers
```
You can copy this directly into your repository's README.md file. The shield badges will automatically pull the current versions when viewed on GitHub.
after the 2. install dependenciesis not in readme format so provide all in readme format
Here's the complete README.md file with all sections properly formatted in GitHub Markdown:

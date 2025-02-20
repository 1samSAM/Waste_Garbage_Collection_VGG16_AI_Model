# Waste Garbage Collection VGG16 AI Model

This project utilizes a deep learning model based on VGG16 to classify waste images into different categories, aiding in automated waste management and recycling.

## 📌 Project Overview

Proper waste segregation is essential for effective recycling and sustainability. This project implements a **Convolutional Neural Network (CNN)** leveraging **VGG16** to classify waste images into predefined categories.

## 📂 Dataset

The model is trained on images categorized into the following waste types:
- 🟤 **Cardboard**  
- 🟢 **Glass**  
- 🔩 **Metal**  
- 📄 **Paper**  
- 🛍️ **Plastic**  
- 🗑 **Trash**  

The dataset ensures diversity in each category to enhance the model's accuracy.

## 🏗 Model Architecture

The project adopts **VGG16** as a feature extractor with modifications:
- **Transfer Learning**: Uses a pre-trained VGG16 model for feature extraction.  
- **Fine-Tuning**: Trains additional layers for waste classification.  
- **Fully Connected Layers**: Added to improve classification performance.  

## 🔧 Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/1samSAM/Waste_Garbage_Collection_VGG16_AI_Model.git
   ```
2.**Navigate to the Project Directory**:
```bash
cd Waste_Garbage_Collection_VGG16_AI_Model
```
3.**Install Dependencies**:
```bash
pip install -r requirements.txt
```
4.**Run the Jupyter Notebook**:
```bash
jupyter notebook Waste_Garbage_Collection.ipynb
```
Follow the notebook instructions to classify waste images.
## 📊 Training Process
Data Augmentation: Rotation, flipping, and scaling applied for better generalization.
Optimizer Used: Adam optimizer for efficient learning.
Evaluation Metrics: Accuracy and loss monitored for training and validation datasets.
## 🎯 Results
The model achieves high accuracy in classifying waste images, making it suitable for automated waste sorting applications.

## 🚀 Future Enhancements
Expand dataset to include more waste types.
Integrate with real-time waste management systems.
Optimize the model further for improved accuracy.
## 📜 License
This project is for educational purposes. Feel free to use and modify it for research and development.
## Acknowledgments
Gratitude to the open-source community and datasets that made this project feasible. Special thanks to the developers of the VGG16 architecture and contributors to waste image datasets.

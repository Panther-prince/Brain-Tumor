# 🧠 MedScan AI - Brain Tumor Detection System

AI-powered brain tumor detection system using VGG16 transfer learning. Web-based Flask application for MRI image analysis with 4-class classification.

## 🏥 Features
- **Medical-grade UI** with professional clinical design
- **4-class tumor detection**: Pituitary, Glioma, Meningioma, No Tumor
- **Real-time analysis** with confidence scoring
- **Drag & drop upload** for MRI images
- **VGG16 transfer learning** for accurate classification

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/Panther-prince/Brain-Tumor.git

# Install dependencies
pip install -r requirements.txt

# Run application
python main.py

📊 Model Architecture

Base Model: VGG16 pre-trained on ImageNet
Transfer Learning: Fine-tuned last 3 layers
Input Size: 128x128x3 RGB images
Accuracy: High-confidence medical imaging classification

🔧 Technologies Used

Python, Flask, TensorFlow/Keras
VGG16 CNN, HTML/CSS/JavaScript
Medical UI design with Bootstrap
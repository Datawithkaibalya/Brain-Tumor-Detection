# 🧠 Brain Tumor Detection using Deep Learning

A deep learning project that classifies brain MRI scans into **Glioma, Meningioma, Pituitary, and No Tumor** using a fine-tuned **ResNet-18** model with PyTorch. Includes a fully functional **Tkinter GUI** for real-time inference.

## 🚀 Features

- **Transfer Learning**: Fine-tuned ResNet-18 pre-trained on ImageNet.
- **4-Class Classification**: Glioma, Meningioma, Pituitary, No Tumor.
- **Interactive GUI**: Upload an MRI image and get instant prediction with confidence score.
- **GPU Acceleration**: CUDA-optimized training and inference.
- **Modular Code**: Separate training and GUI scripts for easy understanding.

## 🛠 Tech Stack

- Python
- PyTorch & Torchvision
- Tkinter (GUI)
- PIL (Image Processing)
- NumPy, Matplotlib

## 📁 Project Structure

Brain-Tumor-Detection/
├── src/
│   ├── train.py          # Model training script
│   └── gui.py            # Tkinter GUI application
├── requirements.txt      # Dependencies
├── .gitignore
└── README.md

## ⚙️ How to Run

1. Clone the repository:
   git clone https://github.com/Datawithkaibalya/Brain-Tumor-Detection.git

2. Install dependencies:
   pip install -r requirements.txt

3. Train the model:
   python src/train.py

4. Run the GUI:
   python src/gui.py

## 📊 Dataset

Brain Tumor MRI Dataset from Kaggle.

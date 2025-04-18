# Facial Emotion Recognition (AITHON '22 🧠🎭)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Repo Size](https://img.shields.io/github/repo-size/yourusername/facial-emotion-recognition)](https://github.com/yourusername/facial-emotion-recognition)
[![Contributors](https://img.shields.io/github/contributors/yourusername/facial-emotion-recognition)](https://github.com/yourusername/facial-emotion-recognition)

A deep learning-based system to recognize human facial emotions using a custom image dataset, built with Convolutional Neural Networks (CNN). Developed as part of **AITHON '22**, a hackathon conducted by IEEE Student Branch, College of Engineering, Karunagappally.

## 📌 Features

- Custom dataset creation with 7 emotions
- Data preprocessing and augmentation
- CNN-based emotion classification
- Training & test visualizations (accuracy, loss, confusion matrix)
- Sample predictions
- Modular, scalable project structure

## 🚀 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, OpenCV, Matplotlib, Seaborn
- Google Colab
- Jupyter Notebook

## 📂 Dataset Details

- Emotions: Angry, Sad, Happy, Calm, Laugh, Disgusting, Sarcasm
- Custom captured facial images
- Train/Test Split: 80% / 20%
- Augmentations: Normalization, Horizontal Flip, Shear
- Format: Image folders structured by emotion class

## ⚙️ Setup Instructions

```bash
git clone https://github.com/Artsuntkurian/facial-emotion-recognition.git
cd facial-emotion-recognition
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

## 🧪 Usage Instructions

1. Open `notebooks/Facial_Emotion_Recognition_project.ipynb`
2. Run notebook step by step:
   - Dataset loading
   - Preprocessing
   - CNN model definition
   - Training & evaluation
3. View outputs in `assets/plots/` or `assets/samples/`

## 🤝 Contribution Guidelines

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for instructions.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📚 Acknowledgements

- IEEE SB, College of Engineering Karunagappally for organizing AITHON '22
- Our team members for dataset creation and testing

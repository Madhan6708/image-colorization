# 🖌️ Basic Image Colorization using Deep Learning

This project implements a simple image colorization model using deep learning. A grayscale input image is colorized using a U-Net-based convolutional neural network (CNN) trained on the L*a*b* color space.

---

## 📌 Project Description

This notebook demonstrates the use of a basic U-Net architecture in TensorFlow/Keras to colorize grayscale images. The model takes the L-channel (lightness) from the L*a*b* color space as input and predicts the a and b color channels to generate the final color image.

---

## ▶️ How to Run the Notebook

1. Open the `Basic_Colorization.ipynb` file in Google Colab or Jupyter Notebook.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
## 📊 Accuracy Metrics
Metric	Value
Precision	~0.00043
Recall	~0.0006
SSIM	~0.72
PSNR	~25+ dB
## 📦 Model Weights (Google Drive)
https://drive.google.com/file/d/1DNBSbXbBZC94zmSjWTG1qPj2tITM88NO/view?usp=drive_link

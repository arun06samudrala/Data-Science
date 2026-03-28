# U-Net Image Segmentation (Cityscapes)

## 🚀 Overview
This project implements a **U-Net convolutional neural network** for **semantic image segmentation** on the Cityscapes dataset.

The model learns to classify each pixel in an image into meaningful categories such as roads, buildings, vehicles, and pedestrians.

---

## 🧠 Problem Statement
Traditional image classification predicts a single label per image.  
In contrast, **semantic segmentation** requires assigning a label to every pixel.

This project aims to:
- Build a U-Net model from scratch
- Train it on real-world urban scene data
- Generate pixel-wise segmentation masks

---

## 🏗️ Model Architecture
- Encoder-decoder structure (U-Net)
- Skip connections for spatial information retention
- Convolution + MaxPooling (downsampling)
- Transposed Convolutions (upsampling)

---

## 📊 Dataset
- **Dataset:** Cityscapes
- High-resolution urban street images
- Fine-grained pixel-level annotations

⚠️ Dataset is not included in this repository due to size.  
Download from: https://www.cityscapes-dataset.com/

---

## ⚙️ Training Setup
- Framework: TensorFlow / Keras
- Input size: 96 × 128 (resized)
- Loss: Sparse Categorical Crossentropy
- Optimizer: Adam
- Training images: ~1000
- Validation split: 80 / 20

---

## 📈 Results
- Training Accuracy: ~83%
- Validation Accuracy: ~75%
- Model shows strong learning and generalization


---

## 🔧 Key Learnings
- Importance of proper data preprocessing in segmentation
- Handling image-mask alignment
- Effect of resolution on segmentation quality
- Benefits of validation split to monitor overfitting

---

## 🚧 Future Improvements
- Train on full dataset
- Increase input resolution (e.g., 128×256 or higher)
- Add data augmentation
- Use pretrained encoders (ResNet, EfficientNet)
- Evaluate using IoU / Dice Score

---

## 📁 Project Structure

projects/
14_unet_segmentation/
├── notebook.ipynb
├── data/ (ignored in git)
└── README.md


---

## 💻 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/arun06samudrala/Data-Science.git
cd Data-Science

2. Create virtual environment

python3 -m venv .venv
source .venv/bin/activate
pip install tensorflow numpy pandas matplotlib imageio


3. Download dataset

Download and extract Cityscapes dataset into:

projects/14_unet_segmentation/data/

4. Run notebook

Open in VS Code or Jupyter and run all cells.


🙌 Acknowledgements
	•	Cityscapes Dataset
	•	U-Net architecture paper
# NeuralBlack: Advanced Brain Tumor Detection System

> **Developed by Srishti Bisht • June 2025**  
> Pioneering an end-to-end AI solution—from data preprocessing to real-time diagnosis—to empower radiologists with quick, accurate insights.

---

## 🌟 Synopsis
NeuralBlack applies deep transfer learning and robust data augmentation to classify brain MRI scans into four classes:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

**Key Outcomes:**
- **99.3% overall accuracy** on held-out test data  
- Production-ready **Flask API** for instantaneous image inference  
- Fully documented **Jupyter Notebook** pipeline covering EDA, training, and evaluation  

---

## 📦 Core Components

| Module                         | Description                                                      |
|--------------------------------|------------------------------------------------------------------|
| `notebooks/`                   | Interactive analysis and model-building (`training_pipeline.ipynb`) |
| `scripts/train.py`             | Data loading, augmentation, and training routines                |
| `scripts/inference.py`         | CLI tool for single-image predictions                            |
| `scripts/app.py`               | Flask server exposing `/predict` endpoint                        |
| `models/bt_resnet50_model.pt`  | Pretrained model weights                                         |
| `test_images/`                 | Sample MRI scans for quick tests                                 |
| `Dockerfile`                   | Containerization configuration                                   |

---

## 🔧 Installation & Quickstart

1. **Clone & enter project**  
   ```bash
   git clone https://github.com/Srishtiaideveloper/desktop-tutorial.git
   cd desktop-tutorial


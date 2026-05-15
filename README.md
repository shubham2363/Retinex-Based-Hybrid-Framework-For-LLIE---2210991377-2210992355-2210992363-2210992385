
# Retinex-Based Hybrid Framework For Low-Light Image Enhancement

A hybrid low-light image enhancement system that combines **Retinex theory**, **Transformer-based feature extraction**, and **Diffusion refinement** to achieve both high-quality enhancement and real-time processing.

The framework provides two operational modes:

- **Backend AI Mode** → High-quality enhancement using deep learning
- **Frontend Default Mode** → Fast browser-based enhancement for real-time applications

---

# 📌 Authors

- Aryan Chhabra  
- Shreyansh Maheshwari  
- Shubham Dhoni  
- Sitanshu Gupta  

### Paper Details

- **Paper ID:** 1659
- **Status:** Submitted

### Guide

**Dr. Shikha Tuteja**

Chitkara University Institute of Engineering and Technology, Punjab, India.

---

# 📖 Abstract

Low-light image enhancement is an important task in computer vision and image processing. Traditional enhancement techniques often introduce artifacts, lose fine details, or fail in extremely dark scenes.

This project proposes a **Retinex-Based Hybrid Framework** that integrates:

- Transformer architectures
- Retinex-inspired decomposition
- Diffusion refinement
- Real-time browser enhancement techniques

The system is designed to balance:

- Image Quality
- Processing Speed
- Detail Preservation
- Real-time Usability

The proposed Backend AI Mode achieved:

- **PSNR:** 18.76 dB
- **SSIM:** 0.72

on the LOL dataset, outperforming several traditional and learning-based approaches.

---

# 🚀 Features

## Backend AI Mode

- Transformer-based feature extraction
- Retinex illumination-reflectance decomposition
- Diffusion refinement network
- Adaptive histogram equalization
- Edge-aware sharpening
- Super-resolution support

## Frontend Default Mode

- Real-time browser enhancement
- WebGL & Canvas API support
- Fast preview generation
- Lightweight processing pipeline
- Adjustable enhancement controls

---

# 🧠 System Architecture

```text
Input Image
     │
     ├── Frontend Default Mode
     │      ├── White Balance
     │      ├── Multi-scale Retinex
     │      ├── Dehazing
     │      ├── Noise Reduction
     │      └── Edge Enhancement
     │
     └── Backend AI Mode
            ├── Transformer Feature Extraction
            ├── Retinex Decomposition
            ├── Diffusion Refinement
            └── Post-processing
```

---

# 🛠 Tech Stack

## Backend

- Python
- Flask
- PyTorch
- OpenCV
- CUDA

## Frontend

- HTML5
- CSS3
- JavaScript
- WebGL
- Canvas API

---

---

# 📊 Experimental Results

## Performance Comparison on LOL Dataset

| Method | PSNR | SSIM |
|--------|------|------|
| HE | 15.24 | 0.58 |
| CLAHE | 16.35 | 0.62 |
| MSRCR | 16.97 | 0.65 |
| LIME | 17.32 | 0.67 |
| RetinexNet | 17.56 | 0.68 |
| EnlightenGAN | 17.83 | 0.69 |
| Frontend Default | 17.92 | 0.68 |
| **Our Backend AI** | **18.76** | **0.72** |

---

# 📈 Ablation Study

| Component | PSNR |
|-----------|------|
| Base Transformer | 17.45 |
| + Retinex Decomposition | 18.12 |
| + Diffusion Refinement | 18.54 |
| + Post-processing | 18.76 |

---

# 🖼 Dataset

The model was trained on the **LOL (Low-Light) Dataset** containing paired low-light and normal-light images.

Dataset includes:

- Indoor scenes
- Outdoor scenes
- Mixed lighting conditions

---

# 📌 Applications

- Night Photography
- Surveillance Systems
- Mobile Camera Enhancement
- Medical Imaging
- Autonomous Vehicles
- Low-light Video Processing

---

# 🔍 Future Work

- Larger and more diverse datasets
- Video enhancement support
- Noise-aware enhancement
- ISP pipeline integration
- Lightweight model compression
- Mobile deployment optimization

---

# 📚 Research Paper

Included in this repository:

```text
Research_Paper.pdf
```

Paper Title:

**Retinex-Based Hybrid Framework For Low-Light Image Enhancement**

---

# 🤝 Acknowledgement

We thank the creators of the LOL dataset for providing training and evaluation resources.

---

# 📜 License

This project is intended for academic and research purposes.

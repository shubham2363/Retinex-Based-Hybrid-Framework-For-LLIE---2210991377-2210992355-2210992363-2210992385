Retinex-Based Hybrid Framework For Low-Light Image Enhancement

A hybrid low-light image enhancement system that combines Retinex theory, Transformer-based feature extraction, and Diffusion refinement to achieve both high-quality enhancement and real-time processing. The framework provides two operational modes:

Backend AI Mode → High-quality enhancement using deep learning.
Frontend Default Mode → Fast browser-based enhancement for real-time applications.
📌 Authors
Aryan Chhabra
Shreyansh Maheshwari
Shubham Dhoni
Sitanshu Gupta

Guide: Dr. Shikha Tuteja

Chitkara University Institute of Engineering and Technology, Punjab, India.

📖 Abstract

Low-light image enhancement is an important task in computer vision and image processing. Traditional enhancement techniques often introduce artifacts, lose fine details, or fail in extremely dark scenes.

This project proposes a Retinex-Based Hybrid Framework that integrates:

Transformer architectures
Retinex-inspired decomposition
Diffusion refinement
Real-time browser enhancement techniques

The system is designed to balance:

Image Quality
Processing Speed
Detail Preservation
Real-time Usability

The proposed Backend AI Mode achieved:

PSNR: 18.76 dB
SSIM: 0.72

on the LOL dataset, outperforming several traditional and learning-based approaches.

🚀 Features
Backend AI Mode

✔ Transformer-based feature extraction
✔ Retinex illumination-reflectance decomposition
✔ Diffusion refinement network
✔ Adaptive histogram equalization
✔ Edge-aware sharpening
✔ Super-resolution support

Frontend Default Mode

✔ Real-time browser enhancement
✔ WebGL & Canvas API support
✔ Fast preview generation
✔ Lightweight processing pipeline
✔ Adjustable enhancement controls


🧠 System Architecture

The framework contains two complementary pipelines:

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

🛠 Tech Stack
Backend
Python
Flask
PyTorch
OpenCV
CUDA
Frontend
HTML5
CSS3
JavaScript
WebGL
Canvas API

📈 Ablation Study
Component	PSNR
Base Transformer	17.45
+ Retinex Decomposition	18.12
+ Diffusion Refinement	18.54
+ Post-processing	18.76

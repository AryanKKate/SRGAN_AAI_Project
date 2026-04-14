# 🚀 Hybrid Face & Scene Super-Resolution using GANs

## 📌 Overview  
This project implements a **hybrid super-resolution system** that enhances low-resolution images using **Generative Adversarial Networks (GANs)**. It combines **global scene enhancement** with **face-specific refinement** to generate visually realistic high-resolution outputs.

---

## 🧠 Key Idea  
- **Scene Model** enhances overall image structure  
- **Face Model** improves facial details  
- **RetinaFace** detects faces in the image  
- **Adaptive Blending** merges outputs seamlessly  

---

## ⚙️ Tech Stack  
- PyTorch  
- SRGAN (Generator + Discriminator)  
- RetinaFace  
- OpenCV  
- NumPy / Matplotlib  
- Evaluation: PSNR, SSIM  

---

## 🏗️ Pipeline  
Low-Resolution Image
↓
Scene SR Model (global enhancement)
↓
Face Detection (RetinaFace)
↓
Face SR Model (local enhancement)
↓
Adaptive Blending
↓
High-Resolution Output


---

## 📊 Results  
- Produces sharper and more realistic images  
- Improves facial details compared to standard SRGAN  
- Evaluated using:
  - PSNR
  - SSIM  

---

## 🚀 Features  
- Hybrid GAN-based architecture  
- Face-aware super-resolution  
- Adaptive blending (artifact reduction)  
- Separate training pipelines for face and scene models  
- GPU-optimized training with mixed precision (AMP)  

---

## 📂 Datasets  
- CelebA → Face enhancement  
- DIV2K → Scene enhancement  



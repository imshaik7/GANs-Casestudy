# Generative Modelling Using GANs Across Multiple Domains

## 📌 Overview

This project is an MSc-level case study exploring the performance of **Generative Adversarial Networks (GANs)** across multiple data domains. The study investigates how GAN behaviour varies depending on data structure, model architecture, and evaluation strategy.

The project covers four key domains:

- Synthetic 2D data (sine wave & spiral)
- Medical imaging (BloodMNIST)
- Tabular cybersecurity data (CICIDS 2017)
- Creative sketch generation (QuickDraw)

The primary objective is not only to implement GANs but to **critically evaluate their strengths and limitations across different data representations**.

---

## 🧠 Key Concepts

- Generative Adversarial Networks (GANs)
- DCGAN (Deep Convolutional GAN)
- Latent space learning
- Adversarial training dynamics
- Cross-domain evaluation

---

## 📂 Project Structure
Generative-Modelling-Case-Study/
│
├── notebooks/
│ ├── Part1_Synthetic_GAN.ipynb
│ ├── Part2_1_BloodMNIST.ipynb
│ ├── Part2_2_CICIDS.ipynb
│ ├── Part2_3_QuickDraw.ipynb
│
├── data/
│ ├── BloodMNIST/
│ ├── CICIDS/
│ ├── QuickDraw/
│
├── outputs/
│ ├── figures/
│ ├── tables/
│
├── report/
│ └── Generative_modelling_casestudy_IS.pdf
│
└── README.md

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (PCA)
- Google Colab (GPU training)

---

## 🔬 Experiments

### 🔹 Part 1 — Synthetic Data GAN
- Implemented GAN from scratch
- Learned sine-wave distribution (successful)
- Struggled with spiral distribution (complex geometry)
- Explored architectural improvements

---

### 🔹 Part 2.1 — BloodMNIST (Medical Imaging)
- DCGAN for image generation
- Captured structure and colour patterns
- Limitations:
  - blurry outputs
  - lack of fine biological detail

---

### 🔹 Part 2.2 — CICIDS (Tabular Data)
- GAN for feature vector generation
- PCA used for evaluation
- Findings:
  - captures global trends
  - fails to model feature dependencies effectively

---

### 🔹 Part 2.3 — QuickDraw (Creative AI)
- DCGAN for sketch generation
- Learns stroke patterns
- Struggles with:
  - semantic consistency
  - recognisable shapes

---

## 📊 Key Findings

- GAN performance is **highly data-dependent**
- Works best for:
  - structured image data
- Struggles with:
  - tabular relationships
  - abstract representations
- Evaluation requires:
  - visual + statistical methods (not just metrics)

---

## ⚠️ Limitations

- Training instability
- Mode collapse
- Difficulty in evaluation across domains
- Lack of domain-specific validation

---

## 🚀 Future Work

- Conditional GANs (cGAN)
- Wasserstein GAN (WGAN) for stability
- Tabular-specific GAN architectures
- Higher-resolution datasets

---

## 📄 Report

Full report available here:

 `Generative_modelling_casestudy_IS.pdf`

---

## 🔗 References

- Goodfellow, I. et al. (2014) — Generative Adversarial Networks  
- Radford, A. et al. (2015) — DCGAN  
- MedMNIST Dataset — https://medmnist.com/  
- CICIDS 2017 — Kaggle  
- QuickDraw Dataset — https://github.com/googlecreativelab/quickdraw-dataset  

---

## 👤 Author

**Imthiyaz Shaik**  
MSc Data Science  
University of Hertfordshire

---

## ⭐ Notes

This project was developed as part of an MSc coursework assignment and demonstrates both **implementation and critical evaluation of generative models across domains**.

```

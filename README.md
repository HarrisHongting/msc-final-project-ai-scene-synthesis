# Advancing Language-driven Scene Synthesis with AI Text Prompt Generation

## 📌 Project Overview

This repository contains the implementation and report of my MSc Final Project at **University College London (UCL)**.
The project enhances **Language-driven Scene Synthesis using Multi-conditional Diffusion Models (LSDM)** by introducing **AI-generated text prompts** via the **Groq AI API**.

By generating diverse language inputs at multiple temperature settings and integrating them into training, the model achieves **improved generalisation** and **higher accuracy** in 3D scene synthesis tasks.

---

## 🛠 Tech Stack

* **Programming:** Python, PyTorch
* **Frameworks & APIs:** Groq AI API, Diffusion Models
* **Systems & Tools:** Ubuntu 24.04, Docker, GitHub Actions
* **Data:** PRO-teXt dataset

---

## 🚀 Key Contributions

* Developed a **distributed inference pipeline** integrating Groq AI API for text prompt augmentation.
* Improved **scene generation accuracy** with multi-prompt training (+20% improvement in Chamfer Distance and F1 Score).
* Demonstrated the effectiveness of **diverse AI-generated prompts** for enhancing semantic and spatial consistency in LSDM.
* Delivered a **scalable and reproducible training pipeline** using PyTorch and Docker.

---

## 📊 Results

| Metric                | Original LSDM | Enhanced Model |
| --------------------- | ------------- | -------------- |
| Chamfer Distance ↓    | 0.8037        | 0.5223         |
| Earth Mover’s Dist. ↓ | 0.7152        | 0.4545         |
| F1 Score ↑            | 0.5505        | 0.7375         |
| Category Accuracy ↑   | 85%           | 100%           |

**Visual Comparison:**
*(Insert figures or screenshots from your report here, e.g. single-object vs multi-object scene generation results.)*

---

## 📑 Report

The full MSc dissertation report is available under:

* [`/report/final_report.pdf`](./report/final_report.pdf)

Citation:

> Liu, H. (2024). *Advancing Language-driven Scene Synthesis with AI Text Prompt Generation*. MSc Dissertation, University College London.

---

## 🔮 Future Work

* Extend multi-modal input integration (speech, video).
* Optimise training efficiency and GPU utilisation.
* Real-time deployment in **VR/AR** and **robotics simulations**.

---

## 📬 Contact

* **Author:** Hongting (Harris) Liu
* **Email:** [hliu.applications@gmail.com](mailto:hliu.applications@gmail.com)
* **Website:** [harrisliu.com](https://www.harrisliu.com)
* **LinkedIn:** [linkedin.com/in/harris-liu-19102000hl](https://www.linkedin.com/in/harris-liu-19102000hl)

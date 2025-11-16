# 🚀 GraphAI – Real-Time Graphene Layer Segmentation  
### Powered by **YOLO11-seg · Flask API · Next.js Frontend**

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-YOLO11--seg-blue?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Framework-Flask-red?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/Frontend-Next.js-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Graphene%202D%20Materials-Research-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Image%20Segmentation-AI-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Paper-ICoBITS%202025-purple?style=flat-square" />
</p>

---

## 📌 Overview

**GraphAI** is a deep learning–powered application that performs **real-time segmentation of graphene layers** from optical microscope images using the **YOLO11-seg** architecture.

The system integrates:

- **Next.js** → Frontend UI  
- **Flask API** → Model inference  
- **YOLO11-seg** → Segmentation engine  

## 🧠 Model Summary

Across three identical experiment runs, YOLO11-seg achieved:

| Metric | Result |
|--------|--------|
| **mAP50** | 0.88 – 0.93 |
| **mAP50-95** | 0.65 – 0.72 |
| **Precision** | 0.80 – 0.90 |
| **Recall** | 0.78 – 0.86 |

These metrics indicate **strong convergence**, **high stability**, and **excellent performance** for real-time use.

## 🗂️ Dataset

| Property | Details |
|---------|---------|
| **Total Images** | 1,775 |
| **Source** | Optical microscope |
| **Classes** | 1-Layer, 2-Layer, 3-Layer, 4-Layer |
| **Purpose** | Graphene thickness segmentation |

📥 **Dataset (Zenodo):**  
<p>
  <a href="https://zenodo.org/records/8042835" target="_blank">
    <img src="https://img.shields.io/badge/Download%20Dataset-Zenodo-blue?style=for-the-badge&logo=zenodo&logoColor=white" />
  </a>
</p>

## 🚀 Running the Project Locally

```bash
git clone [https://github.com/junervin12/graph-ai](https://github.com/junervin12/graph-ai)
cd graph-ai
```

## 👥 Contributors

<p> <img src="https://img.shields.io/badge/Nazwa%20Hilda%20Syafira-Contributor-purple?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/Salwa%20Asysyifa%20Khoerunisa-Contributor-blue?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/Desvita%20Nursayla%20Putri%20Cantika-Contributor-green?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/Junervin-Supervisor-black?style=for-the-badge" /> </p>

## 🏫 Affiliation
This project is developed under the Agroindustrial Engineering Study Program, Universitas Linggabuana PGRI Sukabumi, as part of a student-led research initiative on 2D materials and deep learning.

## 📚 Citation

If you use GraphAI for research, please cite:
```bash
Syafira, N. H., Khoerunisa, S. A., Cantika, D. N. P., & Junervin. (2025).
Real-Time Segmentation of Graphene Layers Using YOLO11-seg.
International Conference on Business, Innovation, Technology & Science (ICoBITS).
```

# XAI-AV-Misclassifications
Explaining object detection failures in autonomous vehicles using Grad-CAM and SHAP


---

## 🛠️ Technologies Used

- 🧠 YOLOv11 (Custom Object Detection Model)
- 🔍 Grad-CAM (Visual Explanations for CNNs)
- 🧮 SHAP (SHapley Additive exPlanations)
- 📊 KITTI Dataset (Autonomous Vehicle Benchmark)
- 📓 Jupyter Notebooks
- 🐍 Python, NumPy, OpenCV, PyTorch, Matplotlib

---

## 🚘 Problem Statement

Modern object detection models in AVs still face challenges with:
- **Misclassifying pedestrians, cyclists, and static objects**
- **Failing in occluded or low-contrast environments**

This project aims to:
- **Detect** and **log misclassifications**
- **Explain** the failure using interpretable visualizations

---

## 💡 Key Insights

- **Grad-CAM** shows where the model "looks" before making decisions.
- **SHAP** explains how different image regions impact the final prediction.
- Misclassifications often arise from:
  - Background clutter
  - Object occlusion
  - Lighting conditions

---



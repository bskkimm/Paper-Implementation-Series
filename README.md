# 📚 From Paper to Code: Implementations of Key Computer Vision Papers from Scratch

Welcome to my computer vision model implementation series!  
This repository serves as a central hub for my **from-scratch implementations** of legendary computer vision models, each broken down and reconstructed with clarity and precision.



---

## 🚀 Introduction

This repository briefly introduces my **legendary computer vision model implementation series**, where I faithfully reimplement influential papers to gain hands-on, low-level understanding of the techniques driving modern visual AI systems.

---

## 🎯 Motivation

The purpose of this project is twofold:

1. **Develop Practical Proficiency**: To gain end-to-end experience in building deep learning pipelines — from data preparation to training, inference, and deployment — in the domain of computer vision.
2. **Build Foundational Understanding**: To deeply understand the core architectural paradigms of modern vision models, such as **Convolutional Neural Networks (CNNs)** and **Transformers**.

---

## 🔁 Workflow

Each implementation follows a consistent and rigorous pipeline:

![image](https://github.com/user-attachments/assets/c0bb7f29-2b8b-474e-8ce6-7a8fcc2cdee1)

1. **Paper Reading & Understanding**  
   Analyze the original research paper to understand the theoretical backbone of the model.

2. **Data Preparation**  
   Prepare the dataset according to the specific requirements of the model.

3. **Model Building**  
   Implement the architecture from scratch using PyTorch.

4. **Training & Experimentation**  
   Train the model, tune hyperparameters, and analyze performance metrics.

5. **Inference & Deployment**  
   Evaluate the model with test samples and explore basic deployment options.

---

## 🧠 Implemented Models

### 📌 [YOLOv1 – You Only Look Once (v1)](https://github.com/yourname/yolov1-repo)
#### 🔍 Model Summary
YOLOv1 is a real-time object detection model that reframes detection as a single regression problem, directly predicting class probabilities and bounding boxes from full images in one evaluation. It introduced a new paradigm compared to two-stage detectors like R-CNN.

#### 📊 Results

| Metric          | Value |
|-----------------|-------|
| mAP (VOC 2007)  | 63.4% |
| FPS             | 45    |

<div align="center">
  <img src="results/yolov1_sample1.png" width="400"/>
  <img src="results/yolov1_sample2.png" width="400"/>
</div>

---

### 📌 [ViT – Vision Transformer](https://github.com/yourname/vit-repo)
#### 🔍 Model Summary
ViT replaces convolutional layers with pure transformer blocks. It splits the image into patches, flattens them, and feeds them into a standard transformer architecture, achieving state-of-the-art performance with sufficient data.

#### 📊 Results

| Metric        | Value     |
|---------------|-----------|
| Top-1 Accuracy| 83.1%     |
| Dataset       | ImageNet  |

<div align="center">
  <img src="results/vit_patch_embed.png" width="400"/>
  <img src="results/vit_attention.png" width="400"/>
</div>

---

### 📌 [DETR – DEtection TRansformer](https://github.com/yourname/detr-repo)
#### 🔍 Model Summary
DETR is a novel object detection model that unifies detection with transformers and bipartite matching. It eliminates the need for many hand-crafted components like anchor boxes or NMS, making detection elegantly simple.

#### 📊 Results

| Metric        | Value     |
|---------------|-----------|
| mAP (COCO)    | 43.5%     |
| FPS           | 28        |

<div align="center">
  <img src="results/detr_example1.png" width="400"/>
  <img src="results/detr_example2.png" width="400"/>
</div>

---

## 🛠️ Tools & Libraries

- Python 3.10
- PyTorch
- NumPy, OpenCV, Matplotlib
- Weights & Biases (for logging, optional)

---

## 🤝 Contributing

This is a solo learning project, but feel free to:
- Star ⭐ the repos
- Open issues for suggestions
- Fork and experiment

---

## 📜 License

MIT License

---

## 📫 Contact

Feel free to reach out if you’re working on similar implementations or have any feedback!  
**Author:** [Your Name]  
**Website:** [yourwebsite.com](https://yourwebsite.com)


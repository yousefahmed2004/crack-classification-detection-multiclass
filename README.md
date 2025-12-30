# Crack Classification & Detection (Multiclass) using Mask R-CNN

This project implements a state-of-the-art **Instance Segmentation** model to detect and classify structural defects such as cracks, spalling, and rust. Built on the **Detectron2** framework, the model provides pixel-level masks to accurately measure the extent of structural damage.

---

## 🔍 Model Detection Results
The following images demonstrate the model's ability to identify and segment multiple defect classes with high confidence scores.

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234338.png" width="90%" alt="Detailed Crack Detection" />
</p>

### 🖼️ Detection Gallery
<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234251.png" width="48%" alt="Detection Sample 1" />
  <img src="screenshots/Screenshot%202025-12-30%20234257.png" width="48%" alt="Detection Sample 2" />
</p>

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234307.png" width="48%" alt="Detection Sample 3" />
  <img src="screenshots/Screenshot%202025-12-30%20234323.png" width="48%" alt="Detection Sample 4" />
</p>

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234331.png" width="90%" alt="Detection Sample 5" />
</p>

---

## 🧠 Model Architecture
The system utilizes **Mask R-CNN** with a **ResNet-50-FPN** backbone. 



**Technical Details:**
* **Architecture:** Mask R-CNN (Instance Segmentation)
* **Framework:** Detectron2
* **Training Iterations:** 30,000 steps
* **Dataset:** dacl10k (Deep Analysis of Bridge Construction Defects)

---

## 📂 Resources & Downloads
* **📦 Trained Model (.pth):** [Download from Google Drive](https://drive.google.com/file/d/1A77ToX419hQUbzy2bng6RrGbfsor8bve/view?usp=sharing)
* **📊 Dataset:** [Access dacl10k Dataset](https://datasetninja.com/dacl10k#download)

---

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch, torchvision
* **Computer Vision:** OpenCV
* **Visualization:** Matplotlib, NumPy

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yousefahmed2004/crack-classification-detection-multiclass.git](https://github.com/yousefahmed2004/crack-classification-detection-multiclass.git)

# 🏗️ Crack Classification & Detection (Multiclass) using Mask R-CNN

This project implements a state-of-the-art **Instance Segmentation** model to detect and classify structural defects in bridges and buildings. Using the **dacl10k** dataset, the model creates precise masks over cracks and damages.

---

## 📸 Project Screenshots
Visual representation of the model prediction results and project interface:

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234251.png" width="45%" alt="Detection 1" />
  <img src="screenshots/Screenshot%202025-12-30%20234323.png" width="45%" alt="Detection 4" />
</p>

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234307.png" width="45%" alt="Detection 3" />
   <img src="screenshots/Screenshot%202025-12-30%20234338.png" width="45%" alt="Detection 6" 
  
</p>

<p align="center">
  <img src="screenshots/Screenshot%202025-12-30%20234331.png" width="45%" alt="Detection 5" />
 />

  <img src="screenshots/Screenshot%202025-12-30%20234257.png" width="45%" alt="Detection 2" />
</p>

---

## 🧠 Model Architecture: Mask R-CNN
The model is built on the **Detectron2** framework, utilizing a **Mask R-CNN** architecture with a **ResNet-50-FPN** backbone.


**Key Features:**
* **Instance Segmentation:** Precise pixel-level detection of cracks.
* **Multiclass Classification:** Categorizes defects into multiple classes based on the **dacl10k** dataset.
* **Optimized Training:** Configured with a 30,000 iteration schedule and custom learning rate steps.

---

## 📂 Resources & Downloads
* **📦 Trained Model (.pth):** [Download from Google Drive](https://drive.google.com/file/d/1A77ToX419hQUbzy2bng6RrGbfsor8bve/view?usp=sharing)
* **📊 Dataset:** [Access dacl10k Dataset](https://datasetninja.com/dacl10k#download)

---

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** Detectron2 (Meta AI)
* **Libraries:** PyTorch, OpenCV, NumPy, Matplotlib

---

## 🚀 How to Run
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/yousefahmed2004/crack-classification-detection-multiclass.git](https://github.com/yousefahmed2004/crack-classification-detection-multiclass.git)

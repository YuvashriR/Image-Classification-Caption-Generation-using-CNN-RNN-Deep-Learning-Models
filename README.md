# 🧠 Image Classification & Captioning using CNN + RNN  
### Deep Learning • Computer Vision • NLP • PyTorch

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red.svg)
![Status](https://img.shields.io/badge/Project-Completed-success.svg)
![Model](https://img.shields.io/badge/CNN-RNN-orange.svg)
![License](https://img.shields.io/badge/License-OpenSource-green.svg)

---

### 📌 Project Summary

This repository demonstrates an end-to-end deep learning workflow where a model can:

✔ **Classify images** (TinyImageNet30)  
✔ **Generate captions for images** using CNN encoder + RNN decoder  
✔ Integrate **vision + language models** into one intelligent system  

---

## 🖼 Datasets Used

| Dataset | Details | Purpose |
|--------|---------|---------|
| **TinyImageNet30** | 13,500 images • 30 classes • 64×64 px | Image Classification |
| **COCO Subset (5070+ images)** | Each image has 5+ captions | Image Captioning |

---

---

## 🚀 Key Features

| Capability | Description |
|----------|-------------|
| 🧠 Custom CNN Models | Trained for multi-class classification |
| 🔗 CNN + RNN Pipeline | Convert visual features into captions |
| 📈 Performance Tracking | Accuracy, loss curves, ROC, confusion matrix |
| 🏋 Transfer Learning | CIFAR-10 — trained full & frozen-layer variants |
| ✍ Vocabulary + Embedding | Handled using torch text processing |

---

## 📊 Results & Evaluation

### 🧠 Image Classification (TinyImageNet30)
| Metric | Result |
|------|--------|
| Best Accuracy | _Insert final %_ |
| Epochs Trained | _Insert value_ |
| Model Used | Custom CNN |

📌 *Graphs included in notebook:*  
| 🔹 Training/Validation Accuracy | 🔹 Confusion Matrix | 🔹 ROC Curves |

---

### 📝 Image Captioning (COCO)

Sample Output:

| Input Image | Generated Caption |
|------------|-------------------|
| 🖼️ image_1.jpg | `"a dog runs through the grass"` |
| 🖼️ image_2.jpg | `"a group of people sitting at a table"` |
| 🖼️ image_3.jpg | `"a boat floating on blue water"` |
| 🖼️ image_4.jpg | `"children playing near a park"` |

📌 Cosine similarity used to compare generated vs reference captions.

---

## 📷 Screenshots

> *(Replace placeholder links with your own)*

| Image Classification Training | Captioning Output Samples |
|------------------------------|---------------------------|
| ![Training Plot](assets/training.png) | ![Generated Captions](assets/captions.png) |

---

## 🛠 Technology Stack

| Category | Tools |
|--------|---------------------|
| Language | Python |
| Deep Learning | PyTorch, torchvision |
| Visualisation | Matplotlib |
| Processing | NumPy, Pandas, OpenCV, PIL |

---

## 📜 How to Run

```bash
git clone https://github.com/<your-username>/Image-Classification-and-Image-Captioning.git
cd Image-Classification-and-Image-Captioning
pip install -r requirements.txt

I’m passionate about Computer Vision, NLP, and Deep Learning research.
Open to collaboration, discussion, and innovative project ideas!



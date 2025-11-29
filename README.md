# 🧠 Image Classification & Caption Generation using CNN–RNN

A deep learning project that performs **image classification** using CNN models and generates **natural language captions** through a CNN–RNN architecture. Built using **Python & PyTorch**, trained on TinyImageNet30 and COCO image feature embeddings.

---

## 🌐 Overview
This project develops an end-to-end image understanding pipeline.  
It begins with **Convolutional Neural Networks (CNNs)** for classifying TinyImageNet30 images, followed by a **Recurrent Neural Network (RNN) decoder** to generate captions.  
The core objective is to demonstrate how visual features and linguistic models work together in a unified multi-modal setup.

---

## ⭐ Features
| Feature | Description |
|---|---|
| 🔄 Data Preprocessing | Automated loading, resizing, augmentation, normalisation |
| 🧠 Custom CNN Models | Optimised for 30-class TinyImageNet30 dataset |
| 📊 Model Evaluation | Accuracy/loss plots, performance comparison |
| 🔗 Multi-Modal Learning | CNN feature extraction + RNN text decoding |
| ⚙ Deep Learning Framework | Built fully in Python & PyTorch |


## 🖼 Dataset Details
| Dataset | Size | Classes | Image Resolution |
|---|---|---|---|
| **TinyImageNet30** | 13,500 images | 30 categories | 64×64 |
| **COCO Subset** | 5070 images | 5+ captions/image | Used for captioning |

### Two Major Components
1. **Image Classification**
   - Built using **custom CNN layers, pooling & fully-connected layers**
   - Trained + validated on TinyImageNet30
   - Evaluated using accuracy, ROC, and confusion matrix

2. **Image Captioning**
   - CNN features encoded → passed into **RNN for word prediction**
   - Generates captions word-by-word
   - Evaluated using cosine similarity & qualitative testing

---

## 🛠 Technologies & Libraries
| Category | Tools |
|---|---|
| Language | Python |
| Framework | PyTorch |
| Visualization | Matplotlib |
| Data Handling | NumPy, h5py, OpenCV |
| Augmentation | torchvision.transforms |

---
## 🚀 Conclusion
This work demonstrates how **CNNs classify images** while **RNNs use the extracted features to generate meaningful captions**.  
The project highlights the value of multi-modal learning in computer vision + NLP applications, making it applicable to automation, search engines, assistive AI, and more.

---

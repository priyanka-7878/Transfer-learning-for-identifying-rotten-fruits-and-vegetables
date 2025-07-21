#  Smart Sorting Classifier

**Smart Sorting Classifier** is a deep learning-based project that classifies fruits and vegetables as **fresh** or **rotten** using transfer learning (VGG16) and a dataset from Roboflow. The project includes a clean, interactive Gradio web interface where users can upload an image and receive instant classification results.

---

## 📌 Features

- Image classification using VGG16 transfer learning
- Trained on custom fruit & vegetable dataset via Roboflow
- Supports augmentation and fine-tuning
- Gradio UI for easy image upload and prediction
- Visualization of training and evaluation metrics

---

## 🗂️ Dataset

- **Source:** [Roboflow](https://roboflow.com/)
- **folder:** `ripescan-2`
- **Classes:** Multiple categories of fruits and vegetables (fresh & rotten)
- **Split:** Training / Validation / Test folders

---

## 🚀 Setup & Installation

```bash
# Step 1: Install dependencies
!pip install roboflow gradio pillow_heif==0.11.1 --quiet

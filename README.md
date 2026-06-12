# 🌱 Augmentation of Datasets from Images & Transfer Learning for Neural Networks

[![Status](https://img.shields.io/badge/status-planned-yellow)]()

## 🎯 Purpose

This project aims to:

- Get acquainted with **dataset augmentation** techniques for image data
- Learn and implement **transfer learning** for neural networks

## 📊 Dataset Description

| Feature | Details |
|---------|---------|
| **Classes** | beans, bitter gourd, bottle gourd, eggplant, broccoli, cabbage, capsicum, carrot, cauliflower, cucumber, papaya, potato, pumpkin, radish, tomato |
| **Total Images** | 21,000 |
| **Images per Class** | 1,400 |
| **Resolution** | 224×224 pixels |
| **Format** | JPG |
| **Split Ratio** | Train: 70% \| Validation: 15% \| Test: 15% |

### 📥 Data Source

[Download Dataset from Google Drive](https://drive.google.com/drive/folders/1He5s1VTwm74jVUFvncyW2tkpX9zx982X?usp=sharing)

## 🧪 Project Tasks

### Task 1: Baseline CNN Classification
Build and train a convolutional neural network on the **original** dataset.

- ✅ Build training and validation curves
- ✅ Test results on the test set

### Task 2: CNN with Augmented Dataset
Apply the **same CNN architecture** as Task 1 on a pre-augmented dataset.

- ✅ Compare results with Task 1
- ✅ Draw conclusions on augmentation impact

### Task 3: Transfer Learning
Solve classification for both original and augmented datasets using **pre-trained models**.

**Requirements:**
- Use at least 3 pre-trained models
- Frameworks: [Keras Applications](https://keras.io/api/applications/) or [PyTorch Models](https://pytorch.org/vision/0.8/models.html)

**Actions:**
- ✅ Compare classification results
- ✅ Draw conclusions
- 🎯 (Optional) Test on arbitrary internet images of vegetables

## 📦 Expected Deliverables

- [ ] Training and validation curves for each task
- [ ] Test set accuracy results
- [ ] Comparison between baseline, augmented, and transfer learning models
- [ ] Conclusions based on performance differences
- [ ] (Optional) Predictions on custom internet images

## 🛠️ Suggested Frameworks

- **Keras**: [Model Applications](https://keras.io/api/applications/)
- **PyTorch**: [Vision Models](https://pytorch.org/vision/0.8/models.html)

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git

# Install dependencies (example)
pip install tensorflow torch torchvision matplotlib numpy

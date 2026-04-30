# Satellite Image Land-Use Classification Using EuroSAT Dataset

## Overview
This project classifies satellite images into different 
land-use categories using Deep Learning. A ResNet50-based 
CNN model is trained on the EuroSAT dataset using transfer 
learning to automatically identify land cover types from 
satellite imagery.

## Authors
- Wajeeha Attiq — wajeehaattiq7@gmail.com
- Taskeen Shoukat — teeni3372@gmail.com

Department of Computer Science  
Fazaia Bilquis College For Women, NUR Khan, Rawalpindi

---

## Problem Statement
Manual classification of satellite images is a 
time-consuming and complicated process. This project 
provides an intelligent automated framework using CNN 
and transfer learning to classify satellite images 
with high accuracy.

---

## Dataset — EuroSAT
- Total Images: 27,000 labeled satellite images
- Source: Sentinel-2 Satellite
- Image Size: 64x64 pixels
- Total Classes: 10

### Land Cover Classes:
1. Annual Crop
2. Forest
3. Herbaceous Vegetation
4. Highway
5. Industrial
6. Pasture
7. Permanent Crop
8. Residential
9. River
10. Sea / Lake

### Dataset Split:
- Training Set: 80% (21,600 images)
- Validation/Testing Set: 20% (5,400 images)

---

## Model Architecture
- Base Model: ResNet50 (Transfer Learning)
- Input Size: 64x64 pixels (RGB channels)
- Optimizer: Adam (learning rate = 0.001)
- Loss Function: Categorical Cross-Entropy
- Output Layer: Softmax (10 classes)

---

## Data Preprocessing & Augmentation
- Images resized to 64x64 pixels
- Pixel values normalized between 0 and 1
- Data Augmentation techniques applied:
  - Rotation
  - Horizontal & Vertical Flipping
  - Zooming
  - Brightness Adjustment

---

## Results
| Model | Accuracy |
|---|---|
| ResNet50 (CNN) | 92 - 94% |
| SVM | 85 - 88% |
| Random Forest | 85 - 88% |
| KNN | 80 - 83% |
| MLP | 80 - 83% |

CNN-based ResNet50 outperformed all traditional 
machine learning classifiers.

---

## Technologies Used
- **Language:** Python
- **Deep Learning:** PyTorch / TensorFlow / Keras
- **Data Processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Traditional ML:** Scikit-Learn
- **Platform:** Google Colab

---

## Applications
This classifier can be used in real-world applications:
- Urban Planning
- Environmental Monitoring
- Agricultural Management
- Disaster Management and Relief

---

## References
- Helber et al. (2019) — EuroSAT Dataset, IEEE Journal
- Helber et al. (2018) — IEEE IGARSS Conference
- AlAfandy et al. (2020) — Classic Networks for Remote Sensing
- Naushad et al. (2021) — Deep Transfer Learning for LULC

---

## Contact
Wajeeha Attiq  
GitHub: github.com/wajeehaattiq  
Email: wajeehaattiq7@gmail.com  
Portfolio: https://wajeehaattiq.github.io

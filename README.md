# Potato Blight Detection - Data Processing

## **Overview**

This project processes potato leaf images to classify them into three categories: **Healthy**, **Late Blight**, and **Early Blight**. The images undergo preprocessing and augmentation steps to prepare them for model training.

## **Data Sources**

- **Kaggle**: Potato Disease Dataset
- **GitHub**: PlantVillage Dataset

## **Data Processing Steps**

### 1. **Image Augmentation**
   - Rotation
   - Width & height shifting
   - Zooming
   - Horizontal flipping

### 2. **Normalization**
   - Resizing images to 64x64 pixels.
   - Normalizing pixel values to a range of [0, 1].

### 3. **Class Weighting**
   - Calculating **balanced class weights** to address class imbalances.

## **Data Structure**

- **Training Data**:
  - `late/`: Images of leaves with late blight.
  - `early/`: Images of leaves with early blight.
  - `healthy/`: Images of healthy leaves.
  
- **Validation Data**:
  - `late/`: Validation images of leaves with late blight.
  - `early/`: Validation images of leaves with early blight.
  - `healthy/`: Validation images of healthy leaves.

---

Feel free to adjust or expand based on any specific details you want to highlight. Let me know if you need further changes!

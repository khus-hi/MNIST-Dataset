# MNIST-Dataset
A simple machine learning project that classifies handwritten digits (0–9) using the MNIST dataset. KNN is used to train on 28x28 grayscale images and predict digits.

## 📊 Dataset Description

- Each image is **28x28 pixels** (784 total pixels).
- **Pixel values** range from **0 (white)** to **255 (black)**.
- In `train.csv`:
  - The **first column** is `label` (the actual digit).
  - The remaining **784 columns** are pixel values named `pixel0` to `pixel783`.
- In `test.csv`:
  - Only the pixel values are provided (no labels).
 
  ## 🚀 Project Workflow

1. **Load the data** from `train.csv` and `test.csv`.
2. **Preprocess the data**:
   - Normalize pixel values.
   - Reshape for model input (e.g., for CNN).
3. **Train machine learning model**:
   - K-Nearest Neighbors (KNN)
4. **Make predictions** on the test set.

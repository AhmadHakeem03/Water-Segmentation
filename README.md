# U-Net for Image Segmentation

This project implements a **U-Net** model in TensorFlow/Keras for binary image segmentation tasks.  
It includes data loading, preprocessing, model training, evaluation, and visualization utilities.

---

## 📂 Project Structure
- **Model**
  - Compact U-Net implementation (`create_unet`).
  - Dice coefficient metric for segmentation quality.
- **Evaluation**
  - Precision, Recall, F1-score, IoU, Accuracy.
  - Threshold sweep to find the best segmentation threshold.
- **Visualization**
  - Training history plots (loss & dice).
  - F1 & IoU vs. threshold curve.
  - Sample predictions compared to ground truth.

---

## ⚙️ Requirements
Install the following dependencies:

```bash
pip install numpy matplotlib tifffile pillow tensorflow scikit-learn

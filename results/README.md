# Results

This folder contains the experimental results of the project:

**Breast Cancer Classification Using EfficientNet-B4 and CLAHE Enhancement**

---

## Dataset

- **Dataset:** BreakHis (Breast Cancer Histopathological Image Classification)
- **Classification:** Binary
  - Benign
  - Malignant

---

## Model

- EfficientNet-B4 (Transfer Learning)
- Image Size: 380 × 380
- Optimizer: AdamW
- Learning Rate Scheduler: Cosine Annealing
- Loss Function: Focal Loss with Label Smoothing

---

## Image Preprocessing

- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Image Normalization
- Data Augmentation
- Transfer Learning

---

## Performance Metrics

The following metrics are used to evaluate the model:

- Accuracy
- Precision
- Recall (Sensitivity)
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Result Files

| File | Description |
|------|-------------|
| confusion_matrix.png | Confusion Matrix |
| roc_curve.png | ROC Curve |
| accuracy_curve.png | Training & Validation Accuracy |
| loss_curve.png | Training & Validation Loss |
| metrics.txt | Final evaluation metrics |

---

## Final Performance

| Metric | Value |
|---------|------:|
| Validation Accuracy | 98.31% |
| Test Accuracy | 98.57% |
| Test-Time Augmentation Accuracy | 98.23% |
| ROC-AUC Score | 99.83% |

---

## Sample Visualizations

Place the following figures inside this directory:

- Confusion Matrix
- ROC Curve
- Accuracy Curve
- Loss Curve
- Sample Predictions

---

## Conclusion

The proposed EfficientNet-B4 model combined with CLAHE image enhancement achieved high performance on the BreakHis binary classification dataset. The preprocessing pipeline and transfer learning significantly improved classification accuracy while maintaining excellent ROC-AUC performance.

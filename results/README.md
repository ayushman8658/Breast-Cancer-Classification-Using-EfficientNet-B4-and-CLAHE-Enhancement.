# Results

This folder contains the experimental results of the project:

**Breast Cancer Classification Using EfficientNet-B4 and CLAHE Enhancement**

---

## Dataset

- **Dataset:** BreakHis (Breast Cancer Histopathological Image Classification)
- **Classification:** Binary
  - Benign
  - Malignant

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
| `confusion_matrix.png` | Confusion Matrix |
| `roc_curve.png` | ROC Curve |
| `accuracy_curve.png` | Training & Validation Accuracy |
| `loss_curve.png` | Training & Validation Loss |
| `metrics.txt` | Final Evaluation Metrics |

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

## References

- BreakHis Dataset: https://www.kaggle.com/datasets/ambarish/breakhis
- EfficientNet: https://arxiv.org/abs/1905.11946
- CLAHE: Contrast Limited Adaptive Histogram Equalization

---

## Reproducibility

To reproduce the reported results:

1. Download the BreakHis dataset.
2. Apply CLAHE preprocessing.
3. Train EfficientNet-B4 using AdamW optimizer.
4. Evaluate using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

## Conclusion

The proposed EfficientNet-B4 model with CLAHE preprocessing demonstrates excellent performance for binary breast cancer histopathological image classification. Transfer learning, advanced preprocessing, and data augmentation collectively contributed to achieving a test accuracy of **98.57%** and a **99.83% ROC-AUC**, highlighting the model's potential for reliable computer-aided diagnosis.

## Citation

If you use this work in your research, please consider citing this repository.

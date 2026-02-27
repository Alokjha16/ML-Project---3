# 🚀 Vision Transformer Based Semantic Segmentation

## 📌 Project Overview
This project implements a pixel-level semantic segmentation model using a pretrained DINOv2 backbone combined with a convolutional decoder.

The model is designed for efficient feature extraction and accurate spatial reconstruction.

---

## 🏗️ Architecture Details

- **Backbone:** DINOv2 (dinov2_vits14)
- **Decoder:** CNN-based segmentation head
- **Input Size:** 252 × 448
- **Number of Classes:** 10
- **Framework:** PyTorch

---

## 🔍 Highlights

- Transformer-based feature extraction
- Custom convolutional upsampling head
- Stable training configuration
- Efficient validation pipeline

---

## 📊 Validation Results

| Metric | Value |
|--------|--------|
| IoU | **0.4568** |

---

## 🖼️ Sample Output
<img width="1005" height="502" alt="Screenshot 2026-02-28 012252" src="https://github.com/user-attachments/assets/a547eea6-7d2f-4e6c-ba26-c6295fb95adb" />


---

## ▶️ Execution

```bash
python train_segmentation.py
python generate_submissions.py
python evaluate_variants.py
```

---

## 🛠️ Dependencies

- Python 3.9+
- PyTorch
- torchvision
- NumPy

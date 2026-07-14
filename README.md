#  Fruit Quality Inspection using Grad-CAM

A deep learning-based fruit quality inspection system that classifies fruit freshness using Convolutional Neural Networks (CNNs) and Transfer Learning models with Explainable AI (Grad-CAM) for visual interpretation of predictions.

---

##  Project Overview

This project focuses on automatic fruit freshness detection using deep learning. Multiple CNN architectures were trained and evaluated for binary (Fresh/Rotten) and multiclass fruit classification. To improve model transparency, Grad-CAM was integrated to visualize the image regions influencing model predictions.

---

##  Features

- Fresh vs Rotten fruit classification
- Multiple deep learning models
- Transfer Learning using MobileNetV2 and ResNet50
- Fusion model implementation
- Explainable AI using Grad-CAM
- Jupyter Notebook based implementation
- Pre-trained models included

---

##  Models Included

- Base CNN (Augmented)
- MobileNetV2 (Frozen)
- MobileNetV2 (Fine-Tuned)
- ResNet50 Binary Model
- Fusion Model

---

##  Repository Structure

```
fruit-quality-inspection-using-gradcam/
│
├── models/
│   ├── base_cnn_augmented.keras
│   ├── fusion_model.keras
│   ├── mobilenet_multiclass_finetuned.keras
│   ├── mobilenet_multiclass_frozen.keras
│   └── resnet_binary.h5
│
├── notebooks/
│   ├── 1_final_fruit_prediction_imp_prev.ipynb
│   ├── 4_frozen_fruit_preds.ipynb
│   ├── 5_fusion_fruit.ipynb
│   ├── 6_mobile_net_fine_tuned.ipynb
│   ├── 7_augmented_preds.ipynb
│   └── resnet_final_model_fruit.ipynb
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

##  Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

##  Getting Started

### Clone Repository

```bash
git clone https://github.com/rakshit-ladda/fruit-quality-inspection-using-gradcam.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run

Open any notebook inside the `notebooks` folder using Jupyter Notebook or Google Colab.

---

##  Explainable AI

Grad-CAM is used to visualize the regions of the fruit image that contribute most to the model's prediction, improving transparency and interpretability.

---

##  Future Work

- Real-time fruit quality inspection
- Web application deployment
- Mobile application integration
- Edge AI deployment
- Multi-view fruit inspection
- Out-of-Distribution (OOD) detection
- Composite Explainability Confidence Score (ECS)

---

##  Author

**Rakshit Ladda**

GitHub: https://github.com/rakshit-ladda

---

## 📄 License

This project is licensed under the MIT License.

# 🌿 Plant Disease Detection using Hybrid Deep Learning Model

## Overview

This repository contains the trained deep learning model and sample outputs for a plant disease detection system developed as part of a published research work.

The project focuses on automatic plant disease identification from leaf images using deep learning techniques. The trained model is provided for demonstration and academic purposes only.

> **Note:** The complete source code is **not included** because this work is associated with a published research paper.

---

## Features

- Plant leaf disease classification
- Deep learning-based image classification
- Pre-trained Keras model
- Sample prediction outputs
- High classification accuracy
- Research publication implementation

---

## Repository Contents

```
├── Disease_Model.keras # Trained Keras model
├── Outputs/
│ ├── output1.png
│ ├── output2.png
│ ├── output3.png
│ └── ...
├── README.md
```

---

## Model Information

| Item | Description |
|------|-------------|
| Framework | TensorFlow / Keras |
| Model Format | `.keras` |
| Task | Plant Disease Classification |
| Input | Leaf Images |
| Output | Predicted Disease Class |

---

## Dataset

The model was trained using publicly available plant leaf image datasets together with additional preprocessing and experimentation performed during the research.

---

## Sample Outputs

Example prediction results are available in the **Outputs** folder.

These images demonstrate the model's disease classification capability.



---

## Usage

The trained model can be loaded using TensorFlow/Keras.

```python
from tensorflow.keras.models import load_model

model = load_model("Disease_Model.keras")
```

---

## Research Publication

This repository is based on our published research.

If you use this work for academic purposes, please cite the corresponding publication.

---

## Source Code

The implementation source code is **not publicly available**.

This repository provides only:

- Trained model
- Sample prediction outputs
- Documentation

to protect the originality of the published research.

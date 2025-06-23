# Dog-Skin-Disease-Detection and Treatment-Recommendation

This project aims to help identify common skin diseases in dogs using a convolutional neural network (CNN) model built with MobileNetV2. The system classifies images into four categories—bacterial dermatosis, fungal infection, hypersensitivity dermatitis, and healthy—and recommends a set of medications or treatments based on veterinary best practices. It is designed to assist in early screening of street dogs or pets, especially in resource-limited settings where veterinary access is delayed.

---

## 🧠 Model Overview

- **Architecture**: Transfer learning using MobileNetV2
- **Classifier**: Multiclass softmax (4 skin condition classes)
- **Input**: Dog skin image
- **Output**: Predicted condition + suggested medicines

---

## 🐶 Classes Covered

| Label                         | Description                            |
|-------------------------------|----------------------------------------|
| `bacterial_dermatosis`        | Skin infections due to bacteria        |
| `fungal_infection`            | Includes yeast and ringworm            |
| `hypersensitivity_dermatitis` | Allergic skin inflammation             |
| `healthy`                     | No visible skin problems               |

---

## 💊 Treatment Suggestions

Each condition comes with a curated list of suggested treatments.  
Here are examples:

### Bacterial Dermatosis
- Chlorhexidine 4% shampoo
- Cephalexin (oral antibiotic)
- Mupirocin ointment

### Fungal Infection
- Ketoconazole shampoo
- Itraconazole (oral)
- Miconazole spray

### Hypersensitivity Dermatitis
- Apoquel (Oclacitinib)
- Cytopoint injection
- Prednisone (short-term)

> ⚠️ Always consult a veterinarian before applying medication.

---
## 🗂 Dataset

- **Name**: [Dogs Skin Disease Dataset] (https://www.kaggle.com/datasets/yashmotiani/dogs-skin-disease-dataset)
- **Source**: Kaggle

---
## 🛠️ Technologies Used

### 🖥️ Programming Language

Python

### 📚 Libraries

NumPy

pandas

scikit-learn

TensorFlow / Keras

PIL (Pillow)

Matplotlib

### 🛠️ Tools

Jupyter Notebook

Kaggle Notebooks

GitHub (version control and sharing)

---

## 📈 Evaluation

Reports: Confusion matrix & Classification report

Model: MobileNetV2 + global average pooling + Dense output

---

## 📌 Future Improvements

Streamlit or Flask UI for user-friendly access

Extend dataset with more skin conditions (e.g., mange, flea allergy)

Deploy as an Android app with on-device ML

---

## 👤 Author

1. Jit Mandal
2. Ritam Koley


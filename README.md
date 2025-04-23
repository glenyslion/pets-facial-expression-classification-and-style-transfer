# 🐶 Pets Facial Expression Classification & Artistic Style Transfer 🎨

This project aims to classify pet facial expressions using deep learning and apply various artistic style transfer techniques to pet images — turning your furry friend into a work of art!

---

## 📌 Project Overview

### Facial Expression Classification
We classify pet facial expressions into **Happy**, **Sad**, **Angry**, and **Other** using:
- **Custom CNN**
- **Transfer Learning** (MobileNet, ResNet, EfficientNet)
- **Image augmentation** to improve generalization

### Artistic Style Transfer
We applied styles from famous paintings to pet images using:
- **Neural Style Transfer (NST)**
- **Fast Style Transfer (FST)**
- **CycleGAN**

---

## Data
- Pet images include dogs, cats, hamsters, birds, horses, rabbits, and sheep.
- Dataset split: 1000 training, 36 validation, 38 test samples.
- Image source: [Pets Facial Expression Dataset on Kaggle](https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset)

---

## Models & Results

| Model        | Train Accuracy | Test Accuracy |
|--------------|----------------|---------------|
| CNN (Custom) | 25%            | 29%           |
| MobileNet    | 60%            | 53%           |
| ResNet       | 32%            | 32%           |
| EfficientNet | 46%            | 24%           |

MobileNet showed the best results due to its smaller architecture, making it ideal for the small dataset.

---

## Repository Structure
```text
├── EDA.ipynb                                         # Exploratory Data Analysis
├── Image_Classification.ipynb                        # Custom CNN & Transfer Learning
├── Style_Transfer_CycleGAN.ipynb                     # CycleGAN Implementation
├── Style_Transfer_NST_Fast_Style_Transfer.ipynb      # NST & FST
├── Presentation.pdf                                  # Project Slides
├── README.md                                         # This file
```

---

## Future Work
- Augment dataset using GANs
- Fine-tune classification models
- Deploy a web app for pet emotion prediction
- Combine NST and CycleGAN for hybrid stylization

---

## Team Credits
Project developed by:
- Fuqian Zou
- Glenys Lion
- Iris Lee
- Liana Bergman-Turnbull

## Thank you!
This project was developed as part of a data mining course. We appreciate your interest and welcome feedback!

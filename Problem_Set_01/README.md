# Problem Set 01 — Pneumonia Detection from Chest X-Ray Images

## 1. Problem Statement

The objective of this problem is to develop a Convolutional Neural Network (CNN) model that can classify pediatric chest X-ray images into two categories:

- NORMAL
- PNEUMONIA

The dataset contains anterior-posterior chest X-ray images and is organized into training, validation, and testing directories. The task is to learn visual patterns from the X-ray images and use them to predict the corresponding class of an unseen image.

---

## 2. Objective

The main objectives of this problem are:

1. Load and organize the chest X-ray image dataset.
2. Prepare the images for CNN-based classification.
3. Apply suitable image preprocessing and data augmentation.
4. Handle the class imbalance in the training data.
5. Build and train a CNN model.
6. Evaluate the trained model using the test dataset.
7. Analyze the classification performance using accuracy, precision, recall, confusion matrix, and ROC-AUC.

---

## 3. Dataset

The dataset consists of chest X-ray images categorized into:

- `NORMAL`
- `PNEUMONIA`

The images are divided into:

- Training set
- Validation set
- Test set

In the implementation, the images are resized to:

```text
224 × 224 pixels

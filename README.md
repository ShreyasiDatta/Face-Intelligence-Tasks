# Face Classification & Recognition Project

This repository contains two computer vision tasks: binary gender classification and multi-class face recognition with distorted image handling. The models are developed using deep learning techniques and trained on custom datasets.



## 🔹 Task A: Gender Classification (Binary Classification)

📌 Objective

Build a binary classification model to distinguish between **male** and **female** face images.

📂 Dataset Structure

```
train/
 ├── male/
 └── female/
val/
 ├── male/
 └── female/
```

🧠 Goal

Train a model that accurately predicts the gender (male or female) from a given face image.

---

## 🔹 Task B: Face Recognition (Multi-Class Classification)

 📌 Objective

Develop a face recognition system that can identify individuals from both original and **distorted** face images.

📂 Dataset Structure

```
dataset/
 ├── person_1/
 │    ├── img1.jpg
 │    └── img2.jpg
 ├── person_2/
 │    └── ...
distorted/
 ├── distorted_img1.jpg
 └── distorted_img2.jpg

🧠 Goal

Given a face image (or its distorted version), correctly match it to the corresponding person folder:

Match (Label = 1):If the input image matches any face in the same folder.
Non-Match (Label = 0):If the input image matches a face from a different folder.


🛠️ Technologies Used

* Python
* TensorFlow / PyTorch
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib (for visualization)

📈 Future Work

* Improve model robustness to lighting and pose variations.
* Apply data augmentation to improve generalization.
* Explore face embeddings with triplet loss or Siamese Networks for Task B.


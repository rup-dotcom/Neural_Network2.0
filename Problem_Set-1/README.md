🧠 Pneumonia Detection using Convolutional Neural Network (CNN)

 📌 Project Overview

This project focuses on building a deep learning model to classify chest X-ray images into two categories:

* **Pneumonia**
* **Normal**

The goal is to assist in automated medical diagnosis using image classification techniques.

---

📂 Dataset Description

* Total Images: **5,863**
* Categories: **2 (Pneumonia, Normal)**
* Structure:

  ```
  train/
  val/
  test/
  ```
* Source: Pediatric chest X-rays (ages 1–5)
* Format: JPEG images (Anterior-Posterior view)

---

⚙️ Methodology

🔹 1. Data Preprocessing

* Images resized to **150×150**
* Pixel normalization (rescale = 1/255)
* Data augmentation applied on training data:

  * Rotation
  * Zoom
  * Horizontal flip

---

🔹 2. Model Architecture (CNN)

The model consists of:

* Convolutional layers (feature extraction)
* MaxPooling layers (downsampling)
* Fully connected layers
* Dropout layer (to reduce overfitting)

Final layer:

* **Sigmoid activation** → Binary classification

---

🔹 3. Training Strategy

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Epochs: 10–15
* EarlyStopping used to prevent overfitting

---

🔹 4. Evaluation Metrics

* Accuracy
* Loss
* Confusion Matrix

---

📊 Results & Findings

* The CNN model successfully learned to distinguish between Pneumonia and Normal cases.
* Data augmentation improved generalization.
* Dropout and EarlyStopping reduced overfitting.

✅ Key Insight:

The model performs well on test data, indicating that deep learning can effectively assist in medical image classification tasks.

---

🚀 Future Improvements

* Use **Transfer Learning (ResNet/MobileNet)** for higher accuracy
* Apply **Grad-CAM** for model interpretability
* Use **Precision, Recall, F1-score** for better medical evaluation

---

🧾 Conclusion

This project demonstrates how CNNs can be applied in healthcare for automated diagnosis. While promising, real-world deployment requires further validation and clinical testing.

---


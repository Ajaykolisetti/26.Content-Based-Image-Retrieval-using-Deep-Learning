
# Content-Based Image Retrieval using Deep Learning

This project implements a **Content-Based Image Retrieval (CBIR)** system using deep learning models. It utilizes the **COREL1000 image dataset** and extracts image features using pre-trained CNN architectures like **VGG16, MobileNet, and ResNet**. Retrieved features are compared using **Cosine Similarity** to return the **top 10 most similar images** to a query.

## 📂 Dataset

* **COREL1000 Dataset**
* 10 categories (e.g., Bus, Food, Dinosaur, etc.)
* 1000 images total
* 80% training, 20% testing

## 🧠 Models Used

* **VGG16** – Achieved \~98% accuracy
* **MobileNet** – Achieved \~88% accuracy
* **ResNet** – Achieved \~10% accuracy (not effective in this case)

## 🔧 Features

* Image preprocessing (resize, normalize, split)
* Model training & evaluation (accuracy, confusion matrix)
* Interactive GUI for:

  * Uploading dataset
  * Training models
  * Viewing performance metrics
  * Querying CBIR system using test images

## 🚀 How to Run

1. Double-click `run.bat` to start the application.
2. Use the GUI to:

   * Upload the COREL dataset.
   * Preprocess and split the data.
   * Train any of the three deep learning models.
   * View accuracy graphs and confusion matrices.
   * Upload a test image and retrieve similar images using CBIR.

## 📊 Performance Summary

| Model     | Accuracy |
| --------- | -------- |
| VGG16     | 98%      |
| MobileNet | 88%      |
| ResNet    | 10%      |

> 📌 **Note:** VGG16 performed the best, followed by MobileNet. ResNet performed poorly on this dataset.

## 📷 CBIR Demo

1. Upload a test image (e.g., bus or dinosaur).
2. The system returns 10 most similar images based on deep feature vectors and cosine similarity.

## 🛠 Dependencies

Make sure you have the following installed:

* Python 3.x
* TensorFlow
* Keras
* NumPy
* OpenCV
* Other dependencies as required in your environment

## 📁 Folder Structure

```
├── run.bat
├── dataset

## ✍️ Authors

Developed as part of an academic project on deep learning and content-based image retrieval.


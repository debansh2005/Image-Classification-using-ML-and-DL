# Image Classification sing ML vs DL
Comparative study of ML and DL techniques, such as SVM, Decision Tree, Random Forest, VGG16, and Inception v3, in solving image classification tasks.

## Overview

This project presents a comparative study of Machine Learning (ML) and Deep Learning (DL) techniques for image classification.
The goal is to evaluate performance differences between traditional ML algorithms and modern deep learning models on image datasets.

---

## Models Used

### 🔹 Machine Learning

* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

### 🔹 Deep Learning

* VGG16 (Transfer Learning)
* InceptionV3

---

## Feature Engineering

* Image preprocessing
* Feature extraction (RGB, HSV, LBP, Sobel)
* Model training and evaluation
* Accuracy comparison

---

## Tech Stack

* Python
* Scikit-learn
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas, Matplotlib

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

```
├── ML_models.ipynb
├── DL_Models.ipynb
├── README.md
```


---


## Results
### 🔹 Machine Learning Models
<img src="file:///C:/Users/KIIT0001/OneDrive/Pictures/Screenshots/Screenshot%202026-04-15%20213440.png" width="500"/>
### 🔹 Deep Learning Models
<img src="results/images/dl_comparison.png" width="500"/>


| Model         | Type | Accuracy   |
| ------------- | ---- | ---------- |
| SVM           | ML   | ~88%       |
| Random Forest | ML   | ~81%       |
| Decision Tree | ML   | ~61%       |
| VGG16         | DL   | **96.73%** |
| InceptionV3   | DL   | ~95.64%    |

👉 Deep Learning models significantly outperform traditional ML models in image classification tasks.

## Key Insights
* ML models achieve moderate accuracy (~60–90%)
* DL models perform better on image data
* VGG16 gives the best performance

Note: Models were trained with limited epochs due to hardware constraints. Accuracy can improve with longer training.

## Conclusion

* ML works well for smaller datasets
* DL provides higher accuracy for complex image classification
* Transfer learning significantly improves performance

---

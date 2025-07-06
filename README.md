# Image-Classification-Vehicles

This project is a simple image classification model built using **Teachable Machine** to classify vehicle images into three categories:  
- Car  
- Motorcycle  
- Truck

It was developed as part of a training task to apply basic AI skills for image classification.

---

## Dataset

- Total of **120 images** (40 images per class)
- Images were collected from online sources
- Classes used in this project:
  - **Car**
  - **Motorcycle**
  - **Truck**

---

##  Tools & Technologies

- [Teachable Machine](https://teachablemachine.withgoogle.com/)
- Exported files:
  - `keras_model.h5` (Keras model)
  - `labels.txt` (class labels)
- Model tested using **Google Colab**
- Used **TensorFlow** to run the model in Python
---

## ▶️ How to Use

The exported model files (`keras_model.h5` and `labels.txt`) were uploaded to Google Colab, where the model was loaded and tested on new images.

> Note: This is an educational project and not intended for production use.

---

##  Code & Testing

Python code was used in Google Colab to:
- Load the model
- Test it on new images
- Display predictions

📎 Full code notebook: [vehicle_model_test.ipynb](vehicle_model_test.ipynb)

---

## Sample Results

### Model Preview from Teachable Machine  
![Model Preview](https://github.com/اسم_المستخدم/image-classification-vehicles/blob/main/model-preview.png?raw=true)

### Prediction Example from Google Colab  
![Prediction](https://github.com/اسم_المستخدم/image-classification-vehicles/blob/main/prediction-example.png?raw=true)

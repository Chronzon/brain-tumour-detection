# Predicting Brain Tumor using CNN

This project aims to predict brain tumors using Convolutional Neural Networks (CNN) with MRI images. The project is implemented using Kaggle, with the dataset [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).

## What is a Brain Tumor?

A brain tumor is an abnormal growth of cells in or around the brain. Brain tumors can be cancerous (malignant) or non-cancerous (benign). Early diagnosis of brain tumors is critical for effective treatment. Using MRI (Magnetic Resonance Imaging) scans, medical professionals can assess the presence of various types of brain tumors.

## Dataset

The dataset used for this project can be found on Kaggle: [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).

### Structure

The dataset is organized into two main directories:
- **Training**: Used to train the model.
- **Testing**: Used to evaluate the model's performance.

Each directory contains four subdirectories corresponding to different types of brain tumor classifications:
- **glioma_tumor**
- **meningioma_tumor**
- **no_tumor**
- **pituitary_tumor**

## Model Description

The project uses a Convolutional Neural Network (CNN) model to classify MRI images into one of four categories:
- Glioma Tumor
- Meningioma Tumor
- No Tumor
- Pituitary Tumor

The model is trained on the provided dataset and then tested by predicting the presence of tumors in 9 randomly selected MRI images from each category.

### Tools and Libraries

- **Kaggle**: The project was coded on the Kaggle platform.
- **TensorFlow/Keras**: Used for building the CNN model.
- **NumPy** and **Pandas**: For data manipulation.
- **Matplotlib**: For visualizing results.

## Project Output

After training, the model is used to predict brain tumors in 9 randomly selected images from each tumor category. These predictions are shown along with the corresponding MRI images.

## How to Access the Project

You can access and explore the code for this project on Kaggle:  
[Predicting Brain Tumor using CNN](https://www.kaggle.com/code/devlenandyanto/kelompok-3-cnn-predicting-brain-tumor/notebook)

## Credits

- **Dataset**: [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)
- **Author**: Devlen Andyanto

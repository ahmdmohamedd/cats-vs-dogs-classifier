# Cats vs Dogs Classifier

A convolutional neural network (CNN) built with TensorFlow to classify images of cats and dogs. This project demonstrates the use of data augmentation, model training, evaluation, and testing with new images. The trained model is saved for future use.

---

## Features
- Data preprocessing with augmentation (rotation, zoom, flipping, etc.).
- CNN architecture with multiple convolutional layers.
- Visualizations of training and validation accuracy/loss.
- Trained model saving for deployment or future predictions.

---

## Requirements
- Python 3.8 or higher
- TensorFlow 2.x
- Matplotlib
- Numpy

Install dependencies with:
```bash
pip install tensorflow matplotlib numpy
```

---

## Dataset
The dataset is **Cats vs Dogs**, available through TensorFlow's dataset repository. It consists of:
- 2000 training images
- 1000 validation images

Images are automatically downloaded and preprocessed.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/cats-vs-dogs-classifier.git
   cd cats-vs-dogs-classifier
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook cats_vs_dogs_classification.ipynb
   ```

3. Follow the notebook to:
   - Load and augment the dataset.
   - Train the CNN model.
   - Evaluate and visualize model performance.
   - Test predictions on new images.

4. Save the model for deployment.

---

## Model Performance
The model achieves significant accuracy in classifying cats and dogs, with visualizations of training and validation metrics to monitor overfitting or underfitting.

---

# Diabetic Retinopathy Detection using Artificial Intelligence

This project involves the detection of **diabetic retinopathy** using artificial intelligence. Three deep learning models, **ResNet-50**, **DenseNet121**, and **VGG-19**, were used to classify retinal images for diabetic retinopathy diagnosis.

## Models and Results

- **ResNet-50**:
  - Accuracy: **77.32%**
  - Recall: **88.97%**
  - F1-Score: **90.53%**

- **DenseNet121**:
  - Accuracy: **83.33%**
  - Recall: **92.96%**
  - F1-Score: **93.97%**

- **VGG-19**:
  - Accuracy: **84.69%**
  - Recall: **93.35%**
  - F1-Score: **94.69%**

## Dataset

The **APTOS 2019 Blindness Detection** dataset was used for this project. It consists of retinal images categorized into five stages of diabetic retinopathy. Data preprocessing techniques, including resizing and normalization, were applied to ensure uniformity and enhance model performance.


## Technologies Used

- **Python**: For model implementation and data processing.
- **TensorFlow** and **Keras**: Deep learning frameworks for training and evaluation.
- **ResNet-50**, **DenseNet121**, **VGG-19**: Pre-trained models for feature extraction and classification.
- **Pandas** and **NumPy**: For data manipulation.
- **Matplotlib**: For visualizing results.

## Acknowledgements
- Pre-trained models obtained from the Keras Applications library.
- Dataset sourced from publicly available diabetic retinopathy image repositories.

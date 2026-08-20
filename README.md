# Satellite Imagery-Based Poverty Classification

## Project Description
This project leverages deep learning and computer vision to classify poverty levels in Bolivia using satellite imagery. The system categorizes regions into three distinct classes: Low Poverty, Medium Poverty, and High Poverty. Built with TensorFlow and Keras, the project utilizes the EfficientNetB0 architecture for robust image classification and includes comprehensive model evaluation metrics.

## Key Features & Achievements
* **Dataset Processing:** Automated the downloading and processing of the `poverty-bolivia-satellite-images-dataset` from Kaggle.
* **Deep Learning Architecture:** Implemented transfer learning using the `EfficientNetB0` model tailored for 224x224 image inputs.
* **Optimized Training Pipeline:** Configured a training pipeline with a batch size of 32, learning rate of 0.001, and integrated advanced callbacks like `EarlyStopping`, `ReduceLROnPlateau`, and `ModelCheckpoint` to prevent overfitting.
* **Model Evaluation:** Utilized `scikit-learn` to generate detailed classification reports and confusion matrices for thorough performance analysis.
* **Data Visualization:** Integrated `matplotlib` and `seaborn` for clear visual representation of the dataset and training metrics.

# Human Segmentation with U-Net

## Project Overview

This project focuses on the implementation of a Semantic Segmentation model based on PyTorch for the detection of human bodies in images. The model utilizes the U-Net architecture with MobileNetV2 as the encoder and is trained using the AdamW optimization algorithm.

## Key Highlights

- **Semantic Segmentation Model:** Built a robust Semantic Segmentation model to accurately detect human bodies in images.

- **Data Partitioning and Augmentation:** Partitioned a dataset of 2,667 images into training, validation, and test sets. Applied data augmentation techniques to enhance the model's ability to generalize.

- **U-Net with MobileNetV2:** Employed the U-Net architecture with MobileNetV2 as the encoder for human segmentation, leveraging the strengths of both architectures.

- **AdamW Optimization Algorithm:** Utilized the AdamW optimization algorithm for efficient training and convergence of the segmentation model.

- **Model Evaluation:** Assessed the performance of the model on the test set, achieving a remarkable Mean Intersection over Union (MIoU) of 0.91 and an accuracy of 0.96.


**Note:** This notebook is designed to be run in Google Colab. Click the "Open in Colab" badge above to open the notebook in Colab.

## Data Source

The dataset used in this project can be found on Kaggle: [Supervisely Filtered Segmentation Person Dataset](https://www.kaggle.com/datasets/tapakah68/supervisely-filtered-segmentation-person-dataset/download?datasetVersionNumber=3)

## Technologies Used

- PyTorch
- U-Net
- AdamW Optimizer

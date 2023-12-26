# Brain Tumor Detection from MRI Images

## Overview

This project aims to detect brain tumors from MRI images using various convolutional neural network (CNN) architectures. The dataset, sourced from Kaggle, consists of 253 MRI images with binary labels: 'yes' indicating the presence of a brain tumor and 'no' indicating its absence.

### Model Architectures Explored

1. **Simple CNN:** Basic convolutional neural network.
2. **VGG16 Variations:** Six different variations of the VGG16 architecture.
3. **ResNet:** A residual neural network.

After experimenting with these architectures, the VGG16 model achieved the highest accuracy, reaching 81%.

## Dataset

The dataset comprises two folders: 'yes' and 'no', representing images with and without brain tumors, respectively. It is crucial to note that during manual inspection, one image (image 19 in the 'no' directory) was identified as a coronal scan, while the rest were axial scans.<br>
Source: [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

## Model Performance

The selected VGG16 architecture yielded an accuracy of 81%. Further fine-tuning and optimization can be explored to enhance model performance.

## Future Prospects/Scope

### 1. Hyperparameter Tuning:
   Systematically tune hyperparameters such as learning rate, batch size, and dropout rates for better model convergence.

### 2. Model Ensemble:
   Combine predictions from multiple models to improve overall performance and robustness.

### 3. Addressing Class Imbalance:
   Explore methods to handle class imbalance if present, as it could impact the model's ability to generalize.

### 4. Web Deployment:
   Develop a user-friendly interface to allow healthcare professionals to upload MRI images and receive predictions.

## Conclusion

This project showcases the successful implementation of a brain tumor detection model using CNN architectures, with the VGG16 model achieving an accuracy of 81%. The identified scope for future improvements offers avenues for enhancing model performance and applicability in real-world scenarios.


Feel free to contribute, provide feedback, or report issues!

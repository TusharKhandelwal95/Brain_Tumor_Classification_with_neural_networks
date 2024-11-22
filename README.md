# Brain Tumor Classification using Neural Networks

## Overview

This project is designed to classify brain tumor types from MRI scan images using deep learning models. The classification is done using two models:
1. **Transfer Learning - Xception**
2. **Custom CNN Model**

The app also provides a saliency map to visually highlight the areas in the image that contributed most to the prediction.

Additionally, the app leverages **Google Generative AI** for processing and provides insights into the classification.

## Key Features
- **Upload MRI Image:** Users can upload MRI scan images for prediction.
- **Model Selection:** Users can choose between two models:
  - Xception (Transfer Learning)
  - Custom CNN
- **Class Prediction:** The app predicts the type of brain tumor from the uploaded MRI scan, including four possible categories:
  - Glioma
  - Meningioma
  - No Tumor
  - Pituitary
- **Probability Display:** It displays the probabilities for each class.
- **Saliency Map:** The app generates a saliency map to highlight the regions of the MRI image responsible for the classification.
- **Explanation via Google Generative AI:** Provides an expert explanation based on the saliency map generated.

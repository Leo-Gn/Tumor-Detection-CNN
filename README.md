# Tumor-Detection-CNN
Tumor Detection and Classification from MRI Images Using a CNN Model



# Abstract 

The early diagnosis of brain tumors using Magnetic Resonance Imaging (MRI) is critical, while manual diagnosis is slow and variability will always exist. Convolutional Neural Networks (CNNs) have shown high accuracy in medical imaging, but the “black box” design limits clinical use in the real world because of the lack of transparency. This project aimed at addressing this concern while developing a highly accurate custom CNN model to classify glioma, meningioma, pituitary, and no tumor cases (7023 images) from MRI images and evaluate the results. In addition to classification accuracy, another goal of this project was to expand model explainability. To accomplish this, Gradient-weighted Class Activation Mapping (Grad-CAM) technique was incorporated to explain the model’s classifications in the form of heatmap overlays that show which regions of the image were most influential in the prediction. The model’s overall test accuracy was 96.19%, which was promising. The Grad-CAM work successfully produced heatmaps that had some insights into the classification process of the model, and had some reasonable localization of different classes, although there is always some variability in localization using this technique on custom CNN models. This project shows the potential for combining CNN-based classification with explainability approaches like Grad-CAM as a potential first step towards developing AI systems that healthcare professionals can trust and potentially use in a clinical setting.


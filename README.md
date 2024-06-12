# Visualize Activation Maps to Understand CNN Filters for Age Detection

This project aims to predict the age of individuals from images using a pre-trained ResNet50 model. We preprocess the dataset, train the model, and visualize the results using Grad-CAM.

## Project Details
- **Dataset**: UTKFace
- **Model**: ResNet50

## Dynamic Stats

- **Last Update**: {{last_update}}
- **Total Images Processed**: {{total_images}}
- **Test Loss**: {{test_loss}}
- **Test MAE**: {{test_mae}}

## Age Distribution Before Filtering
![Age Distribution Before](./images/age_distribution_before.png)

## Age Distribution After Filtering
![Age Distribution After](./images/age_distribution_after.png)

## Training & Validation Loss
![Model Loss](./images/model_loss.png)

## Grad-CAM Heatmaps
![Grad-CAM Heatmap 1](./images/gradcam1.png)
![Grad-CAM Heatmap 2](./images/gradcam2.png)
![Grad-CAM Heatmap 3](./images/gradcam3.png)

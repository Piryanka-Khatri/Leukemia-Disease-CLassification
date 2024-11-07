# Leukemia Classification - Image-based Model for Detection
This repository provides an implementation for the Leukemia Classification task, utilizing deep learning models to classify leukemia from medical images.

# Dataset Details:
Acute lymphoblastic leukemia (ALL) is the most common type of childhood cancer and accounts for approximately 25% of the pediatric cancers.

These cells have been segmented from microscopic images and are representative of images in the real-world because they contain some staining noise and illumination errors, although these errors have largely been fixed in the course of acquisition.

The task of identifying immature leukemic blasts from normal cells under the microscope is challenging due to morphological similarity and thus the ground truth labels were annotated by an expert oncologist.

In total there are 15,135 images from 118 patients with two labelled classes:

Normal cell;

Leukemia blast.

link: https://www.kaggle.com/datasets/andrewmvd/leukemia-classification/data

# Used Data Details:

Training Data: Images are organized into multiple folds for cross-validation.

Testing Data: Separate images that are not included in the training process for model evaluation.

# Key Features:
Preprocessing: Image transformations such as resizing, normalization, and data augmentation are applied to improve model generalization.

Model: ResNet18-based architecture fine-tuned for leukemia classification.

Performance Metrics: The model performance is evaluated using common metrics such as accuracy, precision, recall, F1 score, and confusion matrix.

Cross-Validation: The dataset is split into multiple folds to evaluate the model’s performance across different subsets of data.

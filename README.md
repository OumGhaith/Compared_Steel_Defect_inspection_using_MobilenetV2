# Compared_Steel_Defect_inspection_using_MobilenetV2
This repository contains the implementation of a comparative study for steel surface defect inspection using the MobileNetV2 convolutional neural network. The project focuses on analyzing steel sheet defects from images, providing a detailed pipeline for training, evaluation, and visualization. 

Features

K-Fold Cross-Validation: Implements 5-fold stratified cross-validation to ensure robust evaluation.

MobileNetV2 Fine-Tuning: Pretrained on ImageNet and fine-tuned on the steel defect dataset.

Performance Metrics: Accuracy, per-class accuracy, confusion matrix, precision, recall, and F1-score.

Visualization: Loss curves, well-classified and misclassified image samples, per-class accuracy bar charts, and confusion matrices.

Model Analysis: Reports total and trainable parameters, memory footprint, and average inference time per image.

Reproducibility: Saves models, weights, and the indices of train/validation splits for consistent evaluation.

Dataset

Dataset contains 1800 images divided into 6 defect classes:
crazing, inclusion, patches, pitted_surface, rolled-in_scale, scratches.

Images are resized to 224×224 and normalized for training.

Usage

Clone the repository.

Install dependencies: torch, torchvision, scikit-learn, matplotlib, seaborn.

Set paths to your train and test datasets.

Run the notebook to train MobileNetV2, evaluate, and visualize results.

Outputs

Trained model weights for the fold containing misclassified images.

Loss curves, confusion matrices, per-class accuracy charts.
all my works are here 
Pickled lists of misclassified and well-classified images.

Sample visualization of classified images for inspection.
find all my papers here 
https://www.researchgate.net/profile/Kateb-Yousra-2?ev=hdr_xprf&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJnbG9iYWxIZWFkZXIifX0

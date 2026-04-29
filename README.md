# Yoga Pose Quality Dataset

This repository contains the dataset files used in the study **"Video-Based Yoga Quality Assessment Using an Unsupervised BiLSTM Autoencoder with Temporal Attention."**

The dataset was prepared for unsupervised yoga pose quality assessment. It includes raw yoga videos, preprocessed joint-angle data, fixed-length sequence files, and dataset split files for training, validation, and testing.

## Contents

- `data_raw/`: original yoga videos used in this study
- `data_angles/`: frame-level joint-angle files extracted from the videos
- `data_sequences/`: fixed-length sequence files generated from the joint-angle data
- `splits/`: train, validation, and test split files
- `README.md`: dataset description

## Notes

The dataset focuses on three yoga poses: Bhujangasana, Trikonasana, and Vrikshasana.

Training and validation data contain only correctly performed yoga sequences. The test set includes both correct and incorrect executions. This setting supports unsupervised reconstruction-based pose quality assessment, where the model learns normal motion patterns from correct examples and evaluates deviations during inference.

## Contact

For questions, please contact Haoran He.

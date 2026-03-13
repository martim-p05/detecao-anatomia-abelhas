This repository contains the inference script and the trained model for the automatic detection of bee anatomical structures (Head, Abdomen, and Wings) in high-resolution photographs.

Base Architecture: YOLOv8

Training Dataset: 425 manually annotated images (split into Train, Validation, and Test).

Classes: cabeca (head), abdomen, asas (wings).

Precision (mAP50): ~95% on the test set.

At certain specific angles, the AI still experiences slight confusion.

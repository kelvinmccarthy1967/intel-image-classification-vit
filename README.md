# Intel Image Classification with Vision Transformer (ViT)

This project classifies images from the Intel Image Classification dataset into six categories:
**buildings, forest, glacier, mountain, sea, street**.

## Dataset
Intel Image Classification dataset (seg_train, seg_test, seg_pred).

## Approach
- Preprocessed images with OpenCV and resized to 224x224.
- Implemented Vision Transformer (ViT) from Hugging Face `transformers`.
- Trained with PyTorch achieving **~99% accuracy on training** and **~95% accuracy on test set**.
- Evaluated using classification report and visualized predictions.

## Repo Structure
📂 intel-image-classification-vit
├── notebooks/ (Jupyter notebooks)
├── requirements.txt
└── README.md

## Results
- Training Accuracy: 99.7%
- Test Accuracy: 94.9%

# Model Weights

This directory is intended to store the trained model weights for the **Robust Lightweight Tiny UAV Detection Using YOLO11** project.

## Trained Model

The final trained model is:

```text
best.pt
```

The model was trained using the **Ultralytics YOLO11** framework on a custom UAV detection dataset.

## Why is `best.pt` not included?

The trained model file is approximately **109 MB**, which exceeds GitHub's maximum file size limit of **100 MB** for a single file.

Therefore, the model weights are not included in this repository.

## How to Use

If you have the trained model, place it in this directory:

```text
weights/
└── best.pt
```

Update the notebook or inference script if a different path is required.

## Reproducing the Model

The complete training workflow is available in:

```text
notebooks/robust_lightweight_tiny_uav_detection.ipynb
```

Running the notebook allows you to reproduce the training process and generate your own `best.pt` model.

## Contact

If you require the trained model for academic or research purposes, please contact the repository owner.
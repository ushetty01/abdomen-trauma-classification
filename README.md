
# Abdominal Trauma Classification Using Deep Learning

**Medical Image Analysis · Deep Learning · Explainable AI**

A research project investigating deep learning approaches for classifying abdominal organ injury severity from CT imaging using the [RSNA 2023 Abdominal Trauma Detection dataset](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection).

The project explores organ-specific classification, CT image preprocessing, deep learning architectures, and explainable AI, with a focus on evaluating classification performance across different injury severity levels.

## Research Objectives

- Investigate deep learning methods for abdominal organ injury classification.
- Develop preprocessing pipelines for CT image analysis.
- Evaluate convolutional neural networks and transformer-based architectures.
- Explore class-imbalance handling and data augmentation.
- Investigate model explainability using Grad-CAM-based techniques.
- Evaluate the generalization of trained models across abdominal organs.

## Dataset

This project uses the [RSNA 2023 Abdominal Trauma Detection dataset](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection).

The dataset contains CT imaging data and associated injury annotations. Raw medical images and generated datasets are not included in this repository. Access and use are subject to the applicable dataset terms.

## Methodology

### CT Image Preprocessing

- CT slice selection and normalization.
- Image resizing, cropping, and contrast enhancement.
- Multi-slice image representations.
- Data augmentation to address class imbalance.

### Deep Learning Models

The research explores the following architectures:

- **DenseNet121**
- **Vision Transformer (ViT)**
- **EfficientNet-B0**

Standalone model implementations and supporting experiment code will be organized and documented as the repository develops.

### Explainable AI

Grad-CAM, Grad-CAM++, and Eigen-CAM are being explored to visualize image regions influencing model predictions.

These visualizations support model analysis but do not independently establish clinical validity.

## Repository Structure

The repository is being organized into the following components:

- `src/` — reusable preprocessing, model, training, and evaluation code.
- `notebooks/` — experimental notebooks and analysis.
- `configs/` — model and experiment configurations.
- `docs/` — methodology and technical documentation.
- `results/` — selected experimental outputs, when appropriate.
- `tests/` — tests for core components.

Only components that are ready for release will be included.

## Research Status

**Currently under development and being prepared for conference submission.**

This repository will initially contain selected model implementations and supporting documentation. The complete research implementation, ensemble methodology, detailed experimental results, and additional analysis are planned for a future release, subject to conference policies and applicable data-use requirements.

## Reproducibility

Documentation for environment setup, dataset preparation, model configurations, and evaluation procedures will be expanded as components are prepared for release.

## Citation

Citation information will be added when the associated research is published or otherwise made publicly available.

## License

A license will be added after reviewing the applicable code and dataset permissions.

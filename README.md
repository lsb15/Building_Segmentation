# Semantic_Segmentation
Individual Project

# Building Area Semantic Segmentation with DeepLabV3+

This repository contains code for performing semantic segmentation on the Massachusetts Buildings Dataset using the DeepLabV3+ architecture implemented in PyTorch. The segmentation_models_pytorch library is utilized for model implementation, and the Albumentations library is used for data augmentation.

## Installation

To install the required dependencies, run the following commands:

```bash
!pip install torch==1.7.1+cu110 torchvision==0.8.2+cu110 -f https://download.pytorch.org/whl/torch_stable.html
!pip install opencv-python pandas random2 seaborn numpy>=1.20.3 albumentations timm==0.9.5 pretrainedmodels==0.7.4
!pip install -q -U segmentation-models-pytorch albumentations > /dev/null
```

## Dataset

The dataset used for semantic segmentation tasks is the Massachusetts Buildings Dataset, which can be accessed from [this Kaggle link](https://www.kaggle.com/datasets/balraj98/massachusetts-buildings-dataset).

## Usage

1. Clone the Segmentation_Pytorch repository from GitHub:

```bash
git clone https://github.com/qubvel/segmentation_models.pytorch.git
```

2. Execute the provided Python scripts for model training, evaluation, and visualization. Ensure to set the appropriate dataset root directory (`${dataset_root}`) and file paths for model weights saving (`SAVE_WEIGHT`).


## References

- [Segmentation Models PyTorch GitHub Repository](https://github.com/qubvel/segmentation_models.pytorch)
- [Massachusetts Buildings Dataset on Kaggle](https://www.kaggle.com/datasets/balraj98/massachusetts-buildings-dataset)

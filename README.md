# AgriInsightML-Efficient-Crop-Health-Analytics with a Vision Transformer

## Introduction
Welcome to the repository for this Vision Transformer (ViT) project, which is aimed at analyzing the health of crops using cellphone [26k+](https://www.kaggle.com/datasets/mosbehbarhoumi/zindidata) images. Developed as part of an initiative to support smallholder farmers, this model processes images to identify various crop conditions. These insights are vital for assessing agricultural insurance claims and providing timely advisories.

## Getting Started

### Prerequisites
To run the notebook in this repository, you will need:
- Python 3.8+
- TensorFlow 2.x
- Jupyter Notebook or JupyterLab

### Usage

To use the Vision Transformer for crop health analysis, follow these steps:

1. Launch Jupyter Notebook or JupyterLab:
2. Open the `mk-vit.ipynb` notebook within the Jupyter interface.
3. Execute the notebook cells to train and evaluate the model.

## Model Overview

The `mk-vit.ipynb` notebook guides you through the entire machine learning pipeline, including data preprocessing, model training, evaluation, and making predictions. It uses the Vision Transformer architecture, which has proven effective in various image classification tasks.

## Repo structure
- `MK-DL.ipynb` notebooks for data exploration, training models 
- `/images/images/`: input data (images are not included due to size constraints and can be downloaded [here](https://www.kaggle.com/datasets/mosbehbarhoumi/zindidata))
- `/images/`: CSV image file with crop damage data classes

## Working with the repo
### Reproducing solution

The following steps can reproduce the solution:

1. Download the image dataset and add it to the `/images/images/` folder.
2. Running notebook cells in ascending order to create the U-Net Model and initial base models.
3. Add a CSV image file with crop damage data classes to the `/images/` folder.


More details are provided in the notebook documentation.

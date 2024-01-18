# Segmentation Border Analysis with GradCAM

## Description
This repository publishes the code used to create the GradCAM border analysis presented in the IPCAI 2024 Paper "Ultrasound Segmentation Analysis via Distinct and Completed Anatomical Borders".
It also includes the network architectures and weights of the pretrained models which were subject to the analyzation: UNet, Attention UNet and UNet Transformer, as well as an example image with its corresponding labels (including a full label as well as the distinct- and completed-border labels) for both examined ultrasound datasets: the leg muscle dataset and the thyroid dataset.

## Usage
1. Clone this repository on your local machine. Note that the example data and network weights are uploaded using Git Large File Storage (git lfs). You might need to install it first (see [Installation Guide](https://git-lfs.com)) to correctly clone the repo. 
2. Execute the Jupyter Notebook border-analysis.ipynb. You may adjust the code to your own data and networks at the designated points.

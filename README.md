# Segmentation Border Analysis with GradCAM

## Description
This repository publishes the code used to create the GradCAM border analysis presented in the IPCAI 2024 Paper "Ultrasound Segmentation Analysis via Distinct and Completed Anatomical Borders".
It also includes the network architectures and weights of the pretrained models which were subject to the analysis: UNet, Attention UNet and UNet Transformer, as well as an example image with its corresponding labels (including a full label as well as the distinct- and completed-border labels) for both examined ultrasound datasets: the leg muscle dataset and the thyroid dataset.

<img width="932" alt="image" src="https://github.com/Al3xand1a/segmentation-border-analysis/assets/98582325/c2e61b48-4242-4e24-bbd8-2a6aaffcc10a">



## Usage
1. Clone this repository on your local machine. Note that the example data and network weights are uploaded using Git Large File Storage (git lfs). You might need to install it first (see [Installation Guide](https://git-lfs.com)) to correctly clone the repo. 
2. Execute the Jupyter Notebook border-analysis.ipynb. You may adjust the code to your own data and networks at the designated points.

## Data
The ultrasound dataset of leg muscles published along with our paper can be found and downloaded [here](https://www.cs.cit.tum.de/camp/publications/leg-3d-us-dataset/). Details about its contents, data aquisition and processing can be found in the corresponding datasheet provided in this repository.
The example leg volume and label used in this repository is part of this dataset, while the labels for distinct and completed borders are computed based on the full label as described in the paper.
The example thyroid data comes from [this dataset](https://www.cs.cit.tum.de/camp/publications/segthy-dataset/).

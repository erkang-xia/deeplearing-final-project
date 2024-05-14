## Project README

### Text Detection and Image Processing with Neural Networks

This repository hosts the Jupyter notebooks for detecting text areas in images, applying blur to obscure them, and subsequently restoring the original appearance using advanced neural network models. Below are the details and resources you need to effectively utilize the provided models.

#### Notebooks Overview

- **CGAN for Image Un-Distortion (`cgan-for-image-un-distortion.ipynb`)**: This notebook contains the implementation of the Conditional Generative Adversarial Network (CGAN) designed to detect and blur text regions in images and then restore them to their undistorted state. Access the original notebook along with all image data at this Kaggle link: [CGAN for Image Un-Distortion](https://www.kaggle.com/code/erkangdeermusik/cgan-for-image-un-distortion).

- **Partial Convolution Inpainting (`partial-convolution-inpainting.ipynb`)**: Here, you will find the model setup for the Partial Convolution based network, designed for image restoration. The notebook includes access to all used image databases and checkpoint files. Visit the Kaggle page here: [Partial Convolution Inpainting](https://www.kaggle.com/code/erkangxia/partial-convolution-inpainting).

#### Model Checkpoints and Data

- **CGAN Checkpoints**:
  - To find the latest checkpoints for the CGAN model, please check the version control logs on the respective notebook page. You can click the above link directly. it should take you to the kaggle repo.  If needed, a previous checkpoint(not the latest, you need to go to kaggle notebook log to find the latest check point, notebook is public) for the CGAN model (Image blur to clear, undistortion) can be found here: [CGAN Checkpoint for Blur to Clear](https://www.kaggle.com/datasets/erkangdeermusik/checkpointforcganblurtoclear).
  - Another relevant checkpoint (Image text detector and blur) can be accessed here(not the latest, you need to go to kaggle notebook log to find the latest check point, notebook is public): [CGAN Checkpoint for Image to Blur](https://www.kaggle.com/datasets/erkangxianyu/checkpointforcganwithwhite/data).

- **Partial Convolution Checkpoints**:
  - Checkpoints for the Partial Convolution model are detailed in the settings of the Kaggle dataset. For the most recent updates, refer to the version control logs. A reference to an older checkpoint is available here: [Checkpoint for Partial Conv](https://www.kaggle.com/datasets/erkangxia/checkpoint-for-patialconv100/settings).

#### Usage Instructions

For running the notebooks:
1. Ensure you have the necessary computational resources and libraries installed.
2. Follow the links provided to download the required datasets and checkpoints.
3. Open the notebooks via Kaggle or a compatible Jupyter environment on your local machine or cloud platform.


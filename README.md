# Medical Image Segmentation with M-Net

This repository contains my implementation of an **M-Net** architecture for 3D medical image segmentation, developed for the Deep Learning course at the University of Tehran.

The project uses the **IBSR dataset** to segment anatomical structures from T1-weighted MRI scans.



## Overview

* **Architecture:** Custom PyTorch implementation of M-Net using 2D convolutions (`Conv2d`).
* **Dataset:** Handled via a custom `IBSRPatchDataset` loader for NIfTI formats. 
* **Pipeline:** Includes complete training, validation, and visual evaluation routines.



## Results
*Check the notebook for detailed loss curves and visual comparisons between predictions and ground truth masks.*



## References

The methodology and concepts applied in this project were inspired by the following research paper:

- [Using a patch-wise M-net convolutional neural  network for tissue segmentation in brain MRI  images](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9130719) by Nagaraj Yamanakkanavar and Bumshik Lee, 2020.


# Turbulence Optical Images Dataset

## Introduction

This repository contains datasets for research on turbulence removal / optical image restoration based on image sequences. The datasets include numerically simulated turbulence-degraded optical image sequences and real-captured turbulence optical image sequences. These data are intended to support the development and performance evaluation of algorithms in related fields, such as image restoration, object tracking, turbulence effect analysis, and machine learning model training.

## Dataset Details

* **Location:** All data files are expected to be stored in the `data/` directory or its subdirectories.
* **Composition:**
    * **Simulated Data:** Originating from 800 groups of original clear image sequences ($U = \{u_1, u_2, \ldots, u_{800}\}$) and their corresponding numerically simulated turbulence-degraded image sequences ($Z = \{z_1, z_2, \ldots, z_{800}\}$).
        * Training Set: Contains 572 image sequence groups.
        * Test Set: Contains 228 image sequence groups.
    * **Real Data:** Contains 200 groups of real-captured optical image sequences under the influence of turbulence, which can be used for algorithm validation.

## Environment and Dependencies

* **Git LFS (Required):** This repository plans to use Git Large File Storage (LFS) to manage large data files. **Before cloning or downloading this repository, please ensure you have installed Git LFS. Otherwise, for files managed by LFS, you will download invalid pointer files instead of the actual image data!**
    * Installation and setup guide: [https://git-lfs.github.com/](https://git-lfs.github.com/)
    * After installation, please run `git lfs install` in your terminal to initialize LFS.
* **Cloning the Repository:**
    ```bash
    # Ensure Git LFS is installed before executing
    git clone [https://github.com/luyijie1222/turbulence-optical-images.git](https://github.com/luyijie1222/turbulence-optical-images.git)
    ```

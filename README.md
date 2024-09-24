# DSP Final Project: Circle Detection in Images

This project was completed as part of the Digital Signal Processing (DSP) course . The primary goal of the project is to detect circles in images, which is a common task in image processing, such as identifying circular objects like cells in microscopy images.

## Project Overview

The project focuses on implementing two different approaches to detect circles in images:

1. **Known Radius**: The task is to detect circles with a predefined radius in the image, ignoring circles of other sizes.
2. **Unknown Radius**: The task is to detect all circles in the image, regardless of their size.

The project is divided into four main parts:
- **Direct Correlation**: Uses direct correlation to find circles with a known radius.
- **DFT-based Correlation**: Applies DFT (Fast Fourier Transform) to optimize circle detection.
- **Derivative-based Correlation**: Uses image derivatives to enhance circle detection.
- **Gradient Vector Pairs**: Detects circles with unknown radii using a method based on gradient vector pairs.

## Project Files

1. **Main File**: `main.m`
   - This is the main script to run the project. By modifying the `Part_Enable` parameter (values: `A1`, `A2`, `A3`, `B`), different parts of the project can be executed.

2. **Subroutines Folder**: Contains the necessary subroutines to perform the various circle detection methods.

3. **Functions Folder**: Contains key functions to be completed for the project:
   - `direct_correlator.m`
   - `fft2_correlator.m`
   - `circle_locator.m`

4. **Results Folder**: Generated results are stored here after running the scripts.


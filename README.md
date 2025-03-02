# VR Assignment : Coin Segmentation and Panoramic Image Stitching

# Overview

This project consists of two parts:

- **Coin Detection, Segmentation, and Counting**: Uses computer vision techniques to detect, segment, and count Indian coins from an image.
- **Panorama Creation**: Stitches multiple overlapping images into a seamless panorama.

## Requirements

```bash
git clone https://github.com/nathanmathewv/VR_Assignment1_NathanMathew_IMT2022022.git
cd VR_Assignment1_NathanMathew_IMT2022022
```

## Part 1

### Features
- Detects coins using edge detection.
- Segments each detected coin using contour analysis and removes unwanted noisy detections.
- Counts the total number of coins.

### Running the code
Run the Python Notebook and see the results on the notebook itself, or see the results on the output directory.

### Input
The `input` directory has 3 different images of coins, one having different number as well.

### Output
The `output` directory has the 3 images with edges highlighted on the coins. It also has images named `segmented_x_y.jpg` which are the segmented coins.

## Part 2

### Features
- Detects and visualises key points using SIFT.
- Matches the key points between overlapping images.
- Aligns and stitches these images using homography.

### Running the code
Run the Python Notebook and see the results on the notebook itself, or see the results on the output directory.

### Input
The `input_x` directory has 3 different images of an outdoor area. The perspective is also lightly changed in one of the diretories.

### Output
The `output` directory has the stitched image, named `stitched_panorama.jpg`.

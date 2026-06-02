# Image Processing using Scikit-Image

A Python project demonstrating fundamental image processing techniques using **NumPy**, **Matplotlib**, and **Scikit-Image**.

## Features

* Generate random grayscale images
* Create grayscale intensity gradients
* Generate RGB color images
* Read and display images
* Visualize RGB channels separately
* Convert color images to grayscale
* Perform manual grayscale conversion
* Apply image thresholding
* Use Otsu's automatic threshold selection
* Detect edges using Sobel operator
* Detect edges using Canny Edge Detection

## Technologies Used

* Python 3
* NumPy
* Matplotlib
* Scikit-Image

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/image-processing-scikit-image.git
cd image-processing-scikit-image
```

Install dependencies:

```bash
pip install numpy matplotlib scikit-image
```

## Project Structure

```text
image-processing-scikit-image/
│
├── images/
│   ├── parrot_rosellaMacaws_couple.jpg
│   └── flower_dahlia_orange.jpg
│
├── image_processing.py
├── requirements.txt
└── README.md
```

## Concepts Covered

### 1. Grayscale Images

Images represented as 2D NumPy arrays where pixel values range from 0–255.

### 2. RGB Images

Color images consist of three channels:

* Red (R)
* Green (G)
* Blue (B)

### 3. Grayscale Conversion

Uses the luminance formula:

```python
Gray = 0.2126*R + 0.7152*G + 0.0722*B
```

### 4. Thresholding

Separates foreground and background based on pixel intensity values.

### 5. Otsu Thresholding

Automatically computes the optimal threshold value for image segmentation.

### 6. Sobel Edge Detection

Detects image gradients and highlights object boundaries.

### 7. Canny Edge Detection

Advanced edge detector with noise reduction and automatic thresholding.

## Sample Output

* Random grayscale image
* Gradient image
* RGB channel visualization
* Grayscale conversion
* Thresholded image
* Otsu threshold result
* Sobel edge detection
* Canny edge detection

## Author

**Vanshika Maheshwari**

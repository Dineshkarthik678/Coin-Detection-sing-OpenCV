# Coin-Detection-sing-OpenCV

## Overview

This project demonstrates coin detection and counting using OpenCV and image processing techniques. The system identifies coins present in an image, detects their boundaries, and calculates the total number of coins automatically.

## Features

- Image preprocessing
- Grayscale conversion
- Noise reduction using Gaussian Blur
- Edge detection
- Contour detection
- Coin counting
- Visualization of detected coins

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## Methodology

1. Load the input image.
2. Convert the image to grayscale.
3. Apply filtering to remove noise.
4. Detect edges using image processing techniques.
5. Find contours corresponding to coins.
6. Draw circles/boundaries around detected coins.
7. Count the total number of detected coins.
8. Display the output image and count.

## Sample Output

```
Number of Coins Detected: 5
```

Detected coins are highlighted with circles or contours in the output image.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/coin-detection-opencv.git
```

Install required packages:

```bash
pip install opencv-python numpy matplotlib
```

## Usage

1. Open the notebook:

```bash
jupyter notebook
```

2. Run:

```bash
Coin-Detection-workfile.ipynb
```

3. Provide an image containing coins.

4. View the detected coins and total count.

## Applications

- Automated Coin Counting
- Banking Systems
- Vending Machines
- Currency Recognition
- Computer Vision Learning Projects

## Future Enhancements

- Coin denomination recognition
- Real-time webcam detection
- Support for multiple currencies
- Deep learning-based classification

## Author

**DINESH KARTHIK R**

## License

This project is licensed under the MIT License.

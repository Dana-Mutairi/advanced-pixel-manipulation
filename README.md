# Advanced Pixel-Level Manipulation

An image-processing project demonstrating direct pixel-level manipulation using NumPy, Pillow (PIL), and OpenCV in Google Colab.

[Open the notebook in Google Colab](https://colab.research.google.com/github/Dana-Mutairi/advanced-pixel-manipulation/blob/main/Assignment_1_Advanced_Pixel_Manipulation.ipynb)

## Project Objective

This project practices image manipulation at the array level. It loads and inspects two images, transfers a randomly selected 30 × 30 pixel region between them, converts the results to grayscale, and applies a custom sharpening filter.

## Project Steps

1. Load, inspect, and display two images.
2. Convert the images into NumPy arrays.
3. Generate a valid random coordinate.
4. Crop a 30 × 30 region from Image 1.
5. Paste the crop into Image 2 to create Image 3.
6. Convert Image 1, Image 2, and Image 3 to grayscale.
7. Apply a custom 3 × 3 sharpening kernel to Image 3.
8. Display and save the results.

## Technologies

- Python
- Google Colab
- NumPy
- Pillow (PIL)
- OpenCV
- Matplotlib

## Repository Structure

```text
advanced-pixel-manipulation/
├── Assignment_1_Advanced_Pixel_Manipulation.ipynb
└── README.md
```

## How to Run

1. Open the notebook using the Colab link above.
2. Upload the two JPG images to the Colab session.
3. Ensure their filenames match those used in the notebook.
4. Select **Runtime → Run all**.
5. Review the displayed and saved results.

> Files uploaded to a Colab session are temporary and must be uploaded again when starting a new runtime.

## Learning Outcomes

This project demonstrates:

- Pixel-level matrix manipulation
- NumPy array slicing
- Random-coordinate generation
- RGB-to-grayscale conversion
- Image copying and region replacement
- Custom convolution-kernel filtering
- Structured notebook documentation

## Training Acknowledgment

This project was completed as part of Computer Vision training coursework. Appreciation is extended to [SDAIA Academy](https://github.com/SDAIAAcademy) for supporting technical learning and open-source project development.

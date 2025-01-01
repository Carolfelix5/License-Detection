# License Plate Detection and Blurring

This project demonstrates the detection and blurring of license plates in car images using OpenCV's Haar cascades. It is designed to preserve privacy by obscuring sensitive information within the images.

## Features

- Load and display car images using OpenCV.
- Detect license plates using the `haarcascade_russian_plate_number.xml` file.
- ![car](https://github.com/user-attachments/assets/c050a9ea-9e83-4a0c-a1ca-137aa0ae92fc)
- Blur detected license plates for privacy.

### How to Run
1. Open the Detection.ipynb notebook in Jupyter Notebook.
2. Execute the cells in order to:
   - Load and display a sample car image.
   - Detect the license plate in the image.
   - Blur the detected license plate.
3. View the results in the output cells of the notebook.

### Key Functions
- detect_plate(image): Detects license plates in the given image using Haar cascades.
- detect_and_blur_plate(image): Combines detection and blurring functionality for privacy preservation.

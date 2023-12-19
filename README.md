# License Plate Recognition System

## Introduction

This repository contains a Python script for license plate recognition using computer vision. The script is designed to work in Google Colab, making it convenient for cloud-based image processing.

## Requirements

To run the script, you need:

- Google Colab account
- Image with a visible license plate (e.g., JPEG format)

## Instructions

1. **Upload Your Image:**
   - Upload your image file (e.g., `your_image.jpg`) to your Google Drive or directly to Google Colab.

2. **Run the Code:**
   - Open the `License_Plate_Recognition.ipynb` notebook in Google Colab.
   - Replace `'your_image_path.jpg'` with the actual path to your uploaded image.
   - Execute the cells one by one.

3. **View Results:**
   - The script will display the original image with the detected license plate bounding box.
   - Additionally, the extracted license plate region will be shown.

## Example

```python
# Replace 'your_image_path.jpg' with the path to your image
find_license_plate('/content/your_image.jpg')
```

## Input Image

![Input Image](/input.jpg)

## Output Image

![Output Image](/output.png)

**Note:** Make sure to replace `'your_image.jpg'` with the actual name of your image file.






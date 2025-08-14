# Elevate-Labs-Task-7
Image Resizer Tool

A simple Python script to resize images using the Pillow library.

## Features

- Resize single images to specified dimensions
- Supports common image formats (PNG, JPEG, etc.)
- Maintains image quality with LANCZOS resampling
- Automatic output directory creation

Resize a single image and save it to the specified output path.
Parameters:
1. input_file (str): Path to the input image file(Input image of dimensions: 1024 x 1536)
2. output_file (str): Path to save the resized image(Output image of dimensions: 800 x 600)
3. new_size (tuple): Target dimensions (width, height)
4. quality (int): Quality for JPEG (1-100)
5. format (str): Output format ('PNG', 'JPEG', etc.)

Returns:  bool: True if successful, False otherwise

# Resize Images with PIL

This Python script allows users to resize images using the Pillow library (PIL). Users can specify the desired width and height, and the script will resize and save the image accordingly.

## Features
- Resize images to custom dimensions
- Supports various image formats (JPG, PNG, BMP, GIF, etc.)
- Handles invalid file paths gracefully

## Requirements
- Pillow library

## Installation
1. Install Python 3 if not already installed.
2. Install Pillow using pip:
   ```sh
   pip install pillow
   ```

## Usage
1. Run the script:
   ```sh
   python resize_image.py
   ```
2. Enter the full path of the image when prompted.
3. The resized image will be saved to the specified output path.

## Example
```python
resize_image("output.jpg", 300, 300)
```

## License
This project is licensed under the MIT License.

## Contributing
Feel free to submit pull requests for improvements or bug fixes.


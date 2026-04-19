
# Computer Vision Assignment: Document Scanner & Image Processing

This project contains a series of computer vision tasks implemented in a Jupyter Notebook using Python, OpenCV, and Matplotlib. The primary focus is on developing a document scanner workflow, including image preprocessing and morphological cleanup.

## Tasks Included

### Task 1: Document Scanner with Morphological Cleanup
This task demonstrates the process of transforming a raw photo of a document (e.g., a receipt) into a clean, scanned version. Key steps involved:
* **Image Loading and Color Conversion**: Reading images using OpenCV and converting them from BGR to RGB for proper display with Matplotlib.
* **Preprocessing**: Applying color transformations and noise reduction to prepare the image for scanning.
* **Morphological Operations**: Utilizing cleanup techniques to refine document edges and remove artifacts.

## Technologies Used
* **Python**: Core programming language.
* **OpenCV (cv2)**: Used for image reading, color space conversion, and computer vision algorithms.
* **NumPy**: Employed for efficient numerical array manipulations.
* **Matplotlib**: Used for visualizing the original and processed images.
* **Google Colab Patches**: Includes `cv2_imshow` for displaying images within the Colab environment.

## Getting Started
1. Open the notebook in **Google Colab** or a local Jupyter environment.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install opencv-python matplotlib numpy
   ```
3. Place the required input image (e.g., `receipt.jpg`) in the `/content/` directory or update the path in the code.
4. Run the cells sequentially to observe the transformation from the original image to the cleaned output.

# Image Binarization Techniques with OpenCV

## Problem Statement and Goal of Project

This project explores fundamental image binarization techniques using OpenCV. The primary goal is to convert grayscale images into binary (black and white) images by applying various thresholding methods. This is a crucial preprocessing step in many computer vision tasks, as it simplifies image analysis by separating objects from the background. The notebook also serves as a practical demonstration of my ability to implement and explain these core concepts.

## Solution Approach

I implemented several thresholding techniques to demonstrate their effects on different types of images. The approaches include:

  * **Simple Binary Thresholding**: Manually setting a threshold value (e.g., 127) to segment the image. Pixels below this value are set to black (0), and pixels above are set to white (255).
  * **Otsu's Method for Automatic Thresholding**: An adaptive technique that automatically determines the optimal threshold value by analyzing the image's histogram to minimize intra-class variance.
  * **Interactive Thresholding Demo**: A user-friendly application with a trackbar to dynamically adjust the threshold value and type, providing immediate visual feedback on how these parameters affect the output.

## Technologies & Libraries

  * **OpenCV**: For core image processing and computer vision functionalities.
  * **NumPy**: For efficient numerical operations and array manipulation.
  * **Matplotlib**: For plotting and visualizing images within the notebook.

## Description about Dataset

The project uses a small set of sample images (`gradient.jpg`, `Lusin-1.jpg`, and `plate.jpg`) to illustrate the different thresholding methods. These images were chosen to showcase how each technique performs under varying conditions (e.g., gradients, real-world objects).

## Installation & Execution Guide

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/imehranasgari/Image-Binarization-OpenCV.git
    ```
2.  **Install the required libraries:**
    ```bash
    pip install opencv-python numpy matplotlib
    ```
3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook binarization.ipynb
    ```

## Key Results / Performance

This project is intended to demonstrate conceptual understanding rather than achieving high performance metrics. The key results are the visual outputs that clearly show the differences between various thresholding methods. The inclusion of both manual and automatic (Otsu's) thresholding highlights my ability to select the appropriate tool for a given problem. The interactive demo further showcases my skills in creating practical, user-friendly applications.

## Screenshots / Sample Output
![alt text](dc3a6605-59ef-4a06-ba05-145b18382264.png)
![alt text](a735d2dd-f855-4f8e-a370-55cb2b593b0e.png)
![alt text](9bcc8167-e7d5-4d57-9ddc-3f3383a497c6.png)
![alt text](c80cadd6-ebc4-4e51-bb72-b9a86874873f.png)
![alt text](bd6e71a8-0bec-4377-ab26-1884cdabf7bf.png)
![alt text](edd9975a-9646-42bc-a38c-e5e078085d45.png)
![alt text](3047cb58-dabe-42fc-9093-f2260a422c3d.png)
![alt text](86b866be-07ae-479b-9ec1-b180c9f9e767.png)
![alt text](ec982937-1921-4f27-8ef9-ef50d891cfc7.png)
![alt text](25dda00e-51c8-40d6-b49d-26e1c0e0d89e.png)
![alt text](81eeb528-a3d4-4ab5-ad01-b58a3c0fc7cb.png)
![alt text](d6ce5e3f-7cef-440c-b1c3-9c99df93a61f.png)
![alt text](29b18637-3e15-45ef-b9d3-9cbcc1742b46.png)
![alt text](1ac186f7-9e95-4f10-bbcc-cf41d839562a.png)
![alt text](145c6349-76b0-4147-898b-7e2c8fdc9d98.png)
![alt text](cbf996cb-aaf2-4ed1-91f5-aa1d756cebc1.png)
![alt text](37ab1616-d18a-4e53-9711-9fea4b2d89a1.png)
![alt text](59a8deb4-c0b5-42c4-bf53-080daa003932.png)
![alt text](121ce374-718b-4efb-90aa-1c3b3dc1ee6e.png)
![alt text](2521739c-3067-41ea-a36b-1e1de5c6f256.png)
![alt text](0feb4233-759e-4593-878d-d8bedb21c940.png)


## Additional Learnings / Reflections

This project reinforced my understanding of image binarization as a critical first step in many computer vision pipelines, such as object detection and optical character recognition (OCR). By implementing both simple and adaptive thresholding methods, I gained a deeper appreciation for the trade-offs between manual control and automated, data-driven approaches like Otsu's method. This exploration serves as a solid foundation for tackling more complex image segmentation challenges.

-----

## 🙏 Acknowledgments

This project represents my initial steps into the practical application of computer vision. The foundational knowledge and guidance for this work were derived from the outstanding OpenCV course taught by **Alireza Akhavanpour** on the **Maktabkhooneh** platform. His ability to deconstruct complex topics into clear, actionable steps was instrumental in the successful implementation of this project.

-----


## 👤 Author

## Mehran Asgari

## **Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com).

## **GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari).

-----

## 📄 License

This project is licensed under the Apache 2.0 License – see the `LICENSE` file for details.

💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

-----

# **Task 06: Frequency Domain Filtering**

**Roll Number:** 2023-SE-06

### **Prompt**

*"Write a complete Python program using NumPy, OpenCV, and Matplotlib, fully compatible with Google Colab, to demonstrate Frequency Domain Filtering in Digital Image Processing. The program should perform the following tasks step by step:

* Allow the user to upload two grayscale images using Google Colab.
* Display both original images clearly.
* Apply 2D Fourier Transform (FFT) to each image and shift the zero frequency component to the center.
* Design a Low-Pass Filter mask and a High-Pass Filter mask in the frequency domain.
* Apply the low-pass and high-pass filters separately to each image in the frequency domain.
* Perform Inverse Fourier Transform (IFFT) to obtain low-frequency and high-frequency images.
* Display the results in a well-organized comparison layout, showing low-frequency and high-frequency components for both images.
* Include a short analysis section explaining the difference between low-frequency and high-frequency components and their significance.
* Ensure the code is clean, well-commented, logically structured, error-free, and suitable for direct lab submission."*

---

## **Objective**

The objective of this task is to analyze images in the **frequency domain** by separating **low-frequency** (smooth regions) and **high-frequency** (edges and details) components using Fourier Transform techniques. This demonstrates the importance of frequency analysis in image processing.

---

## **Methodology / Approach**

1. Upload **two grayscale images** in Google Colab using `files.upload()` and display them.
2. Apply **2D Fourier Transform (FFT)** to each image and shift the zero frequency component to the center for visualization.
3. Design a **Low-Pass Filter (LPF)** mask to retain smooth, low-frequency information.
4. Design a **High-Pass Filter (HPF)** mask to retain edges and high-frequency details.
5. Apply the LPF and HPF masks separately in the frequency domain.
6. Perform **Inverse FFT (IFFT)** to reconstruct images in the spatial domain for both low-frequency and high-frequency components.
7. Display the low-frequency and high-frequency results for both images side by side.
8. Provide analysis explaining the significance of low and high frequency information in images.

---

## **Results / Observations**

* **Low-frequency images** contain smooth regions, overall intensity, and coarse structures.
* **High-frequency images** highlight edges, fine details, and rapid intensity changes.
* Fourier Transform effectively separates spatial information into frequency components, allowing targeted filtering.
* Comparison of low and high frequency images demonstrates the complementary nature of spatial and frequency domain processing.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **NumPy (np):** FFT, IFFT, and frequency domain operations
* **OpenCV (cv2):** Image reading and conversion
* **Matplotlib (plt):** Visualization of original, low-frequency, and high-frequency images
* **Google Colab:** Image upload and execution environment

---

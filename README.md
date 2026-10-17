# NumPy Image Manipulation & Processing Projects

A collection of two beginner-to-intermediate Python projects built using **NumPy and Matplotlib in Google Colab**. These projects explore how digital images can be represented as arrays and manipulated using efficient numerical operations.

##  Projects Overview

### Project 1: Image Pixel Manipulator (Synthetic Images)

**Notebook:** `Image_Pixel_Manipulator.ipynb`

#### About
This project demonstrates how digital images can be created and manipulated using NumPy arrays. A synthetic RGB image is generated from scratch, and different image-processing operations are performed without relying on dedicated image-editing libraries.

#### Features
- Create synthetic RGB images using NumPy.
- Draw colored blocks and stripes using 3D array slicing.
- Crop and flip images using array slicing.
- Extract individual Red, Green, and Blue (RGB) channels.
- Adjust image brightness using `float32` and `uint8` data types.
- Identify bright pixels using Boolean masking.
- Compare memory usage for different data types.
- Visualize images and results using Matplotlib.

#### Key Concepts
`np.zeros()`, `np.full()`, array slicing, RGB arrays, `astype()`, data types, Boolean masking, `nbytes`, and image visualization.

---

###  Project 2: NumPy Image Processing Toolkit

**Notebook:** `NumPy_Image_Processing_Toolkit.ipynb`

#### About
This project treats an image as a multidimensional NumPy array and applies common image-processing operations to a built-in sample photograph. It demonstrates how arrays can be transformed and combined efficiently without explicit pixel loops for the main operations.

#### Features
- Load a built-in sample photograph using `scikit-image`.
- Convert a colorful RGB image into grayscale.
- Flip images horizontally and vertically.
- Rotate images by 90 degrees.
- Split and visualize individual RGB channels.
- Create a 2 × 2 image collage using NumPy array operations.
- Compare vectorized grayscale conversion with pixel-by-pixel loops.
- Measure execution time and visualize the performance comparison.

#### Key Concepts
`np.stack()`, `np.concatenate()`, `np.rot90()`, `np.fliplr()`, `np.flipud()`, array slicing, broadcasting, vectorization, and execution-time measurement.

---

##  Technologies Used

- **Python** — programming language
- **NumPy** — numerical computing and array manipulation
- **Matplotlib** — image visualization and charts
- **scikit-image** — built-in sample photograph for the Image Processing Toolkit
- **Google Colab** — cloud-based Python notebook environment

##  How to Run the Projects

1. Open [Google Colab](https://colab.research.google.com/).
2. Open the required `.ipynb` notebook from this repository.
3. Select **Runtime → Run all** to execute the notebook cells in order.
4. View the generated images, transformations, collages, and performance results.

No manual image upload is required for the Image Processing Toolkit because it uses a built-in sample photograph.

##  What I Learned

Through these projects, I practised:

- Representing images as multidimensional arrays.
- Understanding image dimensions, RGB channels, and pixel intensities.
- Applying NumPy slicing, indexing, stacking, and concatenation.
- Working with numerical data types and memory usage.
- Using Boolean masks for conditional pixel selection.
- Performing vectorized operations instead of explicit pixel loops.
- Visualizing results and comparing execution times.

##  Objective

The goal of these projects is to strengthen my understanding of Python, NumPy arrays, and fundamental image-processing techniques through practical, hands-on implementation.

##  Author

**Jahanvi Khandve**

Computer Science Engineering Student


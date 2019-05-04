# Seam Carving for Content-Aware Image Resizing

## Synopsis

Computational photography code to replicate the published results of [Seam Carving for Content-Aware Image Resizing](http://www.faculty.idc.ac.il/arik/SCWeb/imret/index.html) by Shai Avidan and Ariel Shamir. Three aspects of their research were replicated:

  - Seam removal (Figure 5)
  - Seam insertion (Figure 8)
  - Optimal retargeting with dynamic programming (Figure 7)

## Requirements

Code was written with Python 3.5.6 in a Jupyter Notebook. Required libraries include:

  - OpenCV 4.0.0.21
  - Numpy 1.15.2
  - Matplotlib 3.0.0

## Results

### Seam removal
Reduce the 466 pixel x 700 pixel image to 466 pixels x 350 pixels

**Original**
![Original](images/fig5.png?raw=true)

**Resized**
![Resized](images/fig5out/fig5_resized.png?raw=true)

### Seam insertion
Increase the width of the original image 50%

**Original**
![Original](images/fig8.png?raw=true)

**Resized with seams**
![Resized](images/fig8out/resize_1_with_seams.png?raw=true)

**Resized**
![Resized](images/fig8out/resize_1.png?raw=true)

### Optimal Retargeting with Dynamic Programming
Reduce the 255 pixel x 350 pixel image to 150 pixels x 165 pixels

**Original**
![Original](images/fig7.png?raw=true)

**Transport map**
![Resized](images/fig7out/t_map_color_w_seam.png?raw=true)

**Resized**
![Resized](images/fig7out/fig7_resized.png?raw=true)

# Boundary Detection using Probability of Boundary approach
Boundary detection is an important and well-studied computer vision problem. A simple way to detect boundaries in an image is to look for intensity discontinuities witin the image (also known as edges). The classical edge detection algorithms such as Canny and Sobel algorithms use the aforementioned procedure.

The more recent pb (**probability of boundary**) detection algorithm significantly outperforms these methods by incorporating texture and colour discontinuities in addition to the intensity discontinuity. The aim of this project is to implement a simplified version of the the Probability of Boundary approach, namely the pb-lite approach.

## Instructions to run the code
- cd into the directory where the file Wrapper.py is placed and execute the command > python Wrapper.py

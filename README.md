# Quadcopter image processing project
## Overview
In this project, images are collected with a Parrot Mambo Minidrone and algorithms for red color detection, circle detection, and chessboard coordinates determination are developed.
See https://sites.google.com/umich.edu/eecs351project/home for more details.
## Features
* ### Red color detection
  This algorithm segments out the red portion and determines whether there is a significant presence of the red color in the input image.
* ### Circle detection
  This algorithm finds the circles in the input image.
* ### Chessboard coordinates determination
  This algorithm determines whether there exists an identifiable chessboard in the input image and, if it exists, determines and labels the coordinates (a1 to h8) of the 64 chess squares in the input image.
## Dependencies
Only MATLAB and its Image Processing Toolbox are required for this project.
## Running this project
To run this project, simply put all the MAT-files and MLX-files in this repository into the same directory and open the MLX-files to run the demo scripts.

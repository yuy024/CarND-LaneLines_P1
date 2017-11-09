# CarND-LaneLines_P1
First project of Self-Driving car nano-degree term1.

The goal of this project is to detect lane lines in a video clip. 

The algorithm starts from
1. transform the image into grayscale.
2. blur the image to get rid of noise.
3. detect edges using Canny edge detection algorithm.
4. do hough transform on those edges and find out lines.
5. draw lines on the image based on the result of hough transform.

# Image Position Matching
This repository provides a solution for detecting the position of a smaller image within a larger image using computer vision techniques. The implementation uses Python and OpenCV to perform template matching and feature-based matching to returns the coordinates of the top-left corner of the smaller image in the larger image.
### Objective
Given two images:
1. A [larger image](https://drive.google.com/file/d/1UqRqni9exxxWUj9sxJTfkyj2GHREkWMf/view) (big image).
2. A [smaller image](https://drive.google.com/file/d/1SOlJshvAOCwhM92YTPXHXurJS1h_Uf6l/view) (template to find within the larger image).
The goal is to detect the position of the smaller image within the larger one and return its top-left corner coordinates.
### Deliverables
The solution as well as reasoning is provided in jupyter nptebook. After some exploratory steps, the Python function was created. It takes two images (a big image and a small image) as input and returns the coordinates of the top-left corner of the matched location.

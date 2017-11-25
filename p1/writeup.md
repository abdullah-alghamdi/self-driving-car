# **Finding Lane Lines on the Road** 

---

[//]: # (Image References)

[image1]: ./test_images/solidWhiteCurve.jpg
[image2:] ./test_images_output/solidWhiteCurve.jpg


---



## 1. steps

### 1 - In the lane_finding fuction (applied on images), I applied the following on the images:
- Gray scaling
- Guassian blur
- Canny edge detector
- Find the vertices of the area of interest
- Apply hough transform on all of the above

![alt text][image1][image2]

### 2 - The white_and_yellow function extracts the two colors from the image
### 3 - The process_image function is similar to the lane_finding, white_and_yellow is added after the Canny edge detector


## 2. What else?
My pipeline is not passing the optional challenge, it needs a function to interpolate the lines ( as recommended in in drew_lines)


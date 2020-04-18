**IMAGE SUPER RESOLUTION USING AUTOENCODERS IN KERAS:**

Image Super-Resolution is the task of generating a high-resolution output image from a low-resolution input by restoring the high-frequency details.

Common resizing methods like those from OpenCV and Scipy libraries use different interpolation approaches to estimate the value of the intermediate pixels based on the values of nearby pixels. The problem of such techniques is that as they smooth the spaces in between in the image, some visual details like sharp edges are often not preserved.

We can use Convolutional Neural Networks as building blocks to construct models able to better predict the pixels in between. Experimenting with different objective functions can lead to different results.

Below is a list of the different approaches that this repo covers. This list is by no means exhaustive and I'll be adding new techniques and code as I continue my research in this domain.



**THIS PROJECT IS DIVIDED INTO 7 TASKS-**

1. Task 1: Project Overview and Import Libraries
2. Task 2: What are Autoencoders?
3. Task 3: Build the Encoder
4. Task 4: Build the Decoder to Complete the Network
5. Task 5: Create Dataset and Specify Training Routine
6. Task 6: Load the Dataset and Pre-trained Model
7. Task 7: Model Predictions and Visualizing the Results

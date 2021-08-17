# Face Mask Detection

# Introduction
The number of coronavirus infections in our country is constantly increasing. It is essential to read mask to prevent coronavirus attacks. The purpose of this project is to have a system that will be controlled by the camera and if the person's face is displayed on the camera, the door will open for him/her if he is wearing Max. In this case, we can reduce the corona virus infection by reading mask.

# Flowchart 
![image](https://user-images.githubusercontent.com/63856744/129728401-22a400e7-bcfe-41f2-a066-52897617d816.png)


# Steps to Perform Image Processing 

•	Load images using Python 

•	Convert images into array

•	finally apply some algorithm on that array

Another good thing is that we have a library known as OpenCV which will help us to read the image and return array of color pixels.


# Introduction to OpenCV

•	OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library.

•	The library has more than 2500 optimized algorithms.

•	It has C++, Python, Java and MATLAB interfaces and supports Windows, Linux, Android and Mac OS.

•	It will help us to load images in Python and convert them into array.

•	Each index of array represents (red, green, blue) color pixel which ranges from 0 to 255

![image](https://user-images.githubusercontent.com/63856744/129728839-59cd7eab-502c-4e28-bd57-25c19b963369.png)

Now its ready to perform basic image processing using OpenCV Package. Now after importing OpenCV I can read an image. So, when i read any image using OpenCV it returns object of numpy array by default and using img.shape we are checking the height and width of image and also it returns 3 which is the color channel of image. Now i can see the values of array are the color values actually.

 Using matplotlib we can visualize the image 
 
 
 ![image](https://user-images.githubusercontent.com/63856744/129729023-c872e2d9-48d5-4469-be40-b31edaa6d108.png)



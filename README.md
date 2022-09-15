# Cartoonify-Image-Using-OpenCV
This Project aims to create a Cartoonified Image of the user input image, with the help of OpenCV in Python.

## Table of Contents
* [Objective](#objective)
* [Why this Project?](#why-this-project)
* [General Information about the Project](#general-information-about-the-project)
* [Technologies Used](https://github.com/Shweta2024/cars-engage-2022/blob/main/requirements.txt)
* [Features](#features)
* [Room for Improvement](#room-for-improvement)
* [Installing Guidelines](https://github.com/Shweta2024/cars-engage-2022/blob/main/Contributing.md)
* [Contact](#contact)


## Objective
The goal of this project is to come up with an application that can take images by user input and can fed it to the program to generate a Cartoonified Image with the help of OpenCV in Python.It also allows the user to save the image to their system.



## Why this Project?

With the recent success of Instagram, the popularity of simple and fun photo effects apps have been on the rise. The mobile platform presents a unique arena for these
applications by connecting users with both the means to capture images and the computational power to perform sophisticated processing on these images.Cartoonify seeks to leverage the existing OpenCV library in order to emulate cartoon effects.


## General Information about the Project

- Image is taken from the user and then fed to the prgram.

- The image is then Grayscaled i.e. it is converted to complete gray color.

- Followed by detecting the edges of the image using Canny Filter.

- After that the image is smoothened.

- The this image is mapped with the edges to get the Cartoonified image.


## Technologies Used

- Python : I have used python as the programming language.

- OpenCV : It is used for processing the image and then cartoonifiying it.

- EasyGUI : It opens a file box and allows us to select any file from our system.

- Numpy : Images are stored and processed as numbers and then taken as arrays.NumPy helps to deal with these arrays.

- OS : It allows interaction, to read the path and save images to that path.


## Features

- Upload Image : Users can upload their desired image from their system to get the cartoonified image.

- Save Image : After an image gets cartoonified , the users can also save it to their system.


## Room for Improvemen

- This can take only one image as input at a time to generate its Cartoonified image.However, there is a scope of imrpovement to allow users to upload multiple pictures at a time to get their cartoonified images.



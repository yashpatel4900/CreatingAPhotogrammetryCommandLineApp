# Creating a Photogrammetry App

Generate 3D objects from images using RealityKit Object Capture.

Input
<img src="https://your-image-url.type](https://github.com/yashpatel4900/CreatingAPhotogrammetryCommandLineApp/assets/62371168/aefb2743-0510-4f00-9b6b-50ff73fd3e73" width="300">

Output

<img width="300" alt="3D Object" src="https://github.com/yashpatel4900/CreatingAPhotogrammetryCommandLineApp/assets/62371168/52f8b2f8-ea26-450c-b44f-c6cb89ba4123">



## About Algorithm 

- This swift scripts using RealityKit library to start a Photogrammetry Session.
- Once the input images are assigned to the session it will detect the object from the pictures rather than positioning the camera in the environment.
- As the object gets detected, the algorithm extracts the features of the object from all its viewing points.
- This features gets constucted in the 3D model.


## Overview

- Click 50-60 pictures of the object which needs to be converted in a 3D model.
- Pictures should be sharp and clear, showing all the details of the object.
- Copy all the images to your computer inside a folder and copy the path of the folder.
- Clone this repository and open it as an Xcode project.
- In the file main.swift paste the path of the folder in the line asking for input folder which is line number - 56.
- Similarly, enter a path location in the line asking for output folder which will be line number - 59.
- Once, everything is ready run the project.
- In 5-10 minutes your 3D model will be generated and saved to your output folder.
- Output files will be in two formats - one will be in .obj file with its textures saved as .mtl and the other one will be in .usdz file format.

## Video Tutorial

- You can find a video tutorial on how to use this algorithm to generate 3D objects from images showing execution of all the above steps - https://drive.google.com/file/d/1dEor7npa9YabBfCe3CyCO57_fpMEByh2/view?usp=sharing

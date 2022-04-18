# Creating a Photogrammetry App

Generate 3D objects from images using RealityKit Object Capture.

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

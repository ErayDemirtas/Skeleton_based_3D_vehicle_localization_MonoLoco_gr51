Group 51: Skeleton Based 3D Vehicle Localization

In this project, we are inspired by the article MonoLoco: Monocular 3D Pedestrian Localization and Uncertainty Estimation and repository: https://github.com/vita-epfl/monoloco. First, we used OpenPifPaf to extract 2D joints from images which are inputs to our MonoLoco model.

Dataset: Kitti 3D object dataset which contains 7481 training and 7518 test images with labels.  

Our contribution: - We changed the number of keypoints and their annotations.
                  - We changed the average human (seperately for man/woman) height with average car (seperately for small and big cars) height. 
                  - Note that these changes are done to necessary parts of every file.

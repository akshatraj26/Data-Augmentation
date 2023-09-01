# Data-Augmentation
Image Data Augmentation
You have create a folder called "data" first
Inside that create two folders Images and Labels

In Data folder create train, test and valid folder
Inside those again create Images and labels folder.



After that you will be ready to go.
You have to install two new libraries

pip install albumentations  # This is used for the data augmantation like rotate image, flip, rgb shift etc
pip install labelme # This is used to create label like for the face detection you have to create a rectangle around your face.


This will create a json file with the x and y axis.

when you run labelme in your idle it will open a new window. 
* Click on Open Direcetory
* Save automatically option
* Change the output directory
* Click on Edit and select option that is neede for your project.

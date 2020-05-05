# FaceMask-Detector
Detecting weather a person has wore a face mask or not using MobileNetv2 Neural Network

__Google Drive Link to the dataset for the training__
https://drive.google.com/drive/folders/1sS_wUj1rG3XU7dqVu7N2M1B7432KdscG

Download the dataset in the same directory as the downloaded project

--> Create a virtual environemnt and install the following dependencies 
* Keras
* Tensorflow (Backend)
* Argparse
* imutils
* Numpy

--> Run the file train_mask_detector.py only once in the commmand line with the argument --dataset dataset
[imp] if you want to draw the plot and save it than un-comment the last part of the code specifying the plotting  method

--> Run the file detect_mask_image.py in the command line with the argument --image examples/example_01.png

--> Run the file detect_face_video.py in the command line to detect masks on a video stream

[imp] the dataset folder and the face_detector folder should be in the same directory as of the downloaded project

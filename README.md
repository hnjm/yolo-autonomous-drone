# YOLO Autonomous Drone - Deep Learning Person Detection

The YOLO Drone localizes and follows people. Since in many scenes more than one person might be in the picture we added special person features to detect the right person. An easy solution was the colour of the person's shirt. Hence, we require the "operator" of the drone to have a yellow shirt.

## Requirements
To run this project Keras and Theano are needed for the deeplearning part. Furthermore a working libardrone must be installed. For shirt detection opencv must be installed on the system.
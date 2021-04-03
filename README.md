# Hand-Detection

This project is a basic hand detection project implemented in Python with OpenCV and Tensorflow. The result can be obtained is the following:

![image](https://user-images.githubusercontent.com/55929797/113470173-26512700-9471-11eb-9ee5-aa98218b8936.png)


# Installation

### OpenCV
If you are working under a Linux distribution or a MacOS, use this [tutorial](https://www.pyimagesearch.com/2018/09/19/pip-install-opencv/) from Adrian Rosebrock to install this library.

### Other requirements
All the other requirements can be installed via the command : 
```bash
pip install -r requirements.txt
```

# Download Tensorflow models

In my project I used the ssd model. You can download this model and several others from the [Tensorflow detection model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md). 

# Run project
Run hand_detection.py file 
A window from your webcam will appear and you can test the project

# Outputs
If you move your hand above the red line a warning sound will be heard

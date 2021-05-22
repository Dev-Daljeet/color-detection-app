# Color Detection App

This project is a color detection app that detects the color name and RGB color code of any object in an image. 

The project folder contains 3 main files:
- **Color_detection.py** – main source code of the project
- **Colorpic.jpg** – sample image for experimenting
- **Colors.csv** – a file that contains the dataset which includes 865 color names along with their RGB and hex values

The other 2 files are README.md for documentation and MIT LICENSE file.

**Programming Langauge:** Python

**Modules/Libraries used:** Argparse, Pandas and OpenCV

## A sample screenshot/gif of Project

![Screesshot of output](https://github.com/Dev-Daljeet/Screenshots/blob/master/color-detection-app/default.gif?raw=true)

## Installation and Setup Instructions

### Prerequisites (Requirements):

For running this script you need:

- [Python](https://www.python.org/downloads/)
- [OpenCV](https://pypi.org/project/opencv-python/) and [Pandas](https://pandas.pydata.org) are the Python packages that are necessary for this project

### How to Use/Run:
1. Clone this repository

2. To install OpenCV and Pandas, simply run this pip command in your terminal:
   ````
   $ pip install opencv-python pandas
   ````

2. Go to `\color-detection-app` directory and Execute `color-detection.py`: 
    ```
    $ python color_detection.py -i <add your image path here>
    ```
    
    or
    
     Allow execution of the `color-detection.py` file: `$ chmod a+x ./color-detection.py`
    
    ```
    $ ./color-detection.py -i <add your image path here>
    ```
    
4. Follow the instructions. **Double left click on an object to see the color name and RGB color codes. Use the esc key for exit.**

# License
MIT License
Copyright (c) 2021 Daljeet Singh

Refer to **LICENSE** file for full information.

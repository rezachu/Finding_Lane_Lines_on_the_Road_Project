# Finding Lane Lines on the Road
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

## Overview
This is the first project of the Udacity Self Driving Car Nanodegree. In this project, we are going to learn how to use Python and OpenCV (Open-Source Computer Vision) to detect and capture the straight driving lane line in the videos provided.

## Software requirement

- [Python 3](https://www.python.org/downloads/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://ipython.org/notebook.html)
- [moviepy](http://zulko.github.io/moviepy/)


### Memo to Python beginner
In case you are new to Python and you do not know how to create an environment and install the package, here are few links that could help.
- [Managing Python](http://conda.pydata.org/docs/py2or3.html)
- [Managing Environments](http://conda.pydata.org/docs/using/envs.html)
- [Create Virtual Environments for Python with Conda](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)

## Installing OpenCV

Once you have Anaconda installed, first double check you are in your Python 3 environment:

`>python`    
`Python 3.5.2 |Anaconda 4.1.1 (x86_64)| (default, Jul  2 2016, 17:52:12)`  
`[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.28)] on darwin`  
`Type "help", "copyright", "credits" or "license" for more information.`  
`>>>`   
(Ctrl-d to exit Python)

run the following commands at the terminal prompt to get OpenCV:

`> pip install pillow`  
`> conda install -c menpo opencv3=3.1.0`

then to test if OpenCV is installed correctly:

`> python`  
`>>> import cv2`  
`>>>`  (i.e. did not get an ImportError)

(Ctrl-d to exit Python)

# Installing moviepy  

To install moviepy run:

`>pip install moviepy`  

and check that the install worked:

`>python`  
`>>>import moviepy`  
`>>>`  (i.e. did not get an ImportError)

(Ctrl-d to exit Python)

## Run 
1. Start your the terminal or command line
2. Activate your environment
3. Navigate to the root directory of this repository (./Titanic_Survival_Exploration_Project/)
4. Run `jupyter notebook Titanic_Survival_Exploration.ipynb`



## Documents included in the repository

- `README.md`
- `Empty_Lane_Lines.csv`
- `Finding_Lane_Line.html`
- `Finding_Lane_Line.ipynb`
- `challenge.mp4`
- `P1_example.mp4`
- `raw-lines-example.mp4`
- `solidWhiteRight.mp4`
- `solidYellowLeft.mp4`
- `yellow.mp4` (video exported)
- `white.mp4` (video exported)
- `laneLines_thirdPass.jpg`
- `line-segments-example.jpg`
- `./test_images/`
  - `solidWhiteCurve.jpg`
  - `solidWhiteRight.jpg`
  - `solidYellowCurve.jpg.jpg`
  - `solidYellowCurve2.jpg`
  - `solidYellowLeft.jpg`
  - `whiteCarLaneSwitch.jpg`






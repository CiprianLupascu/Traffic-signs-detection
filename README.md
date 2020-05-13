For this project I have worked with anaconda command terminal
First, you will have to set up a new anaconda virtual environment
C:\> conda create -n tensorflow1 pip python=3.5

Then, activate the environment and update pip by issuing:
C:\> activate tensorflow1

(tensorflow1) C:\>python -m pip install --upgrade pip

Install tensorflow-gpu in this environment by issuing:
(tensorflow1) C:\> pip install --ignore-installed --upgrade tensorflow-gpu
!!!!(You will have to install the CUDA toolkit from nVidia in order to run the code. I have used the version 8)!!!

Install the other necessary packages by issuing the following commands:

(tensorflow1) C:\> conda install -c anaconda protobuf
(tensorflow1) C:\> pip install pillow
(tensorflow1) C:\> pip install lxml
(tensorflow1) C:\> pip install Cython
(tensorflow1) C:\> pip install contextlib2
(tensorflow1) C:\> pip install jupyter
(tensorflow1) C:\> pip install matplotlib
(tensorflow1) C:\> pip install pandas
(tensorflow1) C:\> pip install opencv-python

Then cd to the "traffic signs model" folder 
Enter the "idle" command in the terminal
Open the Object_detection_webcam script and run it
This script uses your webcam to detect 4 traffic signs and a pedestrian model


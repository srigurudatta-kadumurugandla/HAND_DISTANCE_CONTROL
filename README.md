# -AIML-Hand-Gesture-Control

 Introduction

 This program  essentially creates a virtual mouse control using hand gestures detected from the webcam feed. It tracks the movement of the index finger for cursor control and detects a clicking gesture by bringing the thumb close to the index finger.


Libraries Used
1)OpenCV 
2)Mediapipe 
3) pyautogui

Requirements For Execution Of The Code
1.	Install pycharm 
2.	Python version 3.11 
3.	Install packages opencv ,mediapipe and pyautogui  
Procedure for installing packages
•	Go to file ,click on settings and the python interpreter
•	Then click on the ‘+’ on the left corner of the table appearing on the right
•	then type opencv-python to install opencv libraries and in similar fashion install mediapipe and pyautogui by entering the respective name in the search bar provided above 
4.	Make sure a webcam  is present in the laptop or system


Steps to execute
1.	There are two way to access the project files 
•	 Firstly choose any directory u wish to store the project files ,right click on the screen and select open terminal. Make sure u have git bash installed
•	And type the command git https://github.com/Samrat-Shaw/-AIML-Hand-Gesture-Control
•	Due to this all the project files from github will be  stored in the directory or folder u want to save.
•	Then open pycharm go to “Files” then to “Open” and select the directory where u have stored the project folder and then click on the project folder 
•	Now all the files would be imported to pycharm.
•	Second way u can access the files in pycharm is by downloading the zip of the repository to do that  click on code and click on last option “download zip file”
•	Extract the zip file at the desired directory . 
•	Then open pycharm go to “Files” then to” Open” and select the directory where u have stored the project folder and then click on the project folder
•	All the project files will be imported.

2.Install the libraries as mentioned earlier in requirements
3.execute the code  by  running  main.py    
4. there is a feature which  implements the range of distance from where we can perform the actions if your in range it will display OK otherwise a blank screen will be appearing ,so make sure to stand within the range of camera.
5. Use index finger to move the cursor around and bring both index and thumb finger for clicking action
6.To terminate code press ‘q’key
### py -3.11 -m venv venv311
### venv311\Scripts\activate 
### pip install opencv-python
###  python main.py  

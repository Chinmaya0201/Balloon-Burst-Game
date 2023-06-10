# Balloon Burst Game

It is an interactive game developed using Python modules Pygame, OpenCV and Mediapipe

I took the idea of a basic balloon popping game, where random balloons would appear on the screen and the player used to pop them, using click of the mouse but rather than using mouse I added a feature where player can use their index finger to pop them. 

# Approach 
1.	Developed the base of the game using Python PyGame Module.
2.	Used 4 different balloons color namely red, blue, green, yellow with their respective burst effects.
3.	Made use of Object-Oriented Programming to define the attribute of each balloon.
4.	The attribute contained the modified image, x and y coordinates and speed of that balloon.
5.	 Made use of Sprite class in PyGame to hold all the attributes and behaviors of the game characters.
6.	Displayed the score and other instructions on the screen.
7.	Then for the second part I used OpenCV Library to access the camera and capture the real time footage of the background.
8.	Converted the frame into desired size and from BGR to RBG.
9.	For the third part of the game, I used mediapipe library to detect index finger and get the coordinates.
10.	Then for basic game logic when coordinate of balloon and user’s finger collided the balloon would pop also triggering the burst effect and the score will increase.
11.	For the final touches I also added an Intro Window which had a start button that could also be accessed by using the index finger and the current high score of the session.

## Projects Screenshots

### Introduction Window
![Alt text](<Project Screenshots/INTROWINDOW.PNG>)

### Main Window
![Alt text](<Project Screenshots/MAINWINDOW.PNG>)

### Working Video
https://github.com/Chinmaya0201/Balloon-Burst-Game/assets/101726470/017e468d-6958-447e-b686-182bbaad20c9

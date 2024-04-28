#README

All code is preset to webcam on your computer.
Press "q" in any code to exit

#hand_Mouse

This code tracks your hand and with it, controls your cursor on the screen
The code is made in Python
The code will be very slow on some computers so to counter this, the smoothness of the cursor has been reduced
Your hand must be inside the rectangle shown on the popup to control your cursor. Think of it like a trackpad.
Index finger up to move the cursor around
Thumb and index finger have to touch to click on the screen
Index, middle and ring fingers up scrolls up
Index, middle, ring and pinky up to scroll down


#minecraft_Movements

Lift only index finger on your right hand to control the way you look
Left hand controls all other controls.
I'm adding more gestures to move your character and fully play the game.
IMPORTANT: Might not work in some versions due to backend issues. Works in Java edition, maybe in Bedrock edition
I'll try to figure out ways so that you can play in any version.
Lot's of comments and more to come!


#Fruit Ninja

Lift your index finger up and your cursor will follow it. Use this to cut fruits!


#GeneralDetection

Detects hands and body


#Rep Counter

Counts the amount of reps of a workout of your choice
So far only 2 workouts possible: Forearm curls and lateral raises
Shows the amount of reps per arm
"q" to quit the code

#PictureTakingCodeForAI

First of 3 codes to make and use a custom computer vision model.
Can take pictures of your screen or webcam and save them to a file.
Make sure the data has the same background in every image you take for maximum accuracy!
Press the spacebar to take a screenshot and "q" to exit
Works in conjunction with CustomComputerVisionModelMaker and ModelUser

#CustomComputerVisionModelMaker

Second of 3 codes to make and use a custom computer vision model.
This code makes a custom model that you can use to identify something of your choice.
Works in conjunction with PictureTakingCodeForAI and ModelUser
Too high of a accuracy can lead to over training which means it might not be able to adapt. Preferred accuracy is 80-95!

#ModelUser

Third of 3 codes to make and use a custom computer vision model.
Give the path to the model you made with the second code.
Recognizes through screen or webcam with the model
Press the spacebar when recognizing through screen

#ExactHandDirections

Gives everything from which hand is being shown to the direction the hand is pointing to (Not fingers, entire fist), and the orientation of th palm compared to the camera. The text is shown in the popup.
Text is black so may not be visible if the background is black.

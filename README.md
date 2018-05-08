# Face-and-Voice-based-Home-Security-System

State of the art facial and voice recognition system for home security leveraging cognitive libraries and APIs.

1. Face - dlib's facial recognition library
2. Voice - VoiceIt API
3. Sending text notifications - Twilio messaging app

# Steps for running the demo

STEP 1 (Create Twilio credentials):
1.	Go to the sign up page (https://www.twilio.com/try-twilio) and sign up as a new user.
2.	Enter a phone number for verification and type in the code.
3.	Give your project a name and click continue. 
4.	Once you go to the console page click on Generate a number on the top of the screen.
5.	Click on Choose this number and copy the number given to be pasted in the code.
6.	Go to the Console Dashboard and copy the Account SID and Auth token.
7.	Copy the Account SID and Auth token to the placeholders given in the code.

STEP 2 (Create Voiceit credentials):
1.	Go to the sign up page (https://voiceit.io/signup) and sign up as new user.
2.	Go to the user management tab and create a new user.
3.	Go to the settings and retrieve the developer id. Copy paste the developer id to the placeholder in the main code.
4.	Next go to the following link (https://voiceit.io/apidemo) and enter the user id details and developer id generated. 
5.	In the same page create new voice enrollments and say the catch phrase prompted.
6.	Make 5 to 10 recording of your voice and maintain the same tone and modulation.
7.	Refer to the DOCS page (https://voiceit.io/devDocs) for more info

STEP 3: Once this is done, download the three python files given (plotting.py, security.py and voiceit.py)

STEP 4: Next we need to install the face recognition package DLIB which requires Visual studio 2014 and all C++ packages to be installed along with it

STEP 5: Once this is done, go to the terminal and pip install face_recognition

STEP 6: Packages to be pip installed are:
1.	Face recognition         : pip install face_recognition
2.	Twilio                   : pip install twilio
3.	Pyaudio                  : pip install pyaudio
4.	Pyttsx                   : pip install pyttsx

STEP 7: After all the necessary packages are installed, run the file (plotting.py)

STEP 8: After running do not show your face in front of the camera, until the system prompts you through voice

STEP 9: Once prompted you can show your face in front of the camera and the system will provide you with voice prompts regarding next steps

STEP 10: Steps prompted during running the program
1.	Prompt to show your face in front of the camera.
2.	If face detected voice authentication prompt given.
3.	If face not detected, message about unknown person trying to enter is sent to the users registered mobile number.
4.	System prompts voice phrases to be mentioned by the user for voice authentication
5.	If Voice authentication successful, Message that user can enter the house is prompted
6.	Else if user authentication fails, user is given an option to repeat the catch phrase three times. If user fails after three times, message is sent to the users phone and the user s prompted that he is not given access to the house.




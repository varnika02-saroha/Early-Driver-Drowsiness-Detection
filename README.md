# Early-Driver-Drowsiness-Detection
LOGIC OF THE PROJECT:-

Introduction: 
In this project, we are going to build a ‘driver drowsiness detection system’ that will detect if the eyes of the driver are close for too long and infer if the driver is sleepy or inactive. 
Drowsiness Detection is the technique implemented for the detection of a person to check whether the person is feeling sleepy while performing a significant task. This detection has many applications in medical and safety fields. This detection can be quickly done using “shape predictor face landmarks” that mark the essential landmarks on the face. This detection can also be done using the HAAR Algorithm. 

Motivation: 
The Drowsiness Detection System can be an important implementation to ensure safety of drivers, as studies suggest that road accidents that occurs due to the drivers getting drowsy or sleepy account for approximately around 20% of all the accidents and on certain long journey routes, it’s estimated to be up to 50%. It is a serious issue that needs to be taken care of, and certainly, most people those who have driven for continuous long hours at night, can relate to the fact that fatigue and slight brief state of unconsciousness can happen to anyone and everyone, thus further pointing towards the need of drowsiness detection system.

Technology Used: 
The libraries need for ‘early driver drowsiness detection system’ are as mentioned below:-
•	Opencv 
•	Dlib 
•	Numpy 
•	Imutils
•	Pygame 

❖ Libraries: 
1.	Installing and importing all the modules needed for the code. 
•	1. pip install numpy     
•	2. pip install opencv-python 
•	3. pip install time 
•	4. pip install pygame 
•	5. pip install dlib 
•	6. pip install scipy  

Use of Important functions in the program:
 
•	VideoCapture(): The function is used to declare the parts of the camera used for the OpenCV and to turn on the camera. 
•	cv2.imshow(): To display the camera output that is prior set by the user. It is the visual display by the camera on the screen. 
•	dlib.shape_predictor(“location of the .dat file”): The face landmark features will be stored inside the “.dat file”. 
•	cv2.waitkey(“time limit set by the user”): This will keep open the cv2 interface for the given declared time by the user.
•	mixer.init(): The function is used to play the alarm sound/alert as soon as the system reaches to the condition indicating user’s drowsiness. Here, I have used the alarm that can be accessed through
https://drive.google.com/file/d/1y5wGRbcAZWG0OH6gNjFLqgo2gj94o05O/view?usp=sharing 

RESULT:
The library’s pre-trained 68 facial landmark detector is employed in this Dlib technique. The face detector was constructed, which is based on the Histogram of Oriented Gradients (HOG). The quantitative metric used in the proposed algorithm was the Eye Aspect Ratio (EAR) to monitor the Driver Drowsiness. The average real-time test accuracies obtained using Dlib for Eye Detection Accuracy was found to be 80.17% and Drowsiness Accuracy as found to be 78.50%. The results of real-time detection are lower as the model currently works well under good lighting conditions.

APPLICATIONS:
▪ Transportation business where almost daily accidents occurs due to driver fatigue. 
▪ Security guard cabins. 
▪ Operators at nuclear power plants where continuous monitoring is necessary. 
▪ Military applications where high intensity monitoring of soldier is needed. 
▪ In classrooms where students feel drowsy and inattentive during the class. 
▪ In Offices to detect lazy and sleepy employees.

LIMITATIONS:
▪ Dependency on proper ambient light. 
▪ An optimum range is required. 
▪ Orientation of face. 
▪ Problem with multiple faces. 

CONCLUSION:
▪ This system can be used to reduce the amount of road accidents that happen to a great extent. 
▪ This can save a lot of lives which is the main motive of the system. 
▪ Taking into consideration, it is the future of the road safety.   

References:
https://github.com/infoaryan/Driver-Drowsiness-Detection.git
https://github.com/Pankaj-Chadda/Driver-Drowsiness-Detection.git





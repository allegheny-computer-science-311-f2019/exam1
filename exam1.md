# CMPSC 311 Exam 1
# Name: 

## The exam is open notes (printed or electronic) but closed to Internet searches. 


### Question 1 [10 points]

Specify any two steps in the see-think-act cycle. Shortly describe what each of your selected steps is responsible for and give an appropriate example for each one.



### Question 2 [10 points (2 points each)]

1. Are wheel/motor sensors proprioceptive or exteroceptive?
2. Are gyroscope sensors active or passive?
3. Are GPS sensors proprioceptive or exteroceptive?
4. Are ultrasonic sensors active or passive?
5. Are doppler radars (motion/speed sensors that measure speed relative to fixed or moving objects) proprioceptive or exteroceptive?



### Question 3 [10 points]

How is the error of the sensor measured? Give a concrete formula and an example of applying the formula.



### Question 4 [10 points]

What is the goal of calibration? Provide an example of the calibration process for a sensor (you can use any sensor for your example).  



### Question 5 [10 points]

Describe a scenario where map-based localization may not be appropriate.



### Question 6 [10 points]

Consider the environment in the image below. Your robot begins room A and has a goal of stopping in the large room at position B. Design a sequence for a behavior-based robot to navigate successfully to B. Don't worry about the scale and the exact value of X if you use Turn X and Move X behaviors. \\

*Behaviors available are:* \\

LWF: left wall follow \\
RWF: right wall follow \\
HF: go down centerline of a hallway \\
Turn X: turn X degrees left/right \\
Move X: move X centimeters forward/backward \\
EnterD: center and enter through a doorway \\

*Termination conditions available are:* \\

DoorL: doorway on the left \\
DoorR: doorway on right \\
HallwayL: hallway intersection

### Question 7 [10 points]

Assuming that the lego EV3 robot (programmed in leJOS) has a pen attached to it for drawing a line as it moves and given a code snippet below, what will be drawn by the robot (in a perfectly executed scenario) when it is finished with its navigation task? 
Assume an instance of the {\tt DifferentialPilot} class, called {\tt pilot} has already been declared and initialized:
	\begin{verbatim}	
...
pilot.travel(100);
pilot.rotate(90);
pilot.travel(100);
pilot.rotate(90);
pilot.travel(100);
...
	\end{verbatim}


### Question 9 [10 points]

lejos - perception


### Question 8 [10 points]

Ethics

agent/robot definition
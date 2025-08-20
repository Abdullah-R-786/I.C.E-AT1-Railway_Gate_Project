## I.C.E - AT1 - Automatic Railway Gate Logic Project


This repository is for Intro to Computer Engineering - Assessment Task 1 - The Automated Railway Gates Crossing Project. In this repository will include folders for different sections of the assignment with their appropriate files within them for marking. 

The relevent Word Document which has all the questions and written responses compiled together will also be uploaded directly to the respository, and will sit outside of the folders/not in any folder.

## Project Overview
This project is an automated railway gate crossing system designed to ensure the safety of oncoming passengers at the gate crossing intersection. It uses a multitude of sensors to determine the current event and proceed with the appropriate actions. The system is designed to operate continuously and autonomously using real-time logic and sensor feedback.

##   Features
Automatic Railway Crossing Gates with Different Functions for Different Achieved Conditions
-	If a vehicle is detected while a train is approaching, the system delays lowering the gates until the vehicle has safely exited the crossing.

-	If a vehicle enters the crossing late (after the gates have started lowering), the system halts or pauses gate movement until the vehicle clears, preventing it from being trapped.

-	If a train is detected actively crossing, the gates remain fully lowered until it has completely passed.

## Hardware Components
•	Train Approach Sensor
•	Occupancy Sensor
•	Train Departure Sensor
•	Gate Warning Alarm (Audible)
•	Gate Warning LED Lights (Visual)
•	Railway Crossing Gates
•	Logic Controller


## Future Improvements
•	The provided background information has an issue regarding ambiguity in the scenario when a vehicle is already on/getting on the tracks while a train is approaching. The ambiguous condition from the background information suggested that when either condition is true (“gates are lowered when a is train approaching OR a vehicle is still on the tracks”), which is not a good logic condition as it could result in a severe accident through a collision between the train and a trapped vehicle.  We have already gone ahead and refined this issue by setting up the logic, such that if a vehicle is present/occupying the track, the gates must not immediately lower, otherwise the vehicle may get trapped. Instead, the gates will raise for the vehicle to exit out of the crossing and will then close once the vehicle is no longer present.
•	Implement additional short delays within the circuit logic, specifically before lowering gates when train is approaching in order to prevent vehicles unintentionally getting trapped. 
•	Implement log system to record all train/vehicle/gate events for safety audits and analysis.
•	Integrate an emergency override feature which provides a manual control option for authorities if any sensors break/fail or gates get stuck for digital controls.
•	Add backup sensors to prevent failure in detecting vehicles or trains and to mitigate issues if a sensor suddenly stops working.

---

For questions or contributions, please contact Abdullah Rubbani (u3280268).

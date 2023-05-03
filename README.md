# ParkEase

Parking is a key component in the everyday life of citizens of most metropolitan areas including Toronto, Ontario. The citizens of the city continuously face parking problems associated with educational institutions, religious establishments, airports, commercial activities and special events. 

ParkEase was built to address some of these parking issues by developing and implementing an automated parking lot system with a user-friendly web application that displays real-time data of the parking lot. 

There are 3 Components of this system:

Hardware
- 3 sensors combined to detect a car in a given slot
- The sensors have a metal detector built in to ensure non-metalic debris does not result a change in the sensors
- RGB Led light that changes from green to red based off the occupancy of the slot (change in sensor)
- Cameras: Camera recognition of license plates at entrance and exit gates
- Upon accurate validation of a customers license plate (if it is registered in the system) the gate will automatically open
- In case the camera recognition process fails, the user is prompted to scan their QR Code at the gate (acts as a Digital ID/Confirmation)

Software
- React js and Node js web application that features a Map that displays real-time data of each parking slot
- Also features a Customer Profile, Booking Form, and Digital Wallet that stores the QR Code (booking confirmation) and transaction history
- Adjusts rates based off the popularity of the parking lot at a given time and charges users accordingly

Data Analytics 
- Uses the data points comprised in the PostgreSQL database to generate information regarding customer frequency
- Describes the most popular spot in the parking lot, most popular days / weeks / months

# ParkEase

Developed in a team of 4 from January 2023 - April 2023 as a course project @ Toronto Metropolitan University

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


<img width="231" alt="Screen Shot 2023-05-03 at 2 41 07 PM" src="https://user-images.githubusercontent.com/52759538/236012906-31b503ac-7fd5-484e-bd45-996bff14615c.png">


<img width="334" alt="Screen Shot 2023-05-03 at 2 40 37 PM" src="https://user-images.githubusercontent.com/52759538/236012741-b6c5d7ae-4d75-4d92-a986-cb66045b5212.png">

<img width="705" alt="Screen Shot 2023-05-03 at 2 40 22 PM" src="https://user-images.githubusercontent.com/52759538/236012686-cb76a3b0-b52c-4db6-b6e6-363922a7639c.png">

<img width="529" alt="Screen Shot 2023-05-03 at 2 40 54 PM" src="https://user-images.githubusercontent.com/52759538/236012823-0e5cc2ab-8982-4cc4-8d60-48b83f18e98a.png">

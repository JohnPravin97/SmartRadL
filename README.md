# SmartRadL

## Objective

<p style = "font-family: Times New Roman"> <p style="font-size:110%;"> Nowadays many people prefer to choose their bike as a mode of commutation to their office, university, etc. Although there are numerous improvements done towards the pathway for the bikes, still bikers are facing difficulties commutating in their bikes due to the road surface conditions. Also, not knowing the road surface of their planned routes makes it difficult to choose the suitable bikes for their commutation. In this project, we tried to monitor the conditions of the road surface by using machine learning algorithms to classify different pavements of the road like asphalt or cobblestone as well as obstacles found on different pavements of the road like manhole/potholes, kerbs, and speed bumps using the data obtained from the Physics Toolbox Suite Pro App by mounting the mobile phone onto the bike.</p> </p>

## Hardware

<p style = "font-family: Times New Roman"> <p style="font-size:110%;"> For collecting the data, we have chosen two riders biking a Scott Bosch e-bike, which is put in eco mode, in 7th gear, and with a tire pressure of 2 bar. Furthermore, we have used One Plus Nord, running on android 11, mounted on the stem of the handlebar of the bike, installed with the pro version of physics Toolbox Suite Pro App to record the three axes g-force, three-axis acceleration, three-axis gyroscope, azimuth, roll, pitch, GPS coordinates, and speed data. Finally, we have used GoPro Black 4 hero camera to record the video of the rides which is later used for labeling the features.</p> </p>

## Feature Labels

|- Stop                                                                                                                     | - Asphalt Ride
|![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Stop.JPG)        | ![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Asphalt_Ride.JPG) 
|       
|

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Stop.JPG)    

- Asphalt Ride 

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Asphalt_Ride.JPG)                     

- Cobblestone Ride

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Cobblestone_Ride.JPG)

- Asphalt Manhole 

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Asphalt_Manhole.JPG)

- Asphalt Kerb 

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Asphalt_Kerb.JPG)

- Asphalt Bump

![Example Data Table](https://raw.githubusercontent.com/JohnPravin97/SmartRadL/main/Vaihingen_Dataset/Img/Asphalt_Bump.JPG)
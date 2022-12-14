# Question 1

a.) In the first part of this lab, we are required to utilize the internal temperature sensor of MSP430FR2355 microcontroller in order to read temperature in the lab. To carry this out, we use the ADC capabilities of the MSP430 by using channel 12 in our code. ADCMEM0 was then used to read the value of the internal temperature sensor. The following plot shows the temperature over time after running the code:

<img width="959" alt="INTERNAL TEMPERATURE SENSOR (FARENHEIT)" src="https://user-images.githubusercontent.com/98994111/205361908-74285ed0-cc6c-4f5b-98b7-97bf174b852f.png">

b.) The following images show the Level 0 and Level 1 diagrams used for obtaining the readings for the internal temperature sensor:

Level 0:
![image](https://user-images.githubusercontent.com/85361948/206054379-ff4ce63a-484e-400f-9e9b-2e9e8c1b260f.png)

Level 1:
![image](https://user-images.githubusercontent.com/85361948/206054443-9bdf4363-0bb5-498c-b6c2-09e4e4ceed9f.png)

c.) The following figure shows the UML diagram created prior to writing the code:

![IMG_1616](https://user-images.githubusercontent.com/98994111/206060945-542d2031-d33f-4e25-b2e6-832e7f46fedc.jpg)

d.) Since the internal temperature sensor was used for this portion of the lab, no schematic is implemented.

e.) https://github.com/brown-donovan/LAB_5/blob/main/INTERNAL%20TEMPERATURE%20SENSOR


# Question 2

a.) Not only was the internal temperature sensor used, but the DHT 11 temperature sensor was used as well. The plot below shows the change in temprature as the number of samples increase. The temperature readings of the DHT 11 were in units of farenheit. After the first sample, the initial temperature of 71.8 degrees decreased to 64 degrees and remains constant for five consecutive samples. After the sixth sample, the temperature decreases again from 64 degrees to 61 degrees. 

<img width="960" alt="DHT 11 GRAPH (FARENHEIT)" src="https://user-images.githubusercontent.com/98994111/205361845-5a60f775-d7bb-4bc4-9315-b82f83b7c2c0.png">

b.) The following images show the Level 0 and Level 1 diagrams used for obtaining the readings for the DHT11:

Level 0:
![image](https://user-images.githubusercontent.com/85361948/206054301-29fb7eee-edb5-46f7-a784-5abfac26946a.png)

Level 1:
![image](https://user-images.githubusercontent.com/85361948/206054309-acef75bc-3833-4baa-8b23-19a9ab9f07ad.png)

c.) The following figure shows the UML diagram created prior to writing the code:

![IMG_1617](https://user-images.githubusercontent.com/98994111/206060905-e4aebcec-1043-46fb-b782-64ddcbfa1b4d.jpg)


d.) The following figure shows the schematic used for hooking up the DHT11 Sensor to the MSP430 microcontroller:

![image](https://user-images.githubusercontent.com/85361948/206058470-c6109c32-ed37-41a7-aaea-6616ea48980e.png)


e.) https://github.com/brown-donovan/LAB_5/blob/main/DHT%2011%20TEMPERATURE%20SENSOR


CONTRIBUTION CHART: 

<img width="282" alt="Screenshot 2022-12-06 195508" src="https://user-images.githubusercontent.com/98994111/206061271-60eaa1e5-e6fe-4c35-9218-4ebf10ce830a.png">




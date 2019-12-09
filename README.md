# RVR(Resistor Value Recoganizer) 
## Build Insructions for Luminosity Sensor - TSL2591 from Adafruit

### Table of Contents 
[Introduction](https://github.com/HusnalK/Resistor-Value-Recognizer-RVR#Introduction)

[Budget](https://github.com/HusnalK/Resistor-Value-Recognizer-RVR#Budget)

[Time Commitment](https://github.com/HusnalK/Resistor-Value-Recognizer-RVR#Time-Commitment)

### Introduction
The build instructions given below work with Adafruit's luminosity sensor- TSL2591, which will be integerated in the project Resistor Value Recognizer. The TSL2591 sensor measures the light of the environment in lux. The values obtained from the sensor will be used to control LED's in the final project to provide adequate lighting to the camera.

These build instructions will demonstrate the process to design, program and build a PCB for the sensor to connect it to a broadcom development platform. The sensor in this tutorial is working with Raspberry Pi 3B+ and will provide the design file for a laser cut acrylic case along with refrences to all the resources that will be needed for the creation of this project.

The final design and build of the project can be seen below:
<p align="center">
<img src="Images/enclosure1.jpg" width="500" height="600" align="middle" alt="Enclosure">
</p>

### Budget

Given below is the list of all the parts that might be required in this project. It is taking into consideration that you have facilities for safe soldering and powering up the project. 

| Description                    | No. of Each  Parts Required | Source  | Cost of Each Part   (CAD) | Link                    |
|--------------------------------|-----------------------------|---------|---------------------------|-------------------------|
| Raspberry Pi 3 b+  Motherboard |       1                     | Amazon  | $ 79.97                   | https://amzn.to/2ruQ5ua |
| Raspberry Pi Power Supply      |       1                     | Amazon  | $ 12.98                   | https://amzn.to/2YyIirt |
| Micro SD Card (32 GB)          |       1                     | Amazon  | $ 10.68                   | https://amzn.to/356bubr |
| Adafruit TSL2591 Lux Sensor    |       1                     | DigiKey | $ 9.97                    | https://bit.ly/2lTpzYk  |
| Ethernet Cable                 |       1                     | Amazon  | $ 8.29                    | https://amzn.to/2LBMQaY |
| USB 3 to Ethernet Adaptor      |       1                     | Amazon  | $ 20.05                   | https://amzn.to/2RB8HmJ |
| Stackable Pin Header Kit       |       1                     | Amazon  | $ 19.98                   | https://amzn.to/2PyRhVc |
| 40x20cm Female to Female Wires |       1                     | Amazon  | $ 6.99                    | https://amzn.to/2RHou3L |
| Acrylic Plexiglass Sheet       |       1                     | Amazon  | $ 19.99                   | https://amzn.to/2Ry0JLj |
| Screws (M2.5)                  |       4                     | Digikey | $ 0.15                    | https://bit.ly/2t4eDuB  |
| Nuts (M2.5)                    |       4                     | Digikey | $ 0.32                    | https://bit.ly/355WCdt  |
Total = 190.78 CAD


I am using a Raspberry Pi 3b+ as my broadcom development platform. The micro SD card is used to upload the raspbian and set up the Raspberry Pi. Some of these supplies like Raspberry Pi and its power supply, micro SD card, header and wires, ethernet cable and Acrylic glass sheet might already be avaiable with a lot of people doing this project and that greatly reduces the cost of the project.  

Also an important thing to note is that the table above only shows the cost of the part; Taxes, shipping and import fee might still be laid on top of these prices depending on where you live. This may cause an increase in the cost of the project.

### Time Commitment

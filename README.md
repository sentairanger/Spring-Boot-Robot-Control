# Spring-Boot-Robot-Control
This project uses Spring Boot and Diozero to control a robot with the CamJam Edukit 3 board

## Getting Started

To run this project make sure to have Java installed in your machine. Next you can run the application with `java -jar -DPIGPIOD_HOST=your-pi-ipaddress torvalds-0.0.1-SNAPSHOT.jar`. Make sure your robot has remote GPIO enabled with `sudo pigpiod` or run `sudo raspi-config` and then enable it in Interfaces. You can also use the Raspberry Pi Configuration Menu if using the Desktop. Next, access the app at `localhost:8080/home` and then press the buttons. Make sure you wait until the robot stops moving because you will get the already in use error. This is because it's waiting to finish the commands. 

![robot](https://github.com/sentairanger/Spring-Boot-Robot-Control/blob/main/robot.png)

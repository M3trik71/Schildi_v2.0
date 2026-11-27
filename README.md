# Schildi_v2.0

![Projektübersicht](Trailer2.jpg)

This Python project is a newer robotic pet from Project called "Schildi_v2.0". The Base is a "Hiwonder SpiderPi Standard", equipped with clever sensors, it continuously scans its surroundings, processes data in real-time, and reacts completely autonomously with appropriate actions.

Here are the following Components for the Upperside:

![Projektübersicht](Trailer3.jpg)

- 1x Raspberry Pi 5 4GB
- 1x Raspberry Pi 5 Expansion Board Model B
- 1x USB Soundmodul
- 1x USB HBVCAM-V2101 HD Wide Angle Camera
- 1x USB Free Cable
- 1x I2C Gravity HUB v1.0
- 1x Yahboom AI Voice Interaction Module
- 1x PCF8591 AD/DA Konverter Modul
- 1x BME280   Temperatur, Luftdruck, Luftfeuchtigkeit
- 1x GY-521 3-Achsen Gyroskop Sensor Beschleunigungssensor

Here are the following Components for the Underside:

![Projektübersicht](Trailer5.jpg)

- 1x Red Power 10000mAh 3S1P 11.1V Battery
- 1x Main Switch
- 1x F5AL230V Fuse
- 1x INA226 Spannungs Strom Modul
- 1x Free Positiv Cable
- 1x Free Negative Cable

And the Wireing-Diagram for the Underside:

![Projektübersicht](Trailer6.jpg)

Here are the following Components for the Frontside:

![Projektübersicht](Trailer4.jpg)

- 1x HBVCAM-V2101 HD Wide Angle Camera 
- 2x AZDelivery 0,96 Zoll OLED Display I2C - SSD1306 Modul
- 1x OLED Display SH1106 Modul
- 1x Servo Port
  

----------------------------------------------------------

The following are individual descriptions of the various components::

Raspberry Pi 5 4GB

![Projektübersicht](Raspberry-Pi-5-Specification.jpg)

Ports:
- 1x 40-Pin GPIO-Leiste
- 2x Micro-HDMI
- 1× USB-C (Stromversorgung)
- 2× USB 3.0 (blau)
- 2× USB 2.0
	- HD Wide Angle Camera HBVCAM-V2101 V11
	- youyeetoo LD19 LiDAR Kit - 12 Meter - 360 Grad - 30K Lux
- 1x Gigabit Ethernet (RJ45)
- 1x Fan Connector
- 1x PCIe Connector
- 1x ON/OFF Button
- 1x RTC Connector
- 1x UART Connector
- 2x MIPI DSI/CSI Connector
- 1x PoE+ HAT Connector
- 1x microSD-Karten-Slot


----------------------------------------------------------

Raspberry Pi 5 Expansion Board Model B

![Projektübersicht](Expansion_Board_Model_B.png)

Internal:
- Cortex-M3 32-bit high-performance Arm chip
- 3-axis accelerator/ 3-axis gyroscope

Ports:

- 1x Fan Port
- 4x lane IIC Port
	- INA226 Spannungs Strom Modul über IIC-Leistungsüberwachung
	- Yahboom AI Voice Interaction Module
	- PCF8591 AD/DA Konverter Modul
		- 2x LED 
		- 1x Photoresistor LDR
		- 1x Thermistor: Zur Temperaturmessung.
 		- 1x Digital- und -Digital/Analog-Umsetzer mit vier Analogeingängen

- 2x lane GPIO Port
- 6x lane BUS Servo Port
- 2x lane PWM Servo Port
- 1x Buzzer
- 2x Function Key 
- 1x Power Port
- 1x DC Charging Port

----------------------------------------------------------
12x LX-224HV High Power Servos

![Projektübersicht](LX-224HV-Servos.png)


----------------------------------------------------------

HBVCAM-V2101 HD Wide Angle Camera 

![Projektübersicht](HBVCAM-V2101-Camera.png)

- 640x480 Resulution
- 400mW 5V
- USB 2.0

----------------------------------------------------------

Hiwonder Voltage Display Module Compatible with Hiwonder Robot
- <10mA
- Measuring range: 3 - 14 V
- Maximum input: 14V
- 3PIN Port

----------------------------------------------------------

Yahboom AI Voice Interaction Module
- I2C communication
- Serial Port
- Type C Port


----------------------------------------------------------

What should the robot can do?

It should be able to walk.
- Walks with 6-port bus servo LX-224HV-Servos 

It should be able to monitor its own battery.
- Voltage will monitor with a INA226 voltage/current module (I2C power monitoring)

It should have a camera.
- HD Wide-Angle Camera (HBVCAM-V2101 V11)

It should be able to converse with People.
- Yahboom AI Voice Interaction Module

It should be able to perceive its surroundings.
- Glowing Ultrasonic Sensor (HW-SR06)
	or
- youyeetoo LD19 LiDAR Kit (12-meter range, 360-degree view, 30k lux)




----------------------------------------------------------


Other exciting modules?

- Google Coral USB Accelerator or Intel Neural Compute Stick 2
- USB 3.0 SSD
- BME280 (temperature, air pressure, humidity)


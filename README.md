# road-mishap

## Statistics

According to 2021 data, the country had 467,044 accidents, with 151,417 people killed and 469,418 people injured. It also means that 17 people have died and 53 have been injured every hour in India.

There is full-size statistical proof that points to driver drowsiness as a main cause of road accidents all over the world. Driving for prolonged intervals of time can lead to accidents if rest is no longer taken. Drowsiness is an important purpose of vehicular accidents.


## Abstract 

The Detection of Road Mishaps project aims to develop a comprehensive system for detecting and preventing road accidents. The project utilizes Internet of Things (IoT) technology to create three essential modules: Speed Calculator, Gas Detection, and Crash Detection. By combining these modules, the project aims to improve road safety by providing real-time data and alerts to both drivers and authorities, facilitating proactive measures to prevent mishaps.

## Tech Stack

- TinkerCAD and Wokwi Simulation
- Arduino and sensors
- HTML, CSS, JS
- Google Cloud API
- Eagle for PCB Design

### Speed Calculator Module:

*Purpose*: This module is responsible for monitoring and calculating the speed of vehicles on the road. It helps in identifying vehicles that are exceeding speed limits, which can lead to accidents.

*Electronics*: The Speed Calculator module includes components such as ultrasonic sensors or radar sensors to measure the speed of passing vehicles.

*Firmware Design*: The firmware for this module is designed to read data from the sensors, calculate vehicle speed, and transmit this information to a central processing unit. The firmware should also include logic for setting speed limits and generating alerts when violations occur.

### Gas Detection Module:

*Purpose*: This module detects and monitors harmful gases, such as carbon monoxide (CO) and nitrogen oxides (NOx), which can be emitted from vehicles and pose health risks to both drivers and pedestrians.

*Electronics*: Gas sensors like CO and NOx detectors are used to monitor air quality and detect the presence of dangerous gases.

*Firmware Design*: The firmware for this module reads data from the gas sensors, processes the data to determine gas concentration levels, and triggers alerts if hazardous levels are detected. It should also include calibration routines to ensure accurate measurements.

### Crash Detection Module:

*Purpose*: This module is responsible for detecting vehicle collisions or accidents on the road. It plays a crucial role in rapidly alerting authorities and emergency services.

*Electronics*: Accelerometers and impact sensors are typically used to detect sudden changes in vehicle velocity or impacts.

*Firmware Design*: The firmware for this module continuously monitors the accelerometer data. When a significant change in velocity or an impact is detected, it triggers an alarm or sends an emergency notification to authorities and nearby drivers. It should also incorporate GPS data to provide the accident's location


### [Speed Calculator](https://wokwi.com/projects/366746748629807105)

### [Gas Detection](https://www.tinkercad.com/things/bBwrbBcnv4k)

### [Crash Detection](https://www.tinkercad.com/things/hjC9y57r7hT)

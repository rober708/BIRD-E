# BIRD-E
## Purdue University — Senior Design Capstone Project (Team E04) Semesters: Fall 2025 – Spring 2026
## Mentors: Dr Phil Walter (Purdue), Shivam Duhan (Purdue), Jonathan Lane (Purdue -> Berkley!)

The Bounded Infrared Recording Drone Ecosystem (BIRD-E) is a specialized, lightweight tethered quadcopter system equipped with night-vision capabilities. It is designed to provide rapid, temporary, and cost-effective aerial surveillance for fire departments, law enforcement, industrial engineers, and other managerial groups who may benefit from mobile sentries. By operating via a power tether, BIRD-E circumvents standard drone flight limitations of other drones in its price point (~$260).  

## Capabilities
- Pow 


Designed as a cheap alternative to other, more robust tethered drone systems, for lightweight simple recon. BIRD-E is a small, lightweight quadcopter, ideally below 250 grams, utilizing four motors in an X configuration. To minimize weight and maximize flight time, it is powered via a thin tether to a battery and housing on the ground. Imaging is provided by a night-vision camera (PiCam3 NOIR) to allow for versatile aerial inspection. Flight control is managed by the user through a simple, intuitive controller (just an offbrand XBOX controller) interfaced through a laptop, which handles wireless command transmission and live video display. On the drone itself the flight control and wireless streaming duties will be divided, with a microcontroller for flight control and a companion computer for wireless interfacing. While the operational ceiling will be limited by a 3-meter tether, the onboard sensor array, comprising a nine degrees-of-freedom Inertial Measurement Unit (9-DOF IMU), Laser Time-of-Flight (ToF) sensor, Barometric Altimeter, and Optical Flow sensor, will be capable of supporting higher altitudes. Altitude and attitude control is achieved through sensor fusion, targeting a hover precision of ±15cm altitude and ±15° yaw. As a stretch goal, it may also regulate horizontal drift utilizing the Optical Flow sensor as well as support omni-directional flight.

## Known Issues
- BNO055
    - The BNO055 is no longer manufactured. Switch to a new IMU.
- Takeoff
    - The drone will tilt at takeoff. Be sure that the surroundings are clear. It will self adjust in air, but if concerned, try to adjust center of mass. This will vary based on installation.
- USB Port
    - The USB-C port on the PCB has some trouble connecting. 
## Contributors
Andrew Robertson
Ryan Wurtz
Tiana Lin
Zachary Hsiung 

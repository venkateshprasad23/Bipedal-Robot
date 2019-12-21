# Bipedal-Robot
10-DOF Bipedal Robot.

## Description

The project was started in the year 2017 with a long-term goal of developing a humanoid robot. The initial problem statement is to build a 10-DOF, stable, static walking bipedal robot capable of traversing plane surface and is tolerant to external disturbances. A real time simulation of the walking gaits of the robot has been developed to serve the purpose of a testing platform for various gaits, mechanisms and control algorithm.

The robot was designed in PTC Creo and simulated in MATLAB-SimMechanics on which motion planning and control algorithms were implemented for developing the static walking gait. In this gait the robot is made to be in static equilibrium throughout its motion. Mechanisms such as parallelogram linkages, belt and gear drives were developed for actuating the 2 DOF joints at ankle and hip. The fabrication of the real life prototype based on the simulation results is completed. Currently, we are developing the trajectories for the gait of the bipedal robot.

### Code Organisation

```
Biped Alfa Folder  -- Contains the CAD model and the MATLAB SimMechanics file for the basic model that was created first.
Biped Bravo        -- Contains the second, more advanced model and its matlab file and codes.
MATLAB Libraries   -- Contains many useful libraries, one of them being the Contact Forces Library.
```





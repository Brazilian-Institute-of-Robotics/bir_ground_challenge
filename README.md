# bir_ground_challenge

This repository supports the development of the ground robotics challenge from [RASC](https://www.braziliansinrobotics.com/).

**Keywords**: Challenge, Ground-robotics, Turtlebot3

**Author**: [Anderson Lima](https://github.com/aldenpower) <br/>
**Affiliation**: [RASC](https://www.braziliansinrobotics.com/) <br/>
**Maintainer**: [Anderson Lima](https://github.com/aldenpower), eng.andersonfsl@gmail.com

## Justification

Developing skills and knowledge in navigation is very important for a researcher in the field of robotics, in view of the growth of mobile robotics applied to the theme "robots in terrestrial environment", it is necessary to develop mechanisms that solidify knowledge in a practical way. Concepts such as *SLAM, State-machine, computer vision and localization* are quite recurrent in this context, so, the **Heavy Hull** challenge proposes the systematic application of these concepts in order to strengthen future developments.

## Objective

The objective is to carry out the [mission](#mission) obeying the [prerequisites](#prerequisites).


## Mission

The [**Turtlebot 3**](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) must go through a delimited [environment](#Environment) starting at the start point highlighted in the [figure](#figure), being positioned with the camera facing away from the entrance. The mission environment is similar to a labyrinth, composed of two corridors and with the 3 previously placed [fiducial markers](#aruco-fiducial-marker). The robot must go through the environment completely and reach the end point, at the end of the route (arrival at the final point) there will be an [object](#object) that must be identified.

### Environment

#### figure

![figure](./source/envedited.png)

### Object

### ArUco fiducial marker

## Prerequisites

- The challenge must be performed using [ROS2](https://docs.ros.org/en/foxy/index.html)
- For autonomous navigation, ***state-machine*** must be used
- The environment must be built
- The robot must build the [environment](#environment) map while executing the [mission](#mission)
- The robot must use **three** [fiducial markers](#aruco-fiducial-marker) for localization that must be present in the environment




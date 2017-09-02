# Control System for the Neato-based Chairbot

The software here enables two types of control for the neato-based chairbot:
1. Control using Computer Vision-based path-finding algorithm.
2. Control using iPad WASD-like control. 

Both of these control methods use an iPad as the interface.

# Architecture

These are the separate modules:
1. Control System: Where the OpenCV code lives, as well as a server for communicating with the iPad.
2. Chairbot iPad interface: The iPad app.
3. Raspberry Pi server: This receives instructions from iPad and/or the OpenCV code and then pipes that into the neato.

Please visit the wiki for more instructions on the architecture.

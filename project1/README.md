# Project 1

This project's goal is to build a world with walls and a robot model with joints and simple helloworld code

I built a simple 3-wheel car similar to a car I bought from a kit called Freenove as I intend to port the software to it afterwards for some hobby projects


## Project directories:

### `model/floor/`
Contains a floor design with walls in wood texture and in orange colors
### `model/threeWheeler/`
Contains a 3-wheeled car model
### `script/welcome.cpp`
a simple world plugin that prints welcome to Ahmad's world
### `world/myworld/`
a world including:
- two instances of my car
- several tiers imported from gazeob's online model library as obstacles
- my floor

### To run the world plugin:
- $ cd to project1 directory
- $ mkdir build
- $ cd build/
- $ cmake ../
- $ make
- $ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/path/to/the/build/directory

then 
- $ cd to project1/world directory
- $ gazebo myworld

You should see a message "Welcome to Ahmad's world!" printed in the terminal and the world is opened in gazebo
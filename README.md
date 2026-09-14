# Grasping-Object-Manipulative-Robot
# CNN for Mobile Robotics (Manipulative Robot)
This project demonstrates a vision-based mobile manipulative robot simulation using Python, PyBullet, and Google Colab.
---------------------------------------------------------------------------------------
## Features

- RGB-based visual perception
- Object identification using visual features
- Color, shape, and size based target selection
- Robotic arm motion using PyBullet
- Inverse kinematics for reaching the selected target
- Pick and carry operation
- Physics-based object interaction
- Interactive widgets for selecting targets

## Objects

The simulation contains seven objects with different combinations of color, shape, and size:

- Small Green Box
- Big Green Box
- Small Red T-Shirt
- Big Red T-Shirt
- Small Blue Bottle
- Big Blue Bottle
- Yellow Ball

## Requirements

The project is designed to run in Google Colab.

Required Python packages:

- PyBullet
- ipywidgets

## How to Run

1. Open the notebook in Google Colab.
2. Run the installation/setup cell.
3. Run all notebook cells.
4. Select a target using the widget.
5. Start the robot motion.
6. The robot approaches, reaches, picks, and lifts the selected object.

## Note

The current implementation uses a visual feature embedding based on color, shape, and size. It is a demonstration of the perception and robotic interaction pipeline and does not represent a trained CNN model.

## Platform

Google Colab + Python + PyBullet

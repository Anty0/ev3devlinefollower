# EV3dev Line Follower

During high school studies, I had the opportunity to attend a few line follower competitions as a member of the robotics club. This project is my first attempt at implementing a line follower in Python using ev3dev as OS.

One notable feature included in this codebase is that the program would scan the surface under the robot before starting and adjust the low and high thresholds based on the surface reflectivity. In future versions I used this info to adjust starting position of the robot so that I don't have to manually place it exactly on the line (just close enough). Since most of the competitions started measuring time from the moment the robot crossed the starting line, there was quite a lot of time for robot to prepare and adjust itself before starting the actual run.

## Requirements

You'll need to install the ev3dev OS on your EV3 brick. You can find the instructions on the [ev3dev website](https://www.ev3dev.org/docs/getting-started/).

## Usage

To run the program, simply execute the `line_follower.py` script. The robot will start scanning the surface and then hopefully start following the line.

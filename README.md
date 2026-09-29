# Introduction to Robotics

> **Original version:** this README and some fixes were added in 2026. To see the project exactly as it was first built, browse commit [`db210dc`](https://github.com/dianapaula19/introduction-to-robotics-course/tree/db210dcfaca9fcc71a6ae9761cee92e5e3ee4e3f) (2020-03-09).

Arduino projects from the *Introduction to Robotics* course at the University of Bucharest
(2019–2020): from blinking LEDs to a wireless candy claw machine.

| Project | What it is |
|---|---|
| [Candy claw machine](FinalProject/) | Final project with [@IoanaBajan](https://github.com/IoanaBajan): an arcade claw machine built from Lego, plexiglass and nylon wire. Two joysticks on a separate console steer the claw over nRF24L01 radio, an LCD shows the timer, and ultrasonic sensors detect the coin. |
| [Akira Breakout](MatrixGame/) | Breakout on an 8×8 LED matrix, themed on the film *Akira*, with a menu on an LCD, three difficulty levels and a motorcycle race mode. Object-oriented C++ split into classes (`Ball`, `Paddle`, `Menu`, `Race`, ...). |
| [Lab homework](LabHomework/) | RGB LED controlled by potentiometers, a knock detector with buzzers, joystick control of four 7-segment displays, and an LCD game menu. |

![Claw machine electronics](FinalProject/Images/image_1.jpg)

Open any `.ino` file in the Arduino IDE to build it; the hardware list for each project is in
its README.

# Maze solver and a Bluetooth car

In this project, we made a Bluetooth-controlled car which, with a toggle button on the phone, goes into autonomous maze-solving mode.


## Engineering Description:

Working on a previously built Bluetooth car, we understood the flaws in the design of the car and implemented them in this car alongside the ability to solve basic mazes (following wall following rule).

We replaced the complex steering mechanism with a roller ball, and the independent turning of rear wheels now controls the direction of motion in the car.

The maze solver mode uses the ultrasonic sensor attached to the servo to check the distance between the bot and obstacles. 
Initially, it faces forward, and the bot moves forward, but as soon as the bot senses the obstacle, it stops, checks left and right for obstacles and moves in the direction with no obstacles.


## Some photos we shot while making the bot:

![20220813_221715](https://github.com/ChiragKotian/Maze-solver-and-bluetooth-car/assets/117931123/34f9d3f1-88c3-4a45-8a2f-c9e43cb38eee)
![20220813_221712](https://github.com/ChiragKotian/Maze-solver-and-bluetooth-car/assets/117931123/099e123d-8e3c-40cd-a919-94d49d3aa869)
![20220813_221709](https://github.com/ChiragKotian/Maze-solver-and-bluetooth-car/assets/117931123/6576466c-13d9-4b87-bddb-d3cdd46b2041)
![20220813_205036](https://github.com/ChiragKotian/Maze-solver-and-bluetooth-car/assets/117931123/d3a02def-b52b-4180-a447-a9d735f77266)
![20220813_205031](https://github.com/ChiragKotian/Maze-solver-and-bluetooth-car/assets/117931123/04648ce1-c0b9-44b8-8ef7-f803aab0c055)

## Credits:
_This was made by [Chirag Kotian](https://github.com/ChiragKotian), [Arpit](https://github.com/arpitguptagithub) and [Aman Kumar](https://github.com/Amankumar8555)._

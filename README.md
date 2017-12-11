## Relativity Space - Automation engineering candidates' project
This readme contains a project that candidates can work on as a take-home project

### Instructions:
1. Solve the problem from this repo
    * Depending on your time and level of enthusiasm about the problem you can choose to do only parts of the problem
2. Once done, email the results requested back to your interviewer.

Open an issue on this repo if you have any questions about the problems.

Adding clarification and description readme file or comments in code is welcomed if needed.

### Project : Line Follower Robot
The goal of the assignment is to determine all equipment needed and write code for a line follower robot. The workings of a line follower robot are pretty straightforward. These robots have the capability to detect a black/dark line on a lighter surface depending on the contrast. They estimate whether the line underneath them is shifting towards their left/right as they move over them. Based on that estimation, they give respective signals to the motors to turn left/right so as to maintain a steady center with respect to the line.

![Line Follower robot](/images/line_follower.png)

These robots usually use an array of IR (Infrared) sensors in order to calculate the reflectance of the surface beneath them. The basic criteria being that the black line will have a lesser reflectance value (black absorbs light) than the lighter surface around it. This low value of reflectance is the parameter used to detect the position of the line by the robot. The higher value of reflectance will be the surface around the line. So in this linear array of IR sensors, if the leftmost/rightmost IR sensor presents the low value for reflectance, then the black line is towards the left/right of the robot correspondingly. The controller then compensates for this by signaling the motor to go in the opposite direction of the line.

Determine all equipment needed to build this robot, including motors and sensors. The control code should be written in structured text. Bonus points if the delivered project is working TwinCAT 3 project. Feel free to choose proper Beckhoff equipment if you choose to use Beckhoff for your control (encouraged).

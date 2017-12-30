# RaspberryCar
Developed, in a team of three people, a remotely controlled car using Python and Raspberry PI. 

It provides hand gesture interaction so that users can control the robot’s movement by practicing their dexterity.
Car can move in various directions with different speeds.

The guiding path is collected from Touch Display and the speed of car is proportional to speed of finger. The path initially is saved as list of coordinates, obtained from Touch Display by requesting coordinates every 2 time clocks. Speed, length and direction are obtained from this list by chessboard principle:

All coordinates are distributed through 64 squares of a chessboard, if present coordinate moves from ith-jth square to i+1st/jth square we count how many time was taken by a movement and decide the speed. According to speed and direction car moves straight or makes number of required turns.

![ ](RaspberryCarInProgress.gif)
![ ](aspberryCarInProcess.jpg)

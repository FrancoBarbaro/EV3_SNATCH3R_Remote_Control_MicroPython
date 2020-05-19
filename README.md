# EV3_SNATCH3R_Remote_Control_MicroPython
Infrared remote control program for ev3dev2 based on the robot design and program from the 'SNATCH3R' section in "The Lego Mindstorms EV3 Discovery Book" by Laurens Valk

The purpose of the program is to control the EV3 via infrared remote.

While the program is based on the one in Valk's book, it does have some modifications so that the program is more capable:

The first 3 remote channels all have the same functions, but make the robot operate at different speeds. Pressing the two top buttons at the same time will make the robot go forward, pressing the two bottom buttons at the same time will make it go backward, the top right button will make the robot turn right, the top left button will make it turn left, the bottom right button will open the claw, and the bottom left button will close it. Channel 1 makes the motors run at 50% speed, channel 2 runs them at 75% speed, and channel 3 runs them at 100% speed. If any button is pressed on channel 4, the program will stop.

In the original program, only channel 1 of the remote is used and the only speed the motors run at is 50%, there is also no way to stop the program via the remote.

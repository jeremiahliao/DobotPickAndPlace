# DobotPickAndPlace
Updated code to the original Dobot Pick and Place Code

Edited program code for the Dobot Pick and Place routine. Changes were made in the following files:
 - Grab_PartsFinal.ino
 - command.cpp

The voltage values for the lcd keypad shield were different from the original code. We changed the code to match the voltage values in the existing lcd keypad shield so that when the buttons were pressed, the program reflected the correct buttons.

We had an error with the suction cup and gripper not activating when called. We went into the command.cpp file to change the function so that it sent the correct packet to the Dobot in order to activate the air pump correctly.

Aspects to keep in mind BEFORE printing:

	--> In the Slicer, delete the part "Spacer-SteerLeverBallJointSphereHub" and all the parts named "KörperX". You only need "BallJointSphere", "BallJointSphere (1)" and "RightSteerRod".
	--> PLA works good. (PETG might has a too strong layer-adhesion for the spherical bearing, but I haven´t tried it.)
	--> NO SEAMS inside the spherical print-in-place bearing, beacause they might bond together. (Do that with "seam painting"; example pictures in folder "seam_painting".)
	--> .15 layerheigth is recommended for the spherical print-in-place bearing. (I used .30 layerheight for the object, but .15, where the spherical bearing is, by using "variable layer height".)
	--> Make sure, the part-cooling fan runs at 100 % when "BallJointSphere" and "BallJointSphere (1)" start printing. [To ensure that, I manually moved the "M106 255"-command (100 % part-cooling fan, triggered by start of bridging) up a few lines in the .gcode-file by using a text editor. This way, the fan can accelerate to the desired 100 %, before the critical printing starts. So the fan definitely is at 100 % when the bridging starts. Explained with pictures in the folder "move_fan_command".]  

Print "SteerRod" two times, no need to differentiate between "RightSteerRod" and "LeftSteerRod" since they are exayctly the same.
Print the "Spacer(Hub-SteerRod) two times.

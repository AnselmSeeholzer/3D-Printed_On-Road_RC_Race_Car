Aspects to keep in mind BEFORE printing:

	--> In the Slicer, delete the all the parts named "KörperX".
	--> PLA works good. (PETG might has a too strong layer-adhesion for the spherical bearing, but I haven´t tried it.)
	--> NO SEAMS inside the spherical print-in-place bearing, beacause they might bond together. (Do that with "seam painting"; example pictures in folder "seam_painting".)
	--> .15 layerheigth is recommended for the spherical print-in-place bearing. (I used .30 layerheight for the object, but .15, where the spherical bearing is, by using a layer height modifier.)
	--> Make sure, the part-cooling fan runs at 100 % when "BallJointSphere" starts printing. [To ensure that, I manually moved the "M106 255"-command (100 % part-cooling fan, triggered by start of bridging) up a few lines in the .gcode-file by using a text editor. This way, the fan can accelerate to the desired 100 %, before the critical printing starts. So the fan definitely is at 100 % when the bridging starts. Explained with pictures in the folder "move_fan_command".]  
	--> Some extra support material is probalby needed.

Print "RightUpperWB" and "LeftUpperWB".

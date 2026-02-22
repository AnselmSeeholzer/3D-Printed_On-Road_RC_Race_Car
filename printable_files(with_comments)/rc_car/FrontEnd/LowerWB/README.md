Aspects to keep in mind BEFORE printing:

	--> In the Slicer, delete the parts "Ball1", "Ball2" and all the parts named "KörperX". You only need "BallJointSphere", "LowerWB" (and if you want to use the built in support: "SupportMaterial1", "SupportMaterial2, "SupportMaterial3". The z-distance between supports and objects can be adjusted in Fusion360 with the parameters "SupportTopContactZDistance" and "SupportBottomContactZDistance". Standard-value is 0.3 mm for both.)
	--> You will most likely need additional support material in two places. Those are highlighted blue in the picture "support_material" in the folder "support_material".
	--> PLA works good. (PETG might has a too strong layer-adhesion for the spherical bearing, but I haven´t tried it.)
	--> NO SEAMS inside the spherical print-in-place bearing, beacause they might bond together. (Do that with "seam painting"; example pictures in folder "seam_painting".)
	--> .15 layerheigth is recommended for the spherical print-in-place bearing. (I used .30 layerheight for the object, but .15, where the spherical bearing is, by using a layer height modifier.)
	--> Make sure, the part-cooling fan runs at 100 % when "BallJointSphere" starts printing. [To ensure that, I manually moved the "M106 255"-command (100 % part-cooling fan, triggered by start of bridging) up a few lines in the .gcode-file by using a text editor. This way, the fan can accelerate to the desired 100 %, before the critical printing starts. So the fan definitely is at 100 % when the bridging starts. Explained with pictures in the folder "move_fan_command".]  
	--> Some extra support material is probalby needed.

Print "LowerWB" two times, no need to differentiate between "LeftLowerWB" and "RightLowerWB" since they are exayctly the same.
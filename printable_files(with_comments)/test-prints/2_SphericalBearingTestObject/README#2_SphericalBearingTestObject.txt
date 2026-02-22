

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!! Print with similar settings to the "real print" !!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


The second and final test print is a print-in-place spherical bearing, used in the front suspension.

YOU HAVE TO use the "seam painting" feature in your slicer according to the two pictures in this folder! 
Otherwise the inner sphere and the outer ring probably bond together.

After printing, you should be able to break the inner sphere loose from the outer ring.
By rotating the spherical bearing a few times you smooth the surfaceses and it should moce freely.
Apply some grease now.

If it is too tight or loose, adjust the parameters as explained in README#1, edit the gcode fan command and print the test again.

My own optimal parameters are:

	PrintInPlaceBallJointHoleDia = 0.33 cm
	PrintInPlaceBallJointTolerance = 0.022 cm

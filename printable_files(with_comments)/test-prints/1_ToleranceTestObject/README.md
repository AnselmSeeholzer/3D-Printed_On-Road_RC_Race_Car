!!!!! Print with similar settings to the "real print" !!!!!

The first test print is an object to determine wether my parameters fit yours or if they need to be adjusted. 

Print the ToleranceTestObject and check if your hardware fits in the holes.
In the image "xxx" you can see where to put which nut/bolt/bearing/insert.

If some features in this print are too wide or narrow, you can adjust the according parameters in Fusion360 and export the ToleranceTestObject again.

Only adjust the parameters mentioned in the README. Adjusting other parameters might cause conflicts in Fusion360s timeline.
Here are my personal parameter values and the ranges in which each parameter can can safely be modified:

	M2InsertDia = 0.3 cm	M2 threaded brass insert diameter (tested in Fusion360 from 0.28 cm to 0.35 cm)

	M3HoleDia = 0.31 cm	M3 hole diameter (tested in Fusion360 from 0.29 cm to 0.36 cm)
	M3InsertDia = 0.41 cm	M3 threaded brass insert diameter (tested in Fusion360 from 0.29 cm to 0.36 cm)
	M3NutS = 0.565 cm	M3 nut measured side to side (tested in Fusion360 from 0.54 cm to 0.61 cm)
	M3SquareNutS = 0.57 cm	M3 square-nut measured side to side(tested in Fusion360 from 0.54 cm to 0.61 cm)

	M4HoleDia = 0.41 cm	M4 hole diameter (tested in Fusion360 from 0.39 cm to 0.46 cm)
	M4NutS = 0.71 mm	M4 nut, measured side to side (tested in Fusion360 from 0.69 cm to 0.76 cm)

	Bearing963Dia = 0.81 cm	(963 bearing diameter) (tested in Fusion360 from 0.78 cm to 0.86 cm)
	BearingMR105Dia = 1.0125 cm (MR105 bearing diameter) (tested in Fusion360 from 0.98 cm to 1.06 cm)

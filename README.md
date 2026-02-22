# 3D-Printed On-Road RC Race Car

**By Anselm Seeholzer**

With this 3d-printable RC-car I took part in the 2025 *Instructables Autodesk Make it Move Engeneering Student Contest* and the RC-car has won the *3D Printing Judge`s Price*.  

Detailed building instructions with a complete .f3z-file can be found on the [Instructables](https://www.instructables.com/3D-Printed-On-Road-RC-Race-Car/) website. The Instructable (without pictures and .f3z-file) was also transferred in this repository with printable .3mf-files.  

Videos can be found here:
[Video1](https://youtu.be/ogYVA5u91Qc?si=TGJ7EXKurzWOe1Sa)
[Video2](https://youtu.be/yxx4tnBufh8?si=RkOAHaVWVVsFRw-e)
[Video3](https://youtu.be/c6_NunxIvkY?si=fuwjfYf_-NPKvzkU)

![full_car_photo](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/full_car.jpg?raw=true)  
![full_car_render](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/RC-Car2.1_2026-Feb-22_01-52-54PM-000_CustomizedView59793026783_png.png?raw=true)  
![full_car_render](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/_N6A6480.jpg?raw=true)  
![full_car_render](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/RC-Car2.1_2024-Dec-23_02-33-14PM-000_CustomizedView47922860305_png.png?raw=true)  
![full_car_render](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/RC-Car2.1_2024-Dec-24_03-17-26AM-000_CustomizedView21425786976_png.png?raw=true)  
![full_car_render](https://github.com/AnselmSeeholzer/3D-Printed_On-Road_RC_Race_Car/blob/main/pictures_renders/RC-Car2.1_2025-Jan-12_12-16-02PM-000_CustomizedView33869473790_jpg.jpg?raw=true)  

---

## Introduction

This project showcases a 3D-printed RC race car that I designed and refined over the course of 18 months. As a physics student with a passion for vehicle dynamics, I wanted to combine my love for cars with hands-on learning. Inspired by YouTube creators like XF Motorsports, Indeterminate Design and the book Tune to Win by Carroll Smith, this project allowed me to explore the fascinating and complex field of vehicle dynamics.

The idea behind this project was not just to create an RC car, but to design one that reflects core principles of performance and handling. Through this process, I learned how concepts like weight distribution, suspension geometry, and grip dynamics work together to affect a vehicle's behavior. This Instructable is a step-by-step guide to building your own RC car, while also offering insights into the design decisions.

While designing and printing an RC car might seem challenging, I've optimized most parts to be straightforward to print -- even on a less-than-perfectly calibrated 3D printer. All holes for every bolt, nut, bearing and every tolerance are designed parametrically, so every feature's size can be easily adjusted to your likings in Autodesk Fusion. To determine if the parameters need to be changed, I have designed two test objects which use less than 10 g of filament to print.

---

## Project Goals

The main goals and conditions for this RC car were:

- **On-Road Focus**
  This car is purpose-built for smooth, on-road surfaces. Off-road capabilities were intentionally not prioritized.

- **Responsive and Predictable Handling**
  The car should feel intuitive and smooth to drive, allowing the driver to push it to its limits. Oversteer and understeer should be intentionally controllable, making it possible to explore the edge of grip and maintain a challenging driving experience.

- **Rear-Wheel Drive with Differential**
  A rear-wheel-drive setup was chosen for simplicity and driving fun. A differential ensures that the rear wheels rotate at different speeds during cornering, minimizing unwanted slip.

- **Optimized Weight Distribution**
  All heavy components are placed close to the car's center to reduce rotational inertia.

- **Efficient Suspension Design**
  The suspension is designed to maximize the contact area between the tires and the ground in all conditions (cornering, bumps, etc.), which increases grip. Internal friction at linkage points is minimized by using ball bearings or spherical bearings, enhancing the suspension's efficiency.

- **Ease of Maintenance**
  The car's design ensures that components are easily accessible for servicing and replacing parts.

---

## Why I Built This Project

I've always been fascinated by all kind of vehicles on wheels like stunt scooters, mountain bikes and more recently race cars. The physics involved in driving dynamics and car design offer a unique mix of theory and practical application. My interest deepened after watching DIY race car projects on YouTube and reading Tune to Win, which provides a great introduction to vehicle dynamics.

As a physics student, I already had a good understanding of basic physical concepts like force, torque, inertia and momentum. However, vehicle dynamics is a nuanced and complex field, and I wanted to expand my knowledge through hands-on experimentation. Designing this RC car from scratch was the perfect way to bridge theory and practice.

---

## Design Principles

The design process was guided by key engineering principles to ensure the car performs well on the track. Here are some highlights:

- **Suspension Geometry**
  The suspension layout takes into account critical factors like camber, bumpsteer, caster angle, and roll center position.

- **Ackermann Steering**
  The steering geometry approximates Ackermann principles, ensuring the wheels turn at the correct angles for smooth cornering.

- **Bump Steer Mitigation**
  The steering system is designed to minimize bump steer, which could cause unpredictable handling when the suspension compresses.

I measured different geometry layouts in Autodesk Fusion by using 2D sketches. This Data was put into spreadsheets to analyze the suspension geometry and simulate different scenarios (e.g., cornering, bumps). The tables and graphs of the final layout are attached to this Instructable for anyone interested in the technical details. For those who are interested I go into more detail of some design choices in the last chapter of this Instructable.

---

## Challenges and Lessons Learned

### 1. Learning About Vehicle Dynamics

Throughout this project, I learned a lot about vehicle dynamics. The car performs well and is fun to drive, as you can see in the videos. However, it's difficult to say which specific design choices contributed the most to its handling. What I can confidently say is that the combination of decisions led to a car that feels smooth and responsive.

That said, I'd love to have someone with more RC car experience -- either as a hobbyist or a professional -- test drive it. They could provide valuable feedback and a more objective comparison to other RC cars. My last time driving an RC car before this project was over 10 years ago, so my frame of reference is somewhat limited.

### 2. 3D Printing: My First Major Project

This RC car was my first major 3D printing project. Unsurprisingly, the first prototypes had plenty of beginner mistakes. I underestimated how much of a difference fine-tuning print settings like speed, acceleration, cooling, and flow rates could make. Early on, some parts didn't fit together as expected, which led me to explore slicer configurations and better understand how to achieve precise tolerances.

With each iteration, I refined both the design and the print quality. By the end, I had not only a functional RC car but also a much better understanding of 3D printing and prototyping.

### 3. Learning CAD with Autodesk Fusion

This project was also my first big CAD undertaking and only my second project in Autodesk Fusion. Having no prior CAD experience, I encountered a steep learning curve. Here are the main takeaways:

- **2D sketches for Suspension Layout:** Using 2D sketches to define the car's geometry and suspension layout helped me visualize and plan the relationships between components before moving on to 3D parts.
- **Evolving Design Skills:** As I gained more experience with Fusion 360, I discovered new tools and features. Consequently, parts designed later in the project were more refined compared to the earlier ones, which often felt clunky or inconsistent.
- **Ignoring Manufacturability:** Early on, I didn't consider the practical aspects of 3D printing or assembly. Some designs looked good in Fusion but turned out to be challenging to print or assemble.
- **No Parameters at First:** I initially didn't use parameters for dimensions because I didn't know about their existence. This meant I had to manually update dimensions across multiple parts when making changes. The repetitive adjustments were time-consuming and inefficient. Learning to use parameters was a game-changer for speeding up revisions and maintaining consistency.

Because of my steep learning curve in Autodesk Fusion and 3D printing, I decided to start the project with the same suspension geometry from scratch again and redesign every single part - and it was definitely worth it. The redesigned RC car features a cohesive look, with parts that are both easy to print and structurally robust. But still, I learned a lot this time too.

---

## Reflection

Looking back, this project wasn't just about building an RC car -- it was also an intensive learning experience in 3D printing, CAD design, and engineering principles. While there were plenty of mistakes along the way, each one was an opportunity to learn and improve.

---

## Supplies

### Tools

- 3d printer (I used Sovol SV07)
- approx. 500 g PLA
- approx. 400 g TPU/ tough PLA/ any impact resistant filament
- soldering iron
- soldering iron tips for setting brass inserts
- tools for your screws (I recommend Torx drive) and nuts
- some grease

### RC-specific hardware

- 4x HSP Wheel Axle 1/10 (part number 02033)
- 4x HSP Hub 1/10 with bearings (part number 02014)
- 2x HSP Dogbone 77 mm (part number 08060) (You need the Dogbone advertised as 77 mm length. Its distance between the center of the pins is actually 72 mm.)
- 1x HSP Differential (part number 02051) (The front version *with the long shaft* is needed. You can also use the rear version and simply buy a separate long shaft.)
- 4x 1/10 tires (approx. 70 -75 mm outer diameter) (You can also use standard HEX12 RC car rims instead of the 3d printed rims of this model)
- 4x shock absorbers 50 mm (I recommend getting a relatively good one with different springs (having the right spring rate is super important) and oil dampening. I use "Yeah Racing Big Bore Go".
- 1x transmitter/receiver combo, ESC and 540 motor. I use "Carlson Reflex X1", "Hobbywing 1060" and "Tamiya Torque Tuned".
- 1x gear for motor and differential each. The differential has an internal gearing of 1:3. Use a gearing compatible with your motors KV rating. I use a 21 teeth 48 dp motor gear and a 43 teeth 48 dp differential gear. So my total gearing is 1:6.143. The differential gear's diameter must be below 2 cm.

### General hardware

- M2 flat head screw:
  - 8 mm (any length between 8 and 12 mm) (1x)
- M2 brass insert (length 3mm) (1x)
- M3 flat head screws:
  - 6 mm (2x)
  - 8 mm (12x)
  - 12 mm (8x)
  - 14 mm (4x)
  - 16 mm (4x)
  - 20 mm (8x)
  - 22 mm (6x)
  - 25 mm (2x)
  - 30 mm (2x)
  - 45 mm (4x)
  - 60 mm (6x)
- M3 socket head screws:
  - 18 mm (2x)
  - 20 mm (2x)
- M3 ultra thin head
  - 8mm (4x)
- M3 brass insert (length 5.7 mm) (26x)
- M3 lock nut (18x)
- M3 square nut (2x)
- M3 washer (diameter 6.7 mm) (25x)
- M4 socket head screw
  - 16mm (4x)
- M4 lock nut (8x)
- M4 washer (diameter under 12 mm) (4x)
- Bearing 963 (x18)
- Bearing MR105 (1x)

---

## Step 1: General Print Settings and Assembly Tips

Because we want our parts to be strong, a few print settings are very important.

To achieve a good adhesion between the layers, I print most parts without the use of my part cooling fan. Only when bridging occurs, I set it to 100%. Additionally, printing at a low constant flow rate has shown very good results in my experience. Furthermore over extruding the print a small amount has also shown to improve layer adhesion by filling in small voids that occur between layer lines. Regarding temperatures, I printed in the higher end of the manufacturers recommendation. In a video of CNC Kitchen on YouTube, "Transparent FDM Prints are Clearly Stronger!", the reasons behind this are explained perfectly. I print at slow 3 mm3/s on a 0.6 mm nozzle with a 0.3 mm layer height, but consistently achieve good results this way. Furthermore I use a random seam positioning, in order to avoid having weakspots on a continuous seam, but more importantly, bearings are really concentric in their holes and do not get pushed to one side, because of an aligned seam.

You also have to print some cylindrical spacers. Because of their small size, their diameter us usually smaller than intended to after printing. If that's the case with your printer, you can scale the spacers in the x-y-plane up in your slicer. I found it helpful for the assembly process, when the M3 screws tap a small thread in the spacers, so they don't fall off the screw while assembling.

All parts are printed with PLA if not stated else.

For reference, I attached a file with the material and mass of each part (not including any hardware) I printed.

A small safety precaution: wear protective glasses when removing supports.

*Attachment: material_and_mass_of_each_part.pdf*

---

## Step 2: Test Object 1

It may be a bit boring to start this way, but this print ensures that all prints happening afterwards will come out well calibrated according to your printer.

The first print is "TestObject1". Slice it with the settings you are going to use with the rest of the parts and print it. Check if all the hardware fits in the holes as shown in the pictures. The bearings should have a tight fit.

If everything works, you can move on to "Step3: Test Object 2".

If something does not fit, the according parameter has to be adjusted in Autodesk Fusion (the parameters marked as favorites), the "TestObject1" has to be exported from Autodesk Fusion and sliced and printed again. If everything fits now, you can move on to "Step3: Test object 2", if not, you have to readjust and reprint the test object.

In the Fusion project exist three errors related to changing the parameters I wasn't able to solve. They do cause any issues with the model.

---

## Step 3: Test Object 2

The "TestObject2" determines the tolerance needed for printing a spherical joint used in the front wishbones and steer rods.

Printing this spherical joint as a print-in-place object is the most advanced print of this project. The sphere has to be printed "in air" without adhering much to its frame underneath or to the sides because of the placement of seams. If the sphere bonds too much to its frame, it can't be broken free and can't move.

Having a smaller height helps a lot. So you have to set your layer height to a maximum of 0.15 mm.

To print this object in the best way, we have to place the seams in the right spots and manually edit a few .gcode lines.

In your slicer, use paint-on-seams to place the seams as shown in the pictures 4 and 5. The blue lines represent where the seams are set. The seams shouldn't be touching the walls next to each other from the sphere and the frame.

After exporting the .gcode search in your slicer-preview for the .gcode-command that starts printing the sphere (picture 6). At this point in the print, the part cooling fan should be running at 100 %. But because I print everything else with the part cooling fan at 0 %, it needs to accelerate to that 100% rpm first and this takes 1 to 2 seconds. So when the 100 % part cooling is actually needed, I get an fan than is in the 0 to 20 % rpm range. That causes the sphere to bond to its frame.

To tackle this problem, I basically moved the command for the fan to go to 100 % up a few lines, so it definitely is at 100% rpm, when I need it to be.

You have write down the .gcode-line that starts printing the sphere. After that, open up the .gcode-file using a text editor like Notepad++ and search for that exact .gcode-line (picture 7). One occurrence should pop up (that's exactly where your sphere starts printing). Above the given .gcode-line should be the command "M106 255" and/or "SET_FAN_SPEED FAN=extruder_partfan SPEED=1". Those commands set the part cooling fan speed to 100 %. Simply copy that command, and insert it a few lines above (picture 8). This way the fan starts accelerating earlier. Save the file, and you are good to print.

After printing, check if a M3 screw can fit the hole. I prefer slightly tighter tolerances for these holes to ensure a precise concentric fit. If it doesn't fit, adjust the parameter "PrintInPlaceBallJointHoleDia" in Autodesk Fusion in the same way as described in "Step2: Test Object 1". Following up, gently try to break the sphere free from its cage, using a HEX drive. (Wear protective glasses! If the sphere adheres too much to its cage and you break the part, something can fly towards your eyes.)

If the sphere adheres too much to the cage or if it even feels too loose, adjust the parameter "PrintInPlaceBallJointTolerance" in Autodesk Fusion in the same way as described in "Step2: Test Object 1" and export the model. Don't forget that you unfortunately have to redo the seam painting and g.code-editing. (Having a post-processing-script that automatically moves the fan command is something I'm planning to do in the future.) Reprint it and check the tolerances again.

If the parameters finally fit your printer, you can move on to the next step.

---

## Step 4: The Front Lower Wishbones

While being in the work flow for editing .gcode, we start with the only three parts of this project that need this kind of attention, the front wishbones and steer rods. We start by printing the lower wishbone.

We again have to...

- ensure the layer height is not greater than 0.15 mm where the sphere prints,
- paint the paint-on-seams the way we did in the test print,
- manually move the fan command in the .gcode the way we did in the test print.

After printing the part, the support structures must be removed by using pliers and a small hex drive (pictures 5-8). Gently try to break the sphere free from its cage, using a HEX drive (pictures 9 and 10). Mount the shock by using a M3 square nut and a M3 socket head 20 mm screw (pictures 11 and 12).

After successfully assembling one front lower wishbone, repeat the process again, as the right and left versions of this part are identical. Only the shock has to be mounted the other way.

---

## Step 5: The Front Upper Wishbones

The process is identical to the one from the step before. We again have to...

- ensure the layer height is not greater than 0.15 mm where the sphere prints,
- paint the paint-on-seams the way we did in the test print,
- manually move the fan command in the .gcode the way we did in the test print.

After printing the part, the support structures must be removed by using pliers. Gently try to break the sphere free from its cage, using a HEX drive.

Mirror the part in your slicer and repeat the process again, as the right and left versions of this part are not identical but symmetrical. Mirroring the part in your slicer saves you time (compared to slicing the right and left part separately), because you don't have to do the seam painting again.

---

## Step 6: The Steer Rods

This is the last part, where .gcode editing is needed.

Again, the process the same as before just with two (!) spherical joints per part. We have to...

- ensure the layer height is not greater than 0.15 mm where the sphere prints,
- paint the paint-on-seams the way we did in the test print,
- manually move the fan command in the .gcode the way we did in the test print.

After printing the part, gently try to break the sphere free from its cage, using a HEX drive.

Simply print this part twice, as the left and right versions are identical.

---

## Step 7: The Front Base

The next part to be printed is the FrontBase.

You have to use some supports when printing it. I recommend using tree supports. Remove them by using pliers.

Use a relatively long M3 screw, a M3 nut and washers (I only use a washer on one side in this example, but it is better to use one on each side) to press the 963 bearings in place without forgetting the bearing spacer, which needs to be inserted between both bearings for smooth operation.

Repeat the process for the other bearings.

---

## Step 8: The Assembly of the Front End 1 (Wishbones)

In this step, all the parts we have printed until now get assembled together, beginning to build the front end of the car.

Start by inserting a M3 lock nut into the front lower wishbone. Mount the front lower wishbone to the front base by using a M3 flat head screw (45 mm). Ensure that you choose the right side by checking if the mounting points for the shock are aligned. Following up, insert a M3 lock nut in the front upper wishbone and mount it to the front base by using a M3 flat head screw (45 mm). Next, mount the shock to the front base with a M3 flat head screw (20 mm), two M3 washers and a M3 lock nut.

Ensure that the upper wishbone does not collide with the shock when being moved. If that's the case you have mounted the wrong upper wishbone to this side and have to replace with the other one.

Repeat the process in the same way for the other side.

Apply some grease to the spherical bearings.

---

## Step 9: The Steer Lever and Coupler

Print the right and left steer lever, remove the support material and press the 963 bearings with the bearing spacers into their holes by using the same technique as before.

After printing the steer lever coupler, press the 963 bearings into the holes. The 963 bearings needs a very tight fit on this part. Printing it with a slightly higher flower rate results in a smaller inner diameter of the hole, which ensures a tight fit.

---

## Step 10: The Assembly of the Front End 2 (Steering)

We continue assembling the front end. Insert a M3 flat head screw ( 20 mm) into the steer rod and the steer lever (oriented as in the pictures), put a M3 washer on top of the steer lever, put the steer coupler on top of that (with the bearing facing the washer) and secure everything with a M3 lock nut mounted upside down.

Repeat the process for the other steer rod and steer lever. Check for the right orientation of everything.

Mount your hubs with the included bearings and axles to the wishbones by using M3 flat head screws (14 mm). You might have to add a small chamfer to the hubs mounting point in order to avoid collisions with the wishbones. Between the left and right hub exists a small difference, as they are only symmetrical to each other, not identical. Ensure that the hub's mounting arm for the steer rod is in the orientation closer to the ground.

Next, mount the steer rods to the hubs in the hole shown in the pictures. Do that by using a M3 flat head screw (20 mm), a M3 washer and a M3 lock nut.

Insert a M2 brass insert into the right steer arm. Here is a tutorial for inserting threaded brass inserts.

---

## Step 11: Printing and Attaching the Front Bottom Plate and Top Rod Connection

Start by printing the front base and the front top rod connection. The parts need no support. Print the front top rod connection parts very strong. I printed my parts 100 % solid. In this step, only the bottom part of the front top rod connection mounted to the front end. The top part of the front top rod connection is needed in a later step.

Insert two M3 brass inserts into the front bottom plate.

Mount the front end to the front bottom plate by using six M3 flat head screws (60 mm) and 4 M3 washers. The M3 washer sit below and above the steer levers. Attach the front top rod connection bottom part to the same six M3 flat head screws.

---

## Step 12: The Rear Lower Wishbones

This part transmits a lot of power from the hub to the rear base. The part will break when using PLA. TPU holds up perfectly. No TPU part broke during testing. This time, I tried tough PLA by Material4Print, which has a greater impact resistance than "normal" PLA because of additives. The tough PLA gives some more rigidity than the TPU I used before. The tough PLA has worked well in the first tests, but I haven't tested it as long as the TPU version. Besides using an impact resistant material, printing this part with 6 or more walls is recommended.

After printing, remove the support structures of the lower wishbone after printing it.

Press a 963 bearing in each of the four holes.

Mount the shock to the lower wishbone by using a M3 socket head screw (18 mm) and a M3 square nut.

Attach your rear hub to the lower wishbone with two M3 flat head screws (12 mm) and the printed spacers. - While taking the pictures for this Instructable, I did something wrong. I mounted the left hub to the right lower wishbone. You can spot the "error" in the area of the yellow circle in two pictures. The hubs mounting arm should be "closer" to the shock. I only noticed this later and exchanged the two hubs. The last picture in this step shows the right orientation for the hub when fully assembled.

Mirror the part in your slicer and repeat the process for the other side.

---

## Step 13: The Rear Upper Wishbones

After printing the rear upper wishbone, press two 963 bearings with their bearing spacer into their holes by using the same technique as before. Insert and M3 lock nut into its position.

Repeat the process again, as the right and left versions of this part are identical.

---

## Step 14: The Rear Base

Print the rear base with tree supports and remove them with pliers.

Press two 963 bearings with their spacers in each the left and right side.

Insert the eight M3 brass inserts into their holes by using a soldering iron.

Loosely place the differential into the rear base. Ensure that it is greased and moving freely.

---

## Step 15: The Assembly of the Rear End

Attach the two spacers with two M3 flat head screws (14 mm) to the rear lower wishbone (pictures 1 and 2).

Slide the dogbone into through the rear lower wishbone into the hub (pictures 3 and 4).

Mount the M3 flat head screws to the rear base an ensure that the dogbone is in the differential and the hub (pictures 5 and 6).

By using a M3 flat head screw, two M3 washers and a M3 lock nut, attach the shock to the rear base (pictures 7 and 8).

Mount the rear upper wishbone to the rear base by using a M3 flat head screw (30 mm) (pictures 9 and 10).

Attach the rear upper wishbone to the hubs upper mounting point (which has a M3 thread) by using a M3 flat head screw (20 mm) and the spacer (pictures 11 and 12). Add a M3 washer and a M3 lock nut, which acts as a counter nut to the hub's mounting point's thread (picture 13).

Repeat the process for the other side (pictures 14 and 15).

---

## Step 16: Attaching the Rear End to the Rear Bottom Plate

Print the rear bottom plate. Mount the rear end to the rear bottom plate by using M3 flat head screws (four 20 mm, four 8 mm). Use the 8 mm screws first as shown in picture 4, then use the 20 mm screws as shown in picture 5.

Print the differential shaft support bracket and press in a MR 105 bearing and insert four M3 brass inserts with a soldering iron. Slide it onto the differential shaft and mount it to the rear bottom plate with two M3 flat head screws (8 mm) as shown in picture 12.

---

## Step 17: Connecting the Rear and Front Bottom Plate

Connect the rear and front bottom plate by using two M3 socket head screws (20 mm) and two M3 washers.

---

## Step 18: Attaching the Steering Servo

Print the two servo mounting brackets and insert two M3 brass inserts into each one (picture 3).

Mount the servo mounting brackets to the servo (pictures 4 and 5).

Attach the servo and its servo mounting brackets to the front bottom plate by using four M3 flat head screws (8 mm)(picture 6).

Connect the servo arm to the right steer lever by using a M3 rod with a spherical joint on each end (pictures 7 and 8). The distance between the center points of the spherical joints is 9.5 cm for a optimal steering behavior. If the distance is off, the right and left steering ratios are slightly different.

---

## Step 19: Attaching the Top Rod

After printing the read top rod connection (picture 2), attach the metal square profile (8x8 mm, 40.4 cm) to the rear end by using the rear top rod connection, four M3 flat head bolts ( mm) and four M3 washers (pictures 1 and 3).

Attach the metal square profile to the front end by using the front top connection, six M3 lock nuts and six M3 washers.

To ensure a good alignment...

- do this mounting process while the bottom plate is standing on a very flat surface. This way, you will notice, when the front or rear end aren't sitting on one plane.
- Screw in every bolt and nut only a small distance at a time. This way you correct a misalignment in small increments.

When you have finished attaching the top rod, you'll notice how the whole structure, which was very flexible before, gained an extreme amount of stiffness. The exact reason for that is explained at the end of this Instructable.

---

## Step 20: Attaching the Motor

Start by mounting the differential gear on the differential's shaft (pictures 1 and 2). I used a 48 dp 43 t gear. Definitely use some screw locking adhesive here.

Print the motor mounting bracket (picture 3) with a heat resistant material like PETG or in my case tough PLA and insert four M3 brass inserts (picture 4). Attach the motor to the motor mounting bracket with two M3 flat head screws (6 mm) (pictures 5 and 6).

Mount the motor with its mounting bracket to the rear bottom plate by using four M3 ultra thin head screws (8 mm) (pictures 7, 8 and 10).

Attach the motor gear to the motor so that it meshes nicely with the differential gear and set the right distance between them (pictures 9 and 10). Here is a tutorial for setting the distance right. Grease the gears.

---

## Step 21: Electronics

In this step, wire up all your electric components and hold them in place by using zip ties in the according slots and thick double sided adhesive strips. Always refer to your manufacturers manual when wiring up electric components. Here is a tutorial for basic RC electronics and a tutorial for soldering RC connectors.

If you need to solder components, always work in a well ventilated area and minimize exposure to the fumes.

---

## Step 22: Attaching the Wheels

Print the rim by using tree supports and remove them with pliers (pictures 1-4). Put the tire onto the rim (picture 5). Insert the HEX12 nut, which is part of the hub assembly, with a tight fit by pressing it into its according hole with a M4 screw, washer and nut (pictures 6 and 7).

Repeat this process four times.

Attach two assembled wheels (picture 8) with each a M4 lock nut and M4 washer and without the pin in the hub's axle, which is intended for power transmission, to the front end's hubs (picture 9) by using a 7 mm socket wrench and a 2.5 mm allen key (picture 10). We don't need power transmission in the front and are able to fine tune the bearing preload this way.

Attach the other two assembled wheels to the rear end's hubs the same way, but with the pin in the hub's axle for power transmission installed (pictures 11 and 12). My pin broke after a few months of testing, so i replaced it with a M2 threaded rod, which fits perfectly.

---

## Step 23: Attaching the Front Bumper

The last part to attach is the front bumper.

I recommend using an impact resistant material, but PLA also showed some really good results in saving the car in a crash, if printed with a high wall thickness.

Insert four M3 brass inserts and attach the front bumper to the top rod.

You are ready to go!!

---

## Step 24: Geometry and Suspension Design

When designing this RC car, I decided to aim for a scale of approximately 1:10. This size offered a balance between sufficient space for components and a manageable overall build. I started with the purchase of a rear differential, dogbone-style drive shafts, and wheel hubs, which established the rear track width (22.3 cm). For the front track width, I opted for a slightly wider dimension (23.5 cm) to improve stability and traction during cornering.

The ratio of track width to wheelbase was another key consideration. Based on comparisons with real-world designs and other RC cars, I chose a 1:1.6 ratio, which resulted in a wheelbase of 36.6 cm. This configuration was chosen to promote stable and predictable handling, particularly during high-speed cornering.

The suspension travel was set to approximately 15-20 mm, which includes both compression and rebound. This allows the wheels to compress around 20-25% of their diameter. Given the relatively rough texture of asphalt for small-scale vehicles, this suspension travel is needed.

To maximize grip, I designed the suspension geometry to maintain a near-linear increase in camber as the suspension compresses. This ensures a consistent contact patch during dynamic conditions, such as cornering or bumps. The roll center was positioned low and remains stable across scenarios, contributing to the car's predictable handling. Additionally, I implemented a caster angle of 10 degrees, which adds dynamic camber during cornering when it's most needed.

Bump steer, an issue where suspension travel unintentionally alters the steering angle, was minimized through careful adjustments. The steering system approximates Ackermann geometry but includes modifications to account for lateral weight transfer. The outer wheel, benefiting from increased grip during cornering, is set to turn more sharply than the inner wheel, optimizing cornering performance.

Anti-dive geometry was not included, as the lack of braking components made it unnecessary and would have added complexity without significant benefits.

As I already pointed out, I'm nowhere near of being a suspension geometry expert, so keep that in mind. For those interested in learning more about suspension geometries, I highly recommend this introductory video by XF Motorsports.

*Attachments: Front Suspension.pdf, Rear Suspension.pdf*

---

## Step 25: Strength and Stiffness

Picture 1: When the car is moving on its wheels, it compensate its own gravitational force and additional loads induced by driving dynamics. When assuming all those forces, Fload, attack in the center of gravity, two opposing torques, M1 and M2 are created at the front and rear end of the car. Through does opposing torque, the top rod is experiencing compression forces while the bottom plate is experiencing tensile forces. The metal top rod is very resistant against buckling while the bottom plate made out of PLA has a high tensile modulus and strength. In consequence, the system is very rigid.

Picture 2: If the car drives over a bump on only the left or the right side, opposing torques are induced at the front and rear end. The square profile top rod contributes most to the resistance against such torsional forces. Although a square profile has less resistance against torsional forces than a cylindrical profile, it is much easier to clamp with the top rod connection at the front and back of the car. Having a cylindrical top rod resulted in much more torsional deflection because the round bar was able to rotate slightly in the top rod connection. Having a square profile, the car can only experience as much torsional deflection as the top rod, which is almost negligible with a 8x8 mm titanium square profile (or aluminum or steel).

Furthermore in case of a frontal crash, the impact gets distributed from the front bumper through the top rod to the whole car, which reduces impact spikes in a single part.

---

## Step 26: More Test Videos

https://youtu.be/c6_NunxIvkY?si=WqnR-BRy5YHN8YEP
https://youtu.be/yxx4tnBufh8?si=RkOAHaVWVVsFRw-e  
https://youtu.be/c6_NunxIvkY?si=fuwjfYf_-NPKvzkU

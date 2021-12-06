---
layout: page

---

---
layout: post
title: Boothroyd Dewhurst Inc.


thumbnail-img: /assets/img/DFMA_Logo.jpg


---

During the summer of 2019 I worked at Boothroyd Dewhurst Inc. (BDI) in Wakefield, RI. Here, I supported the Research and Development manager, Brian Rapoza. I collaborated with Brian to write Excel based macros to develop a cost model for the metal extrusion manufacturing process that BDI was implementing into their software (DFMA). We were looking to implement a way to check if the DFMA software was “correct” when performing cost modeling using metal extrusion. The Excel Macros I developed is the tool they used . Here is where my interest peaked in the combination of programming and mechanical engineering. This then sparked my excitement into computer science, and resulted in a minor at Quinnipiac University. <br>
[View Some of My Code](/assets/img/Code_Picure.PNG) <br> [Check Out the Final Report](/assets/img/Final_Report.PNG)


**Medtronic Robot Design project**

  My senior design project is to create a robot that can tie simple knots in medical suture. This project is being sponsored by Medtronic and will be used by their test engineering team. Medtronic manufactures and tests suture. One of the tests they need to do is a tensile test to obtain data on some different material properties. To perform a tensile test on the suture there needs to be a simple overhand knot tied in the suture. Right now, they have employees tying knots in the suture which takes up a lot of time and money so the Medtronic test team has tasked my team and myself with creating a robot that can tie the knots for them.

_More info and updates soon to come as the project progresses_ 
Check out <a href="https://www.medtronic.com/us-en/index.html/" target="_blank">Medtronic</a> to find out more about the company.


**Solenoid Engine Design Project**

Design, build, instrument and operate a ‘3-cylinder’ solenoid engine. A solenoid engine is a very simple device: a flywheel is kinematically connected to a solenoid via a series of linkages, and kept in motion by energizing the solenoid at a very precise instance within the rotation of the flywheel. 
  
My team decided to go ahead with a radial engine design with the three solenoids positioned at 120 degrees to one another all connected to the same crank on the crank shaft. We designed and modeled the engine in SolidWorks and then spend time ordering parts, 3D printing parts, and manufacturing parts in the machine shop. 

Once the hardware was designed we had to do the electrical design with the simple user interface of an on off switch as well as a simple power jack to plug the 12V power supply into. We used three MOSFET transistors to direct the current to the desired solenoids at the right time as well as an LCD screen and a photogate to know when to fire which solenoid. The "brains" behind the engine was Arduino which was the third part of this project. The code was designed and tested to run the engine and print the rpm of the flywheel on the LCD screen. Our engine's max speed is 790 rpm. Click [here](/assets/Engine_Video.mov) to see a video of the running engine!

**Solar Tracker Project**

Design, build, instrument and operate a 2-DOF solar tracker that measures and logs power output data
from a solar panel. A solar tracker is a device which ensures that a solar panel maintains direct orientation to the sun. This can be accomplished with 2 degree-of-freedom motion and a light-sensing scheme.

Myself and my partner designed our solar tracker in SolidWorks knowing that we needed to laser cut all of the pieces of the design out of 1/8th inch acrylic. This was a challenge because every piece has to be flat out of the same piece of stock acrylic. We used three photocells in voltage dividers so that Arduino can read the differences in voltage with the differences in resistances that the photocells produce the the differences in light.

The three photocells are in a fixture that holds them in place but separates them by a wall so that if the light is more intense on one side then only one of the photocells will see that light. For example if the light is more intense on the right side, that photocell will see more light, decreasing the resistance and therefore increasing the voltage in the voltage divider. In the Arduino code there are conditional statements that say if the voltage coming from this photocell is larger then move the servos in that direction until the voltage is the same from all photocells. The voltage of the the photocells will be the same when they are all three pointing directly at the light source which is the goal of this solar tracker.

We used a shield on the Arduino that allows you to write data to a SD card. We tracked the solar panel data from a 6V, 1W solar panel over the course of the day.

See our [tech sheet](/assets/img/Solar_Tracker.pdf).


**CATSMEOW Design Project**

My team was tasked with re-designing a CATSMEOW. The CATSMEOW is a blender assembly that is mounted onto the top of a mason jar
and has a main function of whipping cream. The original design had many issues including adhesive wear, torque, gearing, and just overall design.

My team and I came up with a new design for the CATSMEOW that was able to whip cream in 90 seconds when tested at the end of the year. 
[View the Final Assmebly here](/assets/img/CATSMEOW.pdf)


**Circuits Design Project**

Worked in a team to design, simulate, prototype, and fabricate a DC, multi-output power circuit. The PCB needed to power a project that we completed
earlier in the semester that required 9V, an Xbox controller that required 3V, and also an LED. We used software's such as MultiSim to simulate the circuit
before we sent it out to be printed, also Pad2Pad to draw the desired PCB and have it manufactured. We used tools such as the Elvis II breadboard to 
conduct initial research into the circuit and different parts needed. Once the PCB's arrived we soldered them by hand and tested the boards to check for
functionality. Ours Worked! Check it out [here](/assets/img/CircuitProj.jpg). And the [PCB](/assets/PCB.jpg).


**Thermodynamics Combined Power Cycle Project**

In this project my team and I used MiniRefProp and MATLAB to design a [Combined Power Cycle](/assets/img/Thermo_Proj.PNG). We analyzed the Brayton cycle combined with
the Rankine cycle in MATLAB to find the optimal temperatures and pressures needed at the different states of the cycle to maximize the power
output. We were also tasked with choosing a gas turbine out of a list with all different operating specs. Take a look at some of the [code](/assets/img/Thermo_Code.PNG)






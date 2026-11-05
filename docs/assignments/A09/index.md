# A9 – Pulleys

## Objective
This week, I am designing a pulley system and frame through consideration of friction, static analysis, and dynamic analysis. 

## Selecting the Belt

Before beginning flexible belt analysis, I began by drawing a free body diagram of the forces acting on a single wheel and the pully system in cross sectional area . Additionally, variables for measurements which will be used throughout analysis are defined. I decided to define these variables here, including, but not limited to, the center distance, the material, the safety factor, etc. Belt values are recorded alongside wheel values.

Starting the static analysis of the belt I drew of a singular cross sect a single pulley wheel. Known and unknown values which are represented in the free body diagram are documented. 

Within these values, it should be noted that I chose to assume the material was the same for the wheel as it was for the shaft to lessen the amount of values taken through research. 1060 steel is a high carbon steel, so the friction coefficient used in calculation is for the interaction between rubber and tool steels. To find the individual forces acting on the wheel, minimum cross sectional area, and circumference of the belt, stress and force and friction relations are used to solve.

**Calculations:**


I chose to keep the dimensions of the belt as close as possible to the found values. The true chosen specifications are a overall circumference of 18 1/4" and diameter at 3/32".

**Belt Chosen:**
  
<img src="Screenshot 2026-11-05 070417.png" width="50%" alt="Description of picture">
  
_Resource: https://www.mcmaster.com/3044K602-3044K699/_




## Designing the Shaft

The same initial procedure is repeated to begin setting up the analysis for the shaft. A free body diagram is drawn both for the singular shaft, and the cross sectional area of the wheel and shaft. Values are documented before calculation as well. 

Torsion is defined using force and the geometry of the wheel. This is used alongside the polar moment of inertia to determine the maximum shear stress in the beam. The formula for allowable stress which uses the Von Mises and safety factor because allowable and maximum shear stress are the same in this case.

Geometry limits are then found using these relations.



## Designing the Bearing

To begin the analysis to design the bearing I started by creating a color-coded free body diagram. The length of the bearing is defined here as well. 

The force on the bearing is used to find the pressure on the area where pressure is applied. Then the chosen velocity of the system from the beginning stages of design is converted from radians to feet per minute. 

These values are used to find the PV rating, which I used to choose an appropriate material through the PV limit chart in the Machinery's Handbook. I chose to define this part in Graphite.

## Engineering Analysis for Frame

To begin the design for the frame I began with a simple sketch which assigns a variable to the measurement most important to the function of the design, or the shaft hole. The true diameter noted is based upon the found minimum shaft diameter. I set this measurement to be 0.5". The center length chosen is also notated in this sketch. 
  
This model was then transitioned to CAD, closing out the project. 

**Visuals:**  
  
<img src="Screenshot 2026-11-05 044654.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044712.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044745.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044804.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044824.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044839.png" width="50%" alt="Description of picture">
<img src="Screenshot 2026-11-05 044858.png" width="50%" alt="Description of picture">

  
**Download my Part:** https://drive.google.com/drive/folders/1GgCj_r1WnCjaYqdxjTpEtIHGd-omNRCY?usp=sharing
   
## Lessons Learned
  
For me, the largest lesson learned from this assignment was to do with the Dynamic analysis portion. This was my first exposure, and I have gained an understanding of the benefit analyzing a system at different stages. Additionally, I was able to truly recognize the connection between chain dimensioning and interconnected analysis such as what was used here. To truly consider a system of parts, analysis must consider their connection as well. Lastly, I was not aware of tight and loose side of the wheel which allows the pulley system to function.


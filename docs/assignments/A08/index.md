# A8 – Gears

## Objective
- Design a gearbox that can be assembled and disassembled.
- Analyze and size input and output shafts for strength.
- Design journal bearings to support shafts.
- Create a gearbox housing with proper clearance and fastening.
- Use parametric CAD modeling to generate a final design.
- Document calculations, sketches, and lessons learned.
  
## Analyze
  
To begin the design of the shafts I started by finding the ideal values for the Pinions Torque and speed. As the pinion acts as the input for this system, the power acting on it acts on the gear as well. I used the found speed to determine the value of the power acting throughout.
  
  
### Design of the Shafts
  
**Power Transmission**
Once ideals were found, they are used to determine the shear stress that develops in the input shaft. To set up the equation for the value, the section modulus is found as well. This value is then compared to the allowable torsional shearing stress for small, short shafts found within the Machinery's Handbook. (pg. 289)
  
Because the stress found is far below the allowable stress, the shaft diameter is sufficient.
  
**Short Shaft**
The same procedure is followed to find the shear stress within the output shaft, instead using given values for the Gear. 
  
The stress for this shaft was below the allowable stress as well, so the diameter is kept as is.
  
### Design Journal Bearings
  
**Choosing Size and Length of Journal Bearings**
  
In order to design the bearings, the pressure, speed and PV limit must be determined. This is found using the tangential and rotational force acting on the gears. These values reveal material limitations, which are needed to find diameter and length.
  
I began with analysis of the input Bearing, which is connected to the input shaft. Meaning, the speed at the input of the pinion is equivalent to the velocity of the bearing. Needed values are calculated using the following formula set up.
  
Using the Machinery Handbooks Application Limits of Plain bearing Materials, I chose Nylon as the material for this bearing. (pg. 2442)
  
  
The process stated for the input bearing is used to determine the necessary values for the output bearing. Nylon was chosen for this bearing as well to keep consistently throughout the design.
  
For this design I chose an RC4 or Close Running fit for the shafts because accurate location and moderate journal bearing pressures are required. I chose to use a +.0009 in clearance from the Handbooks chart. (pg. 654)
  
These steps are repeated for the Journal Bearing fit the output shaft.
  
### Design Thickness of the Journal Bearing


### Choosing McMaster Parts

### Sketch of Gearbox Housing

## CAD Model - Gearbox


## Drawings

## Lessons Learned


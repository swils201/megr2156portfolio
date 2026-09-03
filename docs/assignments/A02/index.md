<img width="1533" height="782" alt="image" src="https://github.com/user-attachments/assets/21918f5d-4856-4810-ae31-476c2883f582" /># A2 – Truss Stress Analysis

## Objective  
- Design a lightweight planar truss using A500 steel or an alternative material.  
- Create free body diagrams (FBDs) for joints and critical pins.  
- Calculate the required cross-sectional area of truss elements with a safety factor.  
- Determine pin sizes based on shear forces with a safety factor.  
- Solve equations symbolically and numerically for both truss and pin design.  
- Estimate the total weight of the truss and pins.  
- Create a CAD model with accurate dimensions and connections.  
- Compare CAD weight predictions with hand calculations.  
- Document key engineering lessons learned from the process.  
  
  
## Analyze  
<insert design constraints>
  
To design within the design constraints of this assignment, first I considered how the geometry of the structure could be simplified. For my design, I prioritized the use of right triangles to allow the Pythagorean theorem to be valid for analysis. To determine the structure would hold it's stability I used the stability joint equation provided in the SoDesign Course Materials. (2*[number of joints] = 3 + [number of members]) For these specific design constraints, a stable truss requires 8 members, providing the limits needed to finalize my design. To fully comprehend the requirements of this design, the minimum surface area and weights of all elements, including beams and pins must be found.  



<img src="Final Truss Design.png" width="50%">
<img src="Trussunknown.png" width="50%">


To find these values, I first determined the unknowns and knowns. It's within this process that I chose the highest minimum applied force (P = 30 KN). Because of this I chose the highest minimum magnitude for yield strength of A500 Steel throughout analysis. First, the truss was treated as a whole using the Moment equilibrium equations to determine the magnitude of the support at B. For the rest of the statics analysis, the method of joints was used to both algebraically, notated in black, and then numerically solve the internal forces found throughout the truss, notated in blue. These color notations continue throughout the documentation for clarity.   



<img src="JB.png" width="50%">
<img src="JC.png" width="50%">
<img src="JE.png" width="50%">
<img src="JD.png" width="50%">
<img src="JF.png" width="50%">
<img src="JA.png" width="50%">

  
Once the maximum internal force was determined, found to be Force DE, the safety factor and yield strength of the A500 steel can be used to find the minimum surface area of each beam. After identifying given and needed information, I sketched a generalized Stress-Strain graph to visualize the specific goals of this objective. Then using the relationships between stress, yield, and area, the minimum area was found algebraically and numerically. ***Missing explanation abt beam weights   
   
   
  
<img src="MaxFInt.png" width="50%">
<img src="ElementFactors.png" width="50%">
<img src="Elements.png" width="50%">



***Missing explanation abt beam weights   



To finish the analysis process, the minimum surface area of each pin must be found. In this design, each beam is a rectangular prism while the pins themselves are represented by cylinders representing single shear connections. It is assumed in this analysis that there is no compression failure through buckling. 

  

<img src="PinD.png" width="50%">
<img src="PinKnowns.png" width="50%">



I specifically analyzed off of Pin D to ensure the largest internal force passed through. The provided density and shear strength of the pins is converted to the metric system through analysis to remain consistent in both calculations and modeling. Then the relationships between shear stress, yield shear strength, and the density of the pins was used to determine the minimum surface area.  


<img src="PinSurface.png" width="50%">
<img src="PinWeight.png" width="50%">



**Analysis Resources:*
<insert ss and links>  
- https://beamdimensions.com/materials/Steel/ASTM/ASTM_A500/#Grade_C
- https://www.cuemath.com/numbers/factors-of-338/ 

## Decide  

The geometry of this design was chosen to ensure stability while limiting each area to be equivalent with one another. To meet those constraints, all triangles were made to be at 90 degree angles allowing the Pythagorean theorem and trigonometric identities to be used. These trigonometric identities were key to solving the various internal forces seamless without overspending time calculating specific potential angles between beams. The specific arrangement of these triangles has come about by chance and does not limit this particular design, so it was not considered.   

  
  
## Communicate


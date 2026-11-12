# A10 – Lead Screw Translating System

## Objective

## Design the Crosshead - Saniyah Wilson
### Research - Saniyah Wilson
  
Before beginning analysis, I researched existing bench-top footprint tensile testing machines and the given load cell to determine the length of the crosshead. The main issue of the area or size of the head is ensuring all parts have room to fit and function on the part. To do this, I found the sum of the two nut flange diameters and the width of the cell to find the length if each part was tangent each other. Then, using a sketch, I chose gap distances between the part. This total was my chosen length.
  
Since the nut flange was found to be 1.6 inches, I used that diameter as the minimum base measurement for the crosshead. Since it is a minimum, and FEA is to be conducted later, I chose to dimension the design for part at 2 inches instead.
  
Lastly, I chose 1090 Steel as it is a tool steel with high strength and should result in a durable part.

**Resources:**  
- https://www.azom.com/article.aspx?ArticleID=6560  
- https://www.azom.com/equipment-details.aspx?EquipID=5618  
- https://repositum.tuwien.at/bitstream/20.500.12708/200949/1/Demmel%20Stella%20-%202024%20-%20Design%20manufacturing%20and%20testing%20of%20an%20open-source...pdf  
- https://assets.dwyeromega.com/spec/DS-LC103B.pdf  

### Beam Stress/Strength Analysis - Saniyah Wilson
  
The only dimension left unknown is the minimum height, or thickness, of the crosshead. To determine this I conducted a Beam Stress and Strength Analysis assuming the lead screws act as supports. In these calculations, the relationship between stress, yield strength, and section modulus are used to determine the unknown measurement.
   
Once the final formula has been found symbolically, numbers are input and the value is solved numerically.
  
**Visuals:**  
  
<img src="L10STRENGTH.jpg" alt="Description of image" width="50%">
<img src="L10STRENGTH2.jpg" alt="Description of image" width="50%">
<img src="L10STRENGTH3.jpg" alt="Description of image" width="50%">
  
### Beam Deflection Analysis - Saniyah Wilson
  
Next, beam deflection analysis is conducted to compare the results to the first found value. It can be noted that the Yung's Modulus of 1090 Steel is added to the list of known values in GPa. I chose to do the calculations for this analysis using metric dimensions because the given maximum deflection to be used, 0.01mm, is a much smaller magnitude once converted. Chosen measurements are converted as well for the same reasons.
  
Here, the relationship between that maximum deflection, the Yung's Modulus, and the moment of inertia are used to find the unknown measurement. Once found numerically, it is clear that the first found measurement is the true minimum. 

**Visuals:**  

<img src="L10DEFLECTION.jpg" alt="Description of image" width="50%">
<img src="L10DEFLECTION3.jpg" alt="Description of image" width="50%">
<img src="L10DEFLECTION4.jpg" alt="Description of image" width="50%">
  
### Final Height Chosen - Saniyah Wilson
    
These dimensions are fairly low due to the choice to use a very strong steel, so I chose the height at one inch. This choice makes the part more realistic to manufacture.  
    
<img src="FINAL HEIGHT.jpg" alt="Description of image" width="50%">  
  
### Initial Paper Drawing  - Saniyah Wilson

### Tabulating Costs - Saniyah Wilson
  
Total costs of each part our team did not design, but were used in the final assembly,
were tabulated here.
  
<img src="L10COSTS.png" alt="Description of image" width="50%">   
  
**See the Parts Yourself:** https://docs.google.com/document/d/1bKbhDkLOe-WH6ZnaHG-k7sk0W9YO7X9axeHdGJF9zss/edit?usp=sharing 

## Parametric CAD Model of Crosshead
### Initial Design

Following the initial sketch the dimensions chosen were input into the global equations system in SolidWorks. I chose to leave dimensions which were related to outside parts or which would not be used in the end geometry to be added to the equations throughout the modeling process. This way, variable names are not overly reused, eliminating some confusion.


<img src="A10PARA.png" alt="Description of image" width="50%"> 
The model begins with a rectangle at the base and length determined and is extruded to an inch. 

<img src="A10CAD1.png" alt="Description of image" width="50%"> 
  
On one side, the hole for the lead screw is designed and mirrored to the other half of the part. Then, a cut extrude is used to remove the material.   
  
<img src="A10CAD2.png" alt="Description of image" width="50%"> 
<img src="A10CAD3.png" alt="Description of image" width="50%"> 
<img src="L10CAD4.png" alt="Description of image" width="50%"> 
    
To create the bore holes for to mount the crosshead to the flange, I used the measurements referenced and created a concentric circle around lead hole. This circle is used to align the holes and then is cut before they are mirrored to the other side.  
  
<img src="L10CAD5.png" alt="Description of image" width="50%"> 
<img src="L10CAD6.png" alt="Description of image" width="50%">  
  
Lastly, a cut extrude creates eight holes at half the thickness of the crosshead. This completes the initial model, which I then passed on to Jack for FEA analysis.  
  
<img src="L10CAD7.png" alt="Description of image" width="50%">
<img src="L10CAD8.png" alt="Description of image" width="50%"> 

**Final Model and Parametric Values Added**
  
<img src="L10FINALCAD.png" alt="Description of image" width="50%"> 
<img src="L10FINALPARA.png" alt="Description of image" width="50%"> 
    
**Download the File:** https://drive.google.com/file/d/1dN-fcCupNEkCIPUpsWeFSNqFMlzsTfWq/view?usp=sharing  
  
## Analyze


## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate


# A3 – Parametric and FEA

## Objective   
  
- Use axial deflection modeling to design its dimensions  
- Use parametric design to determine a bars length  
- Introduce you to FEA (Finite Element Analysis)  
- Introduce you to linking dimensions to appropriate parameters in CAD.  
- Compare and contrast the different analysis  
  
## Parametric Design  

To model a hollow cantilever beam, first, I chose an Aluminum material from the Solidworks Materials Database with a Young's Modulus between the parameter of (8.5 - 11.5) x 10<sup>6</sup> psi.     
  
<img src="MaterialChoice.png" width="50%">  
   
*Shown Above: 1060-H18 Aluminum Rod (SS) with Young's Modulus 10007603.9 psi.*   

   
To determine the length of the structure, I chose and assigned the necessary values for the direct tension elongation equation and given values to variables within the Equation Document Properties of my sketch. Initially, the applied force (F) was chosen to be 400 lbf, height (H) to be 5.0 in, and width (W) to be 5.0 in.  
    
<img src="VALUE1.png" width="50%">    

      
After choosing the thickness (T) to be 1 in, the global variables were used to assign variables for area and length. My initial input of equations did not properly considered thickness, and were adjusted before advancing to CAD modeling. To close out this step, I added the tension elongation equation using the variables created to find the appropriate value for length (L).
  
<img src="VALUE_ERROR_CORRECTED.png" width="50%">     
  
*Incorrect Area Equation*  
    
<img src="FINALVALUES_CORRECTED.png" width="50%">  

*Shown Above: Corrected Area Equation*  

  
First, I created the base square forming the cross sectional area using global variables W and H and T. Once defined, I extruded this sketch using the found L value, and realized I had not appropriately consider the magnitudes for the values within the length equation, as the length would be impractical.  
  
<img src="VALUE_ASSIGN.png" width="50%">  
<img src="BEAMSKCH.png" width="20%">  
<img src="BEAMEXTRUDE_INIT.png" width="50%">  

*Shown Above: Length, once visualized, was much longer than expected.*


  
To correct this error, I considered the relationships between the variables in the tension elongation equation. I determined to decrease the length I would need to decrease the height, width, and thickness, while increasing the force. I adjusted these variables within the equation table, resulting in the final beam extrude.

<img src="VALUES_ADJUST_CORRECTED.png" width="50%">
<img src="VALUE_ASSIGN2.png" width="50%">  
<img src="BEAMEXTRUDE_FINAL.png" width="50%">  
  

  
  
**To download model click this link: https://drive.google.com/drive/folders/1jlTfqYKWywQRgLVsVZnjPhhra4-ccnbi?usp=sharing**  



  
## FEA
  
To start the Finite Element Analysis, I began by opening a new study under the name Tensile Loading in SolidWorks. I set one exposed cross section as a fixture and applied the 490 lb Force, as used in the equation, to the other.  
  
<img src="STUDY.png" width="50%">
<img src="FIXTURE.png" width="50%">  
<img src="FORCE.png" width="50%"> 
  
Lastly, I placed the mesh over the beam and accepted the programs default settings before running the study. The study returned a mapping of stress, displacement, and strain. To determine if this model aligns with assignment constraints, the maximum stress visible, 8.172e+2 psi or 0.8172 ksi, can be compared to the strength of Aluminum. In this case, the values support a successful model as the maximum stress is far below 40 ksi.   
     
<img src="MESH.png" width="50%"> 
<img src="STRESS.png" width="50%">
<img src="DISPLACEMENT.png" width="50%">
    
From this study, the minimum Factor of Safety = 19.  
    
<img src="FOS.png" width="50%">  
  

   
## Design Reflection  
  
  
The axial deflection used in the parametric calculation was 0.009 and the found deflection is 0.008998 leaving an around 0.022% discrepancy between the values. The simplicity of both the beam and the force applied allow for these values to be incredibly close, while rounding differences cause slight error.  
  
## Lesson Learned
  
In total, I spent around 6.5 hours on this assignment. The primary lesson I learned through the process of this design, beyond the objective related skills, is to always write all formulas out before attempting to add them to CAD system properties. This would have saved time wasted correcting smaller issues throughout the assignment.  
  

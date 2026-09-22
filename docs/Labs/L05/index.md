# A5 – [Topic]

## Objective

To achieve a snap-fit design by considering the parts mechanical properties, geometry, tolerance, and load bearing requirements.
  

## Modeling
  
My snap fit design is modeled to work similarly to a backpack clip where the two clasp pieces are able to slide apart instead. Component One consists of two flexing prongs modeled after box beams with the snap lip on the outside of each. Component Two has matching lip indents which Component One is able to snap fit into. 
  
  
**Initial Design**  
<img src="L5INITDESIGN.jpg" alt="Part 1 Initial Sketch" width="30%" />  
  
Once the general shape had been decided, variables were designed and two measurements were chosen to base the design off of.  
  
<img src="L5INITDESIGN2.jpg" alt="Part 1 Initial Sketch" width="50%" />  
  
In the image above, the location of the needed and unknown length h, the minimum height length of Component One's lip, is identified and documented. The unknown minimum length of Component One is captured as well.  


Before collecting the formulas to find this height, I documented given values needed such as the maximum force applied and the Youngs Modulus and yield strength of PLA. To try to begin designing against part failure, I chose the maximum values for force allowed for this assignment.  
  
<img src="L5GIVEN1.jpg" alt="Part 1 Initial Sketch" width="30%" />
  
*PLA Specifications Used:*  
- https://cianoshapes.com/wp-content/uploads/2024/10/Scheda-tecnica-del-filamento-UltiMaker-PLA.pdf  

  
**Determining Minimum Height of Lip**
  
*Formulas and Algebraic Calculations*  
  
The formulas used to find this height consists of beam equations specifically for a cantilever beams. The axial load (F2) of 10 lb is used for this calculation, formulas for maximum stress are rearranged to find the needed value and the necessary conversion is noted. For future calculations, it is noted below that the chosen height found based on this value will act as the maximum deflection used to find the overall "beam" length.  
  
<img src="L5HFORMULAS.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
  
*Numerical Calculations*  

<img src="L5LIPHEIGHT.jpg" alt="Part 1 Initial Sketch" width="50%" />
With formulas pre-arranged, values are simply plugged in and the minimum height is noted.
  
From this, the height is chosen to be 0.025 in.
  
  
**FBD of Clip Member**
  
<img src="L5CLIPDESIGN.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5GIVEN2.png" alt="Part 1 Initial Sketch" width="50%" />
  
To begin determining the second designed dimension, I began with a free body of a single member of Component One. Given values were once again noted for convenience.
  
*Formulas and Algebraic Calculations*
  
<img src="L5LFORMULAS1.jpg" alt="Part 1 Initial Sketch" width="50%" />
Beginning the formulas, the moment acting on the members is caused by the transverse load (F = 5 lb) and the relationship between it, the width designed for strength, and maximum normal stress are  documented. 
  
This relationship is rearranged alongside the previously noted definition stress, to find the minimum length designed for strength.
  
<img src="L5LFORMULAS2.jpg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5LFORMULAS3.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
Before beginning numerical calculations, other given values are documented. 
  
<img src="L5GIVEN3.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
*Numerical Calculations*
<img src="L5LSOLVE.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
**Final Sketch**
  
*Minor Calculations*
To determine the angle necessary to fully define the lip, the chosen l2-length is used alongside the chosen lip height. 
  
<img src="L5LIPANGLE.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
*End Result*
Any undefined dimensions from this point are chosen, with the goal to have realistic proportion with existing design decisions. The final sketch is complete!
  
<img src="L5FINALSKCH.jpg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5LFINALSKCH2.jpg" alt="Part 1 Initial Sketch" width="50%" />

  
## Parametrically Design and CAD Modeling
<img src="L5PARAMETRIC.png" alt="Part 1 Initial Sketch" width="50%" />


<img src="L5CAD.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5EXTRUDE.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5CHAMFER.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FILLET.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FINAL.png" alt="Part 1 Initial Sketch" width="50%" />




<img src="L5CAD2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5EXTRUDE2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5CHAMFER2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FILLET2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FINAL2.png" alt="Part 1 Initial Sketch" width="50%" />


<img src="L5ASSEM1.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5ASSEM2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5ASSEM3.png" alt="Part 1 Initial Sketch" width="50%" />

## 3D Printing and Test

**Resources:**
- https://jlccnc.com/blog/tolerance-and-allowance
- https://thevirtualfoundry.com/3d-printing-shells-and-infill/
- https://sovol.eu/blogs/new/3d-printing-infill-patterns-strength-speed-efficiency-guide?srsltid=AU7gw4UrDHCCdBaWZ4behFvWKgcDuNFfOkFZz6fYl9MXetjO0tD7naG_
- https://all3dp.com/2/prusaslicer-support-settings-explained/
**Visuals**
<img src="L5PRINT1.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT2.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT3.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT4.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="IMG_6348.jpeg" alt="Part 1 Initial Sketch" width="50%" />


  
**Slicer Adjustments**
<img src="L5PRINTPOSITION.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PERIMETERS.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINTSETTINGS.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5infill.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5layerheight.png" alt="Part 1 Initial Sketch" width="50%" />

**Final Slice Info & Support View**
<img src="L5sliceinfo.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5supportview.png" alt="Part 1 Initial Sketch" width="50%" />

**View My Print and Files!**
https://drive.google.com/drive/folders/18uhuDUKvQ_IIpI_456J-x7gmxwxmJV_T?usp=sharing


# A5 – [Topic]

## Objective

To achieve a snap-fit design by considering the parts mechanical properties, geometry, tolerance, and load bearing requirements. This design is intended to be printed as an FDM Part using Generic PLA.
  

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
  
<img src="L5CLIPDESIGN.jpg" alt="Part 1 Initial Sketch" width="40%" />
<img src="L5GIVEN3.jpg" alt="Part 1 Initial Sketch" width="30%" />  
  
To begin determining the second designed dimension, I began with a free body of a single member of Component One. Given values were once again noted for convenience.  
  
*Formulas and Algebraic Calculations*  
  
Beginning the formulas, the moment acting on the members is caused by the transverse load (F = 5 lb) and the relationship between it, the width designed for strength, and maximum normal stress are  documented.  
  
<img src="L5LFORMULAS.jpg" alt="Part 1 Initial Sketch" width="50%" />  
   
This relationship is rearranged alongside the previously noted definition stress, to find the minimum length designed for strength.
  
<img src="L5LFORMULAS2.jpg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5LFORMULAS3.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
Before beginning numerical calculations, other given values are documented. 
  
<img src="L5GIVEN3.jpg" alt="Part 1 Initial Sketch" width="30%" />
  
*Numerical Calculations*  
  
<img src="L5LSOLVE.jpg" alt="Part 1 Initial Sketch" width="50%" />
  
**Final Sketch**
  
*Minor Calculations*  
  
To determine the angle necessary to fully define the lip, the chosen l2-length is used alongside the chosen lip height.  
  
<img src="L5LIPANGLE.jpg" alt="Part 1 Initial Sketch" width="40%" />  
  
*End Result*  

Any undefined dimensions from this point are chosen, with the goal to have realistic proportion with existing design decisions. The final dimensions for the fitting Component Two are documented as well, completing the final sketch!  
   
<img src="L5FINALSKCH.jpg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FINALSKCH2.jpg" alt="Part 1 Initial Sketch" width="50%" />  
  
   
## Parametrically Design and CAD Modeling  
  
I began translated this design into CAD modeling through using parametric design to model Component One. I chose to use most variables found within my algebraic calculations as the parameters for the equations within this model, because I've found this is a good way to catch numerical errors.   
  
<img src="L5PARAMETRIC.png" alt="Part 1 Initial Sketch" width="50%" />  
  
Although I unfortunately lost the documentation, originally a small error existed within my length calculations. Through parametric design, I was able to identify that the wrong force was used when the calculation was done manually. The correction was made to both portions of the design.  
  
Once parameters were set, I modeled the general geometry, fixed to the origin of the top plane. The general shape was then dimensioned and extruded with those parameters.  
  
<img src="L5CAD.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5EXTRUDE.png" alt="Part 1 Initial Sketch" width="50%" />  
  
When considering interference between Component One and Component Two and the tolerance allowance for the Prusa Core One, I decided to chamfer the free ends of Component One rather than change the general dimension. This was in hopes to keep the functioning part as close to the intended calculations and design as possible. I chose a 45 degree angle to overaccommodate for this 0.1 mm tolerance. An arbitrary fillet was added at the inside of the bending components to resist failure at that point.  
  
<img src="L5CHAMFER.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FILLET.png" alt="Part 1 Initial Sketch" width="50%" />  
  
*Tolerance Allowance Used:* https://jlccnc.com/blog/tolerance-and-allowance
    
Below is a view of the final CAD part.   
  
<img src="L5FINAL.png" alt="Part 1 Initial Sketch" width="50%" />  
    
Next, I began the second part, or the CAD model for Component Two. For this model I didn't find it necessary to use parametric design as nearly all dimensions for this part were not found through solved equations but rather designed around Component One. The base sketch was drawn and the part extruded, using manually input dimensions.  
  
<img src="L5CAD2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5EXTRUDE2.png" alt="Part 1 Initial Sketch" width="50%" />
  
To finish the part fillet's were added to the points of bending for this Component as well.  
  
<img src="L5FILLET2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5FINAL2.png" alt="Part 1 Initial Sketch" width="50%" />
  
As a test of whether the parts fit together, without clear interference, the Components were mated together within a final assembly, restricting motion to reflect how the part would function. This test indicated success, closing out the CAD modeling portion of this project.  
  
<img src="L5ASSEM1.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5ASSEM2.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5ASSEM3.png" alt="Part 1 Initial Sketch" width="50%" />
    
## Research on Build Orientation  
  
In preparation for printing these parts, I looked into information of ProtoLabs Network regarding the affects of part orientation on strength. Through this I found that FDM parts are documented to be strongest in the XY plane. Additionally, when under bending force it is important to orient parts to allow the outer walls to follow or be collinear with the length of the bend. In the case of my design, this indicates I must orient the part to print along the chosen L length and W2 Width of Components One and Two.  
  
**Resource:**  

- https://www.hubs.com/knowledge-base/how-does-part-orientation-affect-3d-print/  
  
## 3D Printing and Test  
**Slicer Adjustments**  
  
Following the research on print orientation done prior, I placed the two parts within the PrusaSlice Software.   
  
<img src="L5PRINTPOSITION.png" alt="Part 1 Initial Sketch" width="50%" />  
  
To maximize strength, I researched further to find the affects of infill density and patterns, outer walls, and supports would affect the strength and quality of my print. For infill density, I found that past 60% the part would become too brittle while below 30% may not have a high enough load capacity. In terms of the pattern, gyroid is known for its strength in all directions, making it a perfect fit for this design. Lastly, I found within the Print Orientation Research that an FDM part under bending force experiences most of its stress on the outer walls.   
  
These pieces of information led me altogether to increase the number of perimeters to 4, increase the density to 50%, and adjust the pattern. I left layer height and other print settings as recommended by the system because I have found success doing that in the past.  
  
<img src="L5PERIMETERS.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINTSETTINGS.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5infill.png" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5layerheight.png" alt="Part 1 Initial Sketch" width="50%" />  
  
Due to the orientation chosen for strength, supports are necessary for this print. I chose to use Snug supports for this because I found in research that they are useful for details, and the lip dimensions are quite small.   
  
*Final Slice Info & Support View*  
  
<img src="L5sliceinfo.png" alt="Part 1 Initial Sketch" width="50%" />  
  
The estimated print time can be noted here at 24 minutes.  
  
<img src="L5supportview.png" alt="Part 1 Initial Sketch" width="50%" />  
  
**Resources:**  
  
- https://thevirtualfoundry.com/3d-printing-shells-and-infill/
- https://sovol.eu/blogs/new/3d-printing-infill-patterns-strength-speed-efficiency-guide?srsltid=AU7gw4UrDHCCdBaWZ4behFvWKgcDuNFfOkFZz6fYl9MXetjO0tD7naG_
- https://qidi3d.com/blogs/news/3d-printing-infill-patterns-and-density-guide
- https://all3dp.com/2/prusaslicer-support-settings-explained/
     
  
**View My Print and Files!**   
  
In total my part took around 35 minutes to print and I took around 7 hours to complete this assignment.   
  
<img src="L5PRINT1.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT2.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT3.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="L5PRINT4.jpeg" alt="Part 1 Initial Sketch" width="50%" />
<img src="IMG_6348.jpeg" alt="Part 1 Initial Sketch" width="50%" />  
  
*Print Recording*  
  
https://drive.google.com/drive/folders/18uhuDUKvQ_IIpI_456J-x7gmxwxmJV_T?usp=sharing
  
*Lessons Learned*  
  
Once my part was complete, I realized the difficulty of my Snug support choice. At many points the supports were difficult to move, especially so at the lip angle which laid flat to the print surface. In reflection, I may have used paint on supports at that point, so the supports could be removed using tools a bit easier. Additionally, this assignment emphasized the importance of inputting variables in the order of intended use. Although unseen in the assignment, I rewrote several of the parametric equation lines due to this issue.

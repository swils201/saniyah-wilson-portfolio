# A7 – Linkage Mechanisms

## Objective
Design, 3D print, and document a working linkage or mechanism that performs a defined motion or task using only purchased hardware and 3D printed designed parts.
  
## Design and 3D Print
  
**Purpose**  
  
For my design, I intend to make a fidget toy part limited to one degree of motion to each interlinked segment. I was inspired to create an print in part because of an interest in the design behind articulated fidgets, which are often printed in one piece.
  
**Components**  

<img src="95114.jpg" alt="Description of image" width="50%" />
  
**Tolerances**  
For each pin, I chose a the high end of a clearance I found on OZ FDM for print in place parts. At a 0.15 inch clearance for each hole, the moving parts will be very loose. This accommodates for any necessary size-down scaling in the pre-processing process.
  
**Key Design Decisions**  
  
*Decision 1*  
The first key design decision was to use primary benchmark numbers for the dimensions used within the CAD model. Since I intended to forgo parametric design, I hoped this would keep parts proportional.
  
*Decision 2*  
I chose to only design for three moving segments. This decision aides in limiting the time cost of the supports that will be needed for printing.
  
*Decision 3*  
The last key design decision, which I accredit to my successful print in the end, was the choice to design my clearance entirely around found information on print in place parts. A smaller clearance may have led to more controlled motion, but would be more difficult on the Prusa Core One to deliver accurately.
  
**Images**  
<img src="L7_CAD2.png" alt="Description of image" width="50%" />
<img src="L7_CAD4.png" alt="Description of image" width="50%" />
<img src="L7_CAD6.png" alt="Description of image" width="50%" />
<img src="L7_CAD8.png" alt="Description of image" width="50%" />
<img src="L7_CAD10.png" alt="Description of image" width="50%" />
<img src="L7_CAD12.png" alt="Description of image" width="50%" />
<img src="L7_CAD14.png" alt="Description of image" width="50%" />
<img src="L7_CAD16.png" alt="Description of image" width="50%" />
<img src="L7_FINALCAD.png" alt="Description of image" width="50%" />
  
*Decision 4*  
Another decision seen within the CAD model, was the choice to simplify the part geometrically using symmetry throughout the design. Doing this saved time in modeling and limited the need to track dimensions.
  
*Decision 5*  
Rather than changing the elephants foot setting to fulfill the assignments requirements, I chose a random seam placement for my print. To reduce any added friction along the joints, I attempted to reduce the size of these seams by printing at a 0.1 mm layer height.
  
*Decision 6*  
The last design choice I made before printing was to scale the part to 35% in all directions. This decision cut the estimated print time down to 37 minutes, in comparison to the over hour long print time expected with original dimension. 
  
**Final Part**  
<img src="IMG_6630.jpeg" alt="Description of image" width="50%" />
  
  
**Resources:**  
- https://ozfdm.com.au/blogs/knowledge-base/print-in-place-designs-hinges-joints-and-mechanisms
- https://help.prusa3d.com/article/seam-position_151069
  
## Lessons Learned  
   
**Time**    
Research for this project took around an hour to complete. The CAD modeling and design process took between 2 to 3 hours altogether. Slicing and printing each took around 45 minutes. The print in particular took less time than I expected, as I thought I would need to reprint several times.
   
**Biggest mistake**   
The largest challenge that I encountered for this project largely surrounded choosing to jump straight to the CAD model. Because I felt unsure of my design, I thought it better to visualize and apply simultaneously. This made it difficult to revert decisions, as all were built on those placed before. Realizing my mistake in this area, I assigned the dimension for each part so that it would populate within the Global Equations for the model. Using these tables, I would be able to change measurements if necessary down the line.
  
**Tolerance**  
Thankfully, my first-print clearance was successful. I accredit this to my initial large clearance choice. Although I had not foreseen the need to scale down when I made the decision, I'm grateful that the reduction did not interfere with the intended design.
  

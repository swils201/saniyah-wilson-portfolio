# A6 – Design Fits for an Artifact

## Initial Design
  
For this weeks assignment, I designed a snap fit for an Arduino board which fits within one of the holes and accounts for interference with the pins that rest on it. To give the intended parametric design a baseline to go off of, I chose to do beam calculations to determine the minimum measurements for this artifact. Measurements were taken using a mechanical caliper and documented.   
  
<img src="L6_ARTIFACT.jpg" alt="Description" style="width: 50%;">  

Next the initial idea for the design was laid out and variables are assigned, which will be seen in the parametric design. I broke the fitting pieces of the artifact into Component 1 and 2. I chose to print this artifact using PLA because of the materials success in similar assignments.  
  
<img src="L6_COMP1.jpg" alt="Description" style="width: 50%;"> <img src="L6_COMP2.jpg" alt="Description" style="width: 50%;">  
  
Most measurements are assumed for the sake of the initial design, but those involved directly in the fit are solved using PLA-related values. I chose to use a safety factor of 4 to increase chances of success since measurements are small.  
   
**Minimum Measurement Calculations:**  
   
<img src="L6_L2.jpg" alt="Description" style="width: 50%;"> <img src="L6_L2DEFORM.jpg" alt="Description" style="width: 50%;"> 
<img src="L6_L2CHOSEN.jpg" alt="Description" style="width: 50%;">  
  
<img src="L6_W.jpg" alt="Description" style="width: 50%;"> <img src="L6_WCHOSEN.jpg" alt="Description" style="width: 50%;">  
  
  
## Parametrically Design

#### Initial Prototype
I chose to input all initial measurements or researched values which were used to find the determined minimum measurements as parameters alongside those minimum measurements. This would point out any potential calculation errors, without overly cluttering the global equations for the model.

<img src="L6_PARAMETRIC.png" alt="Description" style="width: 50%;">  
  
It can be noted from the prior artifact breakdown that measurements taken aren't ideal for the intended design. Because of this, I chose to model using the minimum values as they are directly. This would allow for a quick prototype model which can be printed and tested quickly. Having all measurements within the equations portal will make changes to this prototype easier as well.  

Another helpful change that was made was in the base plate of the part, as the additional width was unnecessary to the function and added more difficulty to printing.
  
**Prototype Modeling Visuals:**
  
<img src="L6_CAD1.png" alt="Description" style="width: 50%;"> <img src="L6_CAD2.png" alt="Description" style="width: 50%;"> <img src="L6_CAD3.png" alt="Description" style="width: 50%;"> <img src="L6_CAD4.png" alt="Description" style="width: 50%;"> <img src="L6_CAD5.png" alt="Description" style="width: 50%;"> <img src="L6_CAD6.png" alt="Description" style="width: 50%;"> <img src="L6_CAD7.png" alt="Description" style="width: 50%;"> <img src="L6_CAD8.png" alt="Description" style="width: 50%;"> <img src="L6_CAD9.png" alt="Description" style="width: 50%;"> <img src="L6_CAD10.png" alt="Description" style="width: 50%;"> <img src="L6_CAD11.png" alt="Description" style="width: 50%;"> <img src="L6_CAD12.png" alt="Description" style="width: 50%;"> <img src="L6_CAD13.png" alt="Description" style="width: 50%;"> 
<img src="L6_CAD14.png" alt="Description" style="width: 50%;">  
  
#### Prototype 2 

The failures in the first print largely came from the overall surface area of each peg and the distance between the pegs in Component 2. So, the parametric equations which relate to the distances are adjusted.
  
**Model Adjustments**  
  
<img src="L6_R1CAD6.png" alt="Description" style="width: 40%;">    

<img src="L6_R1CAD.png" alt="Description" style="width: 50%;"> <img src="L6_R1CAD2.png" alt="Description" style="width: 50%;"> <img src="L6_R1CAD3.png" alt="Description" style="width: 50%;"> <img src="L6_R1CAD4.png" alt="Description" style="width: 50%;"> <img src="L6_R1CAD5.png" alt="Description" style="width: 50%;">  

#### Prototype 3
## Documentation


#### Initial Prototype Print  
  
I followed nearly the exact slicer settings as I used in last weeks design because of the success I had with it it. One difference is the infill density set at 40% rather than 50%; a decision made because of the size of the part. Another decision, backed by similar reasoning, was to decrease the layer height to 0.1mm. 

Otherwise, system recommended slicer settings were accepted for a small print at 0.35g. Build orientation was aligned for the part to lay on one side. This allows for deposition of the filament along the flexure of the supporting beam piece. 

**Initial Prototype Sliced:**

<img src="L6_PRUSAPRINT1.png" alt="Description" style="width: 50%;"> <img src="L6_PRUSASLICE1.1.png" alt="Description" style="width: 50%;"> <img src="L6_PRUSASLICE1.2.png" alt="Description" style="width: 50%;"> <img src="L6_PRUSASLICE1.png" alt="Description" style="width: 50%;">

Unfortunately, this design was unsuccessful when printed. Measurements were too small and met the constraints of the Prusa Core One's 0.4 mm nozzle. 

**Initial Prototype Visuals:**


#### First Adjustment, Failure, and Further Prototypes

Some adjustments were made to the PrusaSlicer settings to improve the print as well. The most significant being a reduction of layer height by 50%, in hopes to achieve more accuracy.

**Prototype 2 Sliced:**
  
<img src="L6_R1PRUSASLICER.png" alt="Description" style="width: 50%;"> <img src="L6R1PRUSASLICER2.png" alt="Description" style="width: 50%;">

Although this print did not have as many failures surrounding the peg, the dimensions of both Components were just slightly off in terms of securely fitting to the part. To further specify such small tolerances, parametric equations were adjusted in trial prints 3-6. 

**Prototype 2 Visuals**

**Trial Print Visuals**
*Trial 1*
*Trial 2*
*Trial 3*
## Lessons Learned


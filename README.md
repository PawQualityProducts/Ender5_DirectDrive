# DirectDrive Mount for Creality Ender 5+ (5 Pro and 5)

## Design Considerations
This is a Simple Direct Drive Mount originally designed for the Creality Ender 5+, but may also be compatible with the Ender 5 and Ender 5 Pro.

It was developed to:
* Improve injection of filament into the Hot-End by mounting the Extruder Drive close to the Hot-End
* Provide a more even balance for the Print-Head by utilising the Extruder Drive Stepper Motor as a counter-weight to Hot-End assembly. This was done by making use of the space between the Print-Head Assembly and Carriage Rollers
<br/>
<br/>
<b>Disclaimer</b><br/>
<i>The 3D print models, STL files, instructions etc. contained in this repository may be used freely but at your own risk. No liability will be accepted for damage or loss resulting from the use of any files or information contained in this repository.</i>

## To build the Direct Drive Mount you will need:
1) The Direct Drive Mount STL files<br/>
Two versions are available:
- Version 5.1 which consists of the <a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount5.1.stl">Mount</a> file and associated <a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount5.1_Guide.stl">Filament Guide</a> file. An M3 (3mm x 20mm) bolt and nut are required to attach the Guide to the Mount.
- Version 5.2 consists of a single <a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount5.2.stl">Mount</a> file which contains both the Mount and Filament Guide (permanently attached via an integrated hinge)<br/>
<br />
<i>Build with standard settings with Full Support enabled (there's only a bit of support)</i><br />
I've also included the FreeCAD Model Files (<a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount5.1.FCStd">5.1</a> and <a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount5.2.FCStd">5.2</a>) <br />
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/Image.png" width="300" />  
<br />
2) <a href="https://www.amazon.co.uk/gp/product/B07SY745CF/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1">WINSINN Ender Aluminum Dual Extrusion Drive Feed</a> 
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/61NJfNqz1-L._SL1000_.jpg" width="200" />
<br />
3) Cable Extender ( used in Reprap 3D Printers CNC Machines):
<a href="https://www.amazon.co.uk/gp/product/B0728J6QTG/ref=ppx_yo_dt_b_asin_image_o00_s00?ie=UTF8&psc=1">UEETEK Bipolar Stepper Motor Cable for NEMA 17</a>  
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/ExtenderCable.jpg" width="200" />


## To mount onto the print-head:
1) Remove the Bowden Tube and Connector from the Hot-End  
2) Release the tension on the X Drive  
2) Remove to top two rollers from the Hot-End carriage  
3) Insert the two roller-spacers into the holes on the Direct Drive Mount  
4) Hook the Direct Drive Mount onto the Hot-End carriage, aligning the roller holes  
5) Re-mount the Hot-End carriage, attaching the rollers  
6) Attach the Bowden Tube connector to the Hot-End  
7) Measure and cut 80mm of Bowden Tube. Once fully inserted into the Hot-End and the Extruder assembly, there should be a 10mm(approx) gap between the Hot-End Bowden Tube Connector and Extruder Bowden Connector (see image below)    
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/IMG_0806.jpg" width="300" />
<i>NB: I recommend heating the Hot-End to ~190+ degress and insert the Bowden Tube into the Hot-End as far as it will go</i>   
<br />
<br />
8) Heat the Hot-End to 190 degrees then Insert the Bowden Tube into the Hot-End as far as it will go.
9) Insert the other end of the Tube into the Extruder Drive Assembly so that the Bowden Tube connects the Hot-End and Extruder Assembly <br />
9) Mount the Extruder Driver Stepper Motor and Extruder Drive Assembly onto the Direct Drive Mount, and complete Extruder Drive Assembly <br />
10) Extend the Extruder drive Stepper Motor cable and connect <br />  
<i>NB: I used <a href="https://www.amazon.co.uk/gp/product/B01EV70C78/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1">Dupont Wire Male to Female Connector Cables</a> to connect the UEETEK Bipolar Stepper Motor Cable to the existing stepper motor cable so no cutting or soldering was required</i><br />

<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/IMG_0791.jpg" width="300" />
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/IMG_0797.jpg" width="300" />
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/IMG_0795.jpg" width="300" />
<img src="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/IMG_0792.jpg" width="300" />

## Configuration
The Extuder E-Steps were calibrated when I installed the WINSINN Ender Dual Gear Extruder;<br />
However (so far), no other printer, extruder or slicer configuration setting changes have been required






# DirectDrive Mount for Creality Ender 5+ (5 Pro and 5)
By Paul.Haines@PawQualityProducts.co.uk


## Design Considerations
This is a Simple Direct Drive Mount originally designed for the Creality Ender 5+, but may also be compatible with the Ender 5 and Ender 5 Pro.

It was developed to:
* Improve injection of filament into the Hot-End by mounting the Extruder Drive close to the Hot-End
* Provide a more even balance for the Print-Head by utilising the Extruder Drive Stepper Motor as a counter-weight to the Hot-End assembly. This was done by making use of the space between the Print-Head Assembly and Carriage Rollers
<br/>
<b>Disclaimer</b><br/>
<i>The 3D print models, STL files, instructions etc. contained in this repository may be used freely but at your own risk.<br/> No liability will be accepted for damage or loss resulting from the use of any files or information contained in this repository.</i>

## To build the Direct Drive Mount you will need:
1. The Direct Drive Mount STL files<br/>
Two versions are available:
- <a href="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/DirectDriveMount_Ender5_Plus.stl">Ender 5+ version (with BLTouch)</a> <br/>
- <a href="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/DirectDriveMount_Ender5_NoBLTouch.stl">Ender 5x version (without BLTouch)</a> <br/>

A <a href="https://github.com/hainesyp/Ender5Plus_DirectDrive/blob/master/DirectDriveMount_Ender5_x_Guide.stl">Filament Guide</a> is also provided. <i>NB: An M3 (3mm x 20mm) bolt and nut are required to attach the Guide to the Mount</i>
<br/>
<br/>
<b><i>Build with standard settings with Full Support enabled (there's only a bit of support)</i></b><br/>
<br/>
2. <a href="https://www.amazon.co.uk/gp/product/B07SY745CF/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1">WINSINN Ender Aluminum Dual Extrusion Drive Feed</a> <br/>
<img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/61NJfNqz1-L._SL1000_.jpg" width="200" /> <br/>
<i>NB: If you are installing the WINSINN Extruder Drive Feed assembly as part of this Mod, then I recommend you install it first, and <b>re-calibrate the E-Step settings on your printer</b>, to ensure it's operating correctly before proceeding with the rest of the Mod</i>
<br/>
<br/>
3. Cable Extender ( used in Reprap 3D Printers CNC Machines): <br/>
<a href="https://www.amazon.co.uk/gp/product/B0728J6QTG/ref=ppx_yo_dt_b_asin_image_o00_s00?ie=UTF8&psc=1">UEETEK Bipolar Stepper Motor Cable for NEMA 17</a>  <br/>
<img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/ExtenderCable.jpg" width="200" /> <br/>
<br/>
Additionally, I used a Male-To-Male <a href="https://www.amazon.co.uk/Elegoo-120pcs-Multicolored-Breadboard-arduino-colorful/dp/B01EV70C78/ref=sxin_7_ac_d_rm?ac_md=0-0-ZHVwb250IGNvbm5lY3RvcnM%3D-ac_d_rm&cv_ct_cx=dupont+connectors&dchild=1&keywords=dupont+connectors&pd_rd_i=B01EV70C78&pd_rd_r=f2823659-b09a-47e9-97b4-100bd0d7422b&pd_rd_w=dRpYD&pd_rd_wg=Vuc46&pf_rd_p=17aec670-a34a-456d-b214-b9a882c785b0&pf_rd_r=FEM1DK97YQ3HB8MF6BSA&psc=1&qid=1594902157&sr=1-1-fe323411-17bb-433b-b2f8-c44f2e1370d4">Dupont Cable</a> to make the connection between your stepper motor cable and the extended stepper motor cable<br/>
<img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/ExtenderCable2.jpg" width="200" /> <br/>

 

4. 80mm of Bowden Tube (Capricorn Tubing recommended) <br/>
<img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/CapricornTubing.png" width="200" />
<br/>

## To mount onto the print-head:
<table>
  <tr>
    <td>
      <h3>Step 1</h3>
      <p>Heat the Hot-End to ~190 degrees then Remove the Bowden Tube from the Hot-End</p>
    </td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>
      <h3>Step 2</h3>
      <p>Allow the hot-end to cool then remove the Bowden Tube Connector from the Hot-End</p>
    </td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>
      <h3>Step 3</h3>
      <p>Release the tension on the X Drive belt, then remove to top two rollers from the Hot-End carriage<br/>
        <i>NB: It is recommended that you position the Hot-Bed so that the Print-Head carriage can be supported while the Direct Drive Mount is attached. It's also advisable to protect your Hot-Bed surface during the mounting process (eg. especially when attaching the drive stepper motor)</i>
      </p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step03.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 4</h4>
      <p>Insert the two roller-spacers into the holes on the Direct Drive Mount (Image Step 4 below) ensuring they are flush with the side that will make contact with the Print-Head mount</p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step04.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 5</h4>
      <p>Hook the Direct Drive Mount onto the Hot-End carriage, aligning the roller holes</p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step05.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 6</h4>
      <p>Re-mount the Hot-End carriage, and attach the rollers</p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step06.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 7</h4>
      <p>Attach the Bowden Tube connector to the Hot-End</p>
    </td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>
      <h3>Step 8</h4>
      <p>Heat the Hot-End to ~190 Degrees then push the 80mm length of Bowden Tube into the Hot-End as far as it will go.</p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step09.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 9</h4>
      <p>Insert the other end of the Tube into the Extruder Drive Assembly so that the Bowden Tube connects the Hot-End and Extruder Assembly</p>
      <p><i>Note that the Extruder Drive Assembly should be mounted upside down (180 degress from it's original orientation), but should otherwise be assembled exactly as it was before. This Mod does not change the function of the Extruder Drive Assembly itself, just it's mounting location and orientation.</i></p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step10.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 10</h4>
      <p>Mount the Extruder Driver Stepper Motor and Extruder Drive Assembly onto the Direct Drive Mount, and complete Extruder Drive Assembly</p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step11.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 11</h4>
      <p>Extend the Extruder drive Stepper Motor cable and connect</br>
    <i>NB: I used <a href="https://www.amazon.co.uk/gp/product/B01EV70C78/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1">Dupont Wire Male to Male Connector Cables</a> to connect the UEETEK Bipolar Stepper Motor Cable to the existing stepper motor cable so no cutting or soldering was required</i> <br/></br>
    <b>When extending Extruder drive Setpper Motor cable, be sure to reconnect correctly (ie. wire it as originally wired). You should NOT need to switch any wires. If your drive appears to be running in the wrong direction, then you have most-likely mounted the Extruder Drive Assembly incorrectly. The Extruder Drive Assembly should be mounted upside down (ie. 180 degrees from it's original orientation) but should otherwise be assembled in exactly the same way it was before. </b>
  </p>
    </td>
    <td><img src="https://github.com/PawQualityProducts/Ender5_DirectDrive/blob/master/Step12.jpg" width="300" /></td>
  </tr>
  <tr>
    <td>
      <h3>Step 12</h4>
      <p>Re-tension the X Drive Belt then test</br></p>
    </td>
    <td>&nbsp;</td>
  </tr>
</table>


## Configuration
The Extuder E-Steps were calibrated when I installed the WINSINN Ender Dual Gear Extruder;<br />
However, no other printer, extruder or slicer configuration setting changes have been required.






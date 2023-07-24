===============================================================================
|          Complete design files for Intermediate-Rate Tension Device         |
-------------------------------------------------------------------------------
| L. Summey (1), J. Zhang (1), A. K. Landauer (2), J. Sergay (3), J. Yang (4),| 
| A. Daul (1), J. Tao (1), J. Park (1), A. McGhee (1), C. Franck (1)          |
|                                                                             |
| 1 Department of Mechanical Engineering, UW-Madison, Madison, WI, 53706      |
| 2 National Institute of Standards and Technology, Gaithersburg, MD, 20899   |
| 3 Department of Biomedical Engineering, UW-Madison, Madison, WI, 53706      |
| 4 Department of Aerospace Engineering & Engineering Mechanics, UT-Austin,   |
|   Austin, TX, 78712                                                         |
| July 19, 2023                                                               |
| see github.com/FranckLab/Intermediate-Rate-Tension-Device for contact info  |
| and other updates                                                           |
-------------------------------------------------------------------------------

*******************************************************************************

===============================================================================
|          Summary and description of use:                                    |
-------------------------------------------------------------------------------

These folders contain all the files necessary to assemble the published tension
device and the compatible test specimens. Files include CAD designs ready to 3D
print (.step), aluminum parts to cut (.step), photolithography sample mold
shapes (.dxf), and parts to purchase.

An additional folder is added to modify the original device design to be a
compression device. 


*******************************************************************************

===============================================================================
|              Tension device designs:                                        |
-------------------------------------------------------------------------------
- Tension Device Assembly.step (Assembly file for entire tension device with all individual parts that can be found in more detail below) 

- Device 3D Printed Parts (parts to 3D print)
    + Motion Control Knob 
    + TensionDevice - Impact Grip
    + TensionDevice - Sample Dish Holder
    + TensionDevice_Rail Mount
    + Timing Belt Tensioner

 - Device Purchased Parts (CAD of each part that needs to be purchased through 
   third party venders)

 - Waterjet Cut Aluminum Parts (aluminum parts to be created to the specifications of the CAD files with a watercut jet)
    + Tension Device_Z-Stage_Aluminum.step
    + TensionDevice_Nikon Baseplate Mount.step
    + TensionDevice_NikonBaseplate.step
    + TensionDevice_TopPlate_Aluminum.step


===============================================================================
|              Test sample parts for various tensile speciments:              |
-------------------------------------------------------------------------------
The following files are used to create the parts needed for the samples tested in the tension device (as seen in Fig. 3 of the paper) 

- Samples
    + PDMS (Fig. 3A - thin dogbone-shaped specimen made from polydimethylsiloxane)
        + 10mm PDMS Sample - F_Gripper.step (1 grip to hold specimen)
        + 10mm PDMS Sample - M_Gripper.step (1 grip to hold specimen)
        + 10mm PDMS Sample - Holder (part to aid in the assembly of PDMS dogbones into the 2 grippers)
        + SU8 Patterned Figure - SU8.dxf (pattern used to create a dogbone mold from UV patterned SU8 on silicon wafers)
    + Foam (Fig. 3B - dogbone-shaped foam specimen)
	+ 2mmFoamSample - F_Gripper.step (1 grip to hold specimen)
        + 2mmFoamSample - M_Gripper.step (1 grip to hold specimen)
    + Hydrogel (Fig. 3C - hydrogel dogbone for 3D samples)
        + 7mm Hydrogel Mold - F-grip.step (1 grip to hold the specimen)
        + 7mm Hydrogel Mold - M-grip.step (1 grip to hold the specimen)
        + 7mm Hydrogel - Sample Mold.step (mold to pour the hydrogel into)


*******************************************************************************

===============================================================================
|              Compression Device:                                            |
-------------------------------------------------------------------------------
An additional folder has been added with parts needed to modify the tension device to be a compression device

- Compression Modifications
    + Compression - Baseplate for 155mm x 185mm Stage.step
    + Compression - Impact Grip.step
    + Compression - Magnetic Mount Plate.step
    + Compression - Rail Mount (One Motor).step
    + Compression - Sample Holder Base.step
    + Compression - Sample Holder Cap.step
    + Compression - Sample Mold Base.step
    + Compression - Sample Mold Side.step
    + Compression - Stationary Sample Grip.step
    + Compression Motor Mount Plate.step
    + Compression Sample - Stamp_Hamburger.step
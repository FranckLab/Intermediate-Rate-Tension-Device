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

- Device 3D Printed Parts (Parts to 3D print)
    + Motion Control Knob (Rotates the four T8 Lead Screws with the Timing Belt)
    + TensionDevice - Impact Grip (Connected to part '8381K3' which sits on the rail. A cylindrical magnet is placed in the top of the impact grip which connects the impact grip with a metal screw at the end of the linear actuator of the motor)
    + *TensionDevice - Sample Dish Holder (Holder for a 1-well rectangular sample dish)
    + TensionDevice_Rail Mount (Connects the rail to the 'Z-Stage_Aluminum')
    + Timing Belt Tensioner (Placed on top of the 'TopPlate_Aluminum. A cylindrical piece must be placed in the top of it to hold the timing belt in tension)

 - Device Purchased Parts (CAD of each part that needs to be purchased through 
   third party venders)

 - Waterjet Cut Aluminum Parts (Aluminum parts to be created to the specifications of the CAD files with a watercut jet)
    + Tension Device_Z-Stage_Aluminum.step (Connected to the four T8 Lead Screws, the two impact grips, and the rail mount)
    + *TensionDevice_Nikon Baseplate Mount.step (Mounts motors to either side of the baseplate)
    + *TensionDevice_NikonBaseplate.step (Aluminum plate with dimensions that fit a microscope stage)
    + TensionDevice_TopPlate_Aluminum.step (Top of device to mount the rail and control knob)

* Denotes parts that might need to be adapted depending on the user's microscope system or sample dish size

===============================================================================
|              Test sample parts for various tensile speciments:              |
-------------------------------------------------------------------------------
The following files are used to create the parts needed for the samples tested in the tension device (as seen in Fig. 3 of the paper) 

- Samples
    + PDMS (Fig. 3A - thin dogbone-shaped specimen made from polydimethylsiloxane)
        + 10mm PDMS Sample - F_Gripper.step (one grip to hold specimen)
        + 10mm PDMS Sample - M_Gripper.step (one grip to hold specimen)
        + 10mm PDMS Sample - Holder (part to aid in the assembly of PDMS dogbones into the 2 grippers)
        + SU8 Patterned Figure - SU8.dxf (pattern used to create a dogbone mold from UV patterned SU8 on silicon wafers)
    + Foam (Fig. 3B - dogbone-shaped foam specimen)
	+ 2mmFoamSample - F_Gripper.step (one grip to hold specimen)
        + 2mmFoamSample - M_Gripper.step (one grip to hold specimen)
    + Hydrogel (Fig. 3C - hydrogel dogbone for 3D samples)
        + 7mm Hydrogel Mold - F-grip.step (one grip to hold the specimen)
        + 7mm Hydrogel Mold - M-grip.step (one grip to hold the specimen)
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


*******************************************************************************

===============================================================================
|              Citation                                                       |
-------------------------------------------------------------------------------
TBD


*******************************************************************************

===============================================================================
|              Contact and Support                                            |
-------------------------------------------------------------------------------
Email: Jing Zhang (jzhang2338@wisc.edu) or Prof. Christian Franck (cfranck@wisc.edu)

# Advanced Semiconductor Packaging Course
This is a course on advanced semiconductor packaging offered by VSDIAT organized by Mr. Kunal Ghosh in collaboration with IIT Gandhinagar.

## Lab 1

In this lab, we use Ansys Electronics Desktop (AEDT) to perform thermal simulation of a Flip Chip Ball Grid Array (FC-BGA) package. We import an exisitng FC-BGA package from the Icepack tool and perform thermal analysis to identify the thermal hotspots.

### Importing the FC-BGA package and observing the structure:

IcePack -> ToolKit -> Geometry -> Packages -> Select the package to be analyzed.

![FC_BGA_Structure](https://github.com/user-attachments/assets/1f4e5d38-e136-4ba0-9ba9-c0837cecb198)


Next, we set the boundary conditions in the thermal analysis where the total power of the package is 1 W. 
We also select the point monitor for all the layers in the packge and select the temperature.
Next, we generate and build the mesh.

### Generating the Mesh:

![FC_BGA_Mesh](https://github.com/user-attachments/assets/edb02a3a-4396-45d3-acd8-ddf167747fca)


We perform validation and using the "Validate" button to ensure the analysis setup is correct.


### Thermal Simulation and Analysis:

Select the desired structure or layer and select the plot fields and temperature to view the thermal analysis. 
Then select the desired structure -> Enable the specify name and specify folder fields -> set quantity as Temperature and enable "Plot on surface only" at the bottom right to view the thermal simulation results of the FC-BGA. 

![Thermal_Simulation_FCBGA](https://github.com/user-attachments/assets/9dfdeb39-233f-4f95-bf0d-f44755edc6fc)
![Thermal_Simulation_FCBGA_1](https://github.com/user-attachments/assets/c042e3c4-6a9f-4a69-825c-c3cf74d08a73)



## Lab 2

In this lab, we use the Q3D tool to design our own custom package from scratch.  

### Step 1: Creating a Die:

Draw a rectangle with required die dimensions using the Draw rectange option. 
To make it 3D, we can thicken the sheet by selecting the rectange -> Click on Modeler -> Surface -> Thicken Sheet -> Enter desired thickness value.

### Step 2: Creating a Substrate:

We draw another rectange with larger dimensions compared to the die and follow the same process to make it into a 3D model by using thicken sheet option. 

For both the die and substrate, change the material to Silicon and Epoxy respectively in the properties section of each structure. 

![L2_Day_4](https://github.com/user-attachments/assets/720dd4b6-dfaf-4a73-91c3-e14c997f0664)


### Step 3: Creating a Die Attach and Bond Pads:

Use the draw rectangle option to create a die attach layer which goes in between the substrate and the die. Draw the bond pads and position them according the design specifications along the edge of the die and substrate.

![L3_Module5](https://github.com/user-attachments/assets/516c35f1-5dfa-40b9-839c-e0295f941898)

### Step 4: Creating the Wire Bonds

Next, draw a wirebond to connect the die bond pads and substrate bond pads. Set the properties of the wirebonds based on the design specifications and select the desired material (Gold). 

The process can be repeated for drawing the requried package design for further thermal or electrical analysis.


![L4_Module5](https://github.com/user-attachments/assets/c820a224-bcc0-4a8d-a74b-6c5e57c7424d)

### Step 5: Creating a Mold Compound:

Finally, we create another rectange to cover the entire substrate and fill it with a mold compound. We use an epoxy material as the mold material. 

![L5_Module5](https://github.com/user-attachments/assets/68574b77-1ee3-48a6-b781-3e04eb7ad8aa)

This completes the package design for this course. 

## Acknowledgement

I would like to thank Mr. Kunal Ghosh for organizing this online course on introduction to semiconductor packaging. 



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



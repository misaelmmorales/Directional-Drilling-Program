# Directional Drilling & Completions Program

This is a Macro-enabled Excel document with 3 main parts: <br/>(1) Directional Drilling survey, (2) Drag & Torque model, and (3) Completions & Casing check. <br/>The purpose it to simulate a 3D drilling trajectory based on user-defined inputs, perform drag and torque checks on the drilling trajectory, and then design the casing program on the simulated well. VBA is used to design this program.
***

**Directional Drilling Survey**
User-defined inputs include surface and subsurface coordinates, KOP, Build/Hold/Drop parameters, and survey technique (8 options to choose from). 
80 points are computed on a 3D surface based on the survey technique selected. From the other user inputs, a build, hold, and drop section are optimally estimated to reach the target coordinates. Drilling metrics are computed, and a tolerance calculator will estimate the error between the model and the desired target coordinates.
<img src="https://github.com/misaelmmorales/Directional-Drilling-Program/blob/main/images/tool_1.png">

**Drag & Torque Model**
We compute the drag and torque forces acting on the simulated drilling trajectory. The user can define parameters such as FF, ROP, WOB, Fh, and tubular size in order to compute tension, drag force and torque force, and warn for possible buckling.
<img src="https://github.com/misaelmmorales/Directional-Drilling-Program/blob/main/images/tool_2.png">

**Completions & Casing Check**
The user can specifiy up to 9 possible casing types, and we compute the burst-collapse design lines, and perform checks for each casign at each depth, to select the best possible well completions design.
<img src="https://github.com/misaelmmorales/Directional-Drilling-Program/blobl/main/tool_3.png">

## 3-D Printing

3D printing, also known as additive manufacturing (AM), refers to processes used to create a three-dimensional object in which layers of material are formed under computer control to create an object Objects can be of almost any shape or geometry and are produced using digital model data from a 3D model or another electronic data source such as an Additive Manufacturing File (AMF) file. STL is one of the most common file types that 3D printers can read.

## Steps in 3-D Printing 

* > Design your file in Rhino or any other similar tools .
   <img src="http://jitheeshk.github.io/threedprinting.github.io/Screenshot (37).png">
   We can use the toolbar or directly use the commands using COMMAND tab . Some commands are listed below :
   1. ExtrudeCrv
   2. Cap
   3. BooleanDifference
   4. BooleanUnion
   5. Group and Ungroup
   
   Detailed list of commands used in Rhino could be seen [here](https://docs.mcneel.com/rhino/5/help/en-us/commandlist/command_list.htm)
* > After desiging the model in Rhino select the entire design and click file -> Export selected. Then a dialog box appears . Then in the    "save as type" section select .stl format and give a meaningful name.
   <img src="http://jitheeshk.github.io/threedprinting.github.io/Screenshot (38).png">
* > Now open the .Stl file in Cura and generate the gcode.
    Use the following data :<br/>
    Nozzle and material : 0.6mm and PLA (Increase the nozzle size to reduce the time )<br/>
    Profile : Fine<br/>
    Infill : Select as per how much strength we need . The more we select the greater will be the strength also greater will be the time required for printing .<br/>
    Now click "Save to file" and generate the gcode .
    <img src="http://jitheeshk.github.io/threedprinting.github.io/Screenshot (39).png">
* > Now put the memory card in Ultimaker 2+ and navigate to our file and select print .
 



# Mesh2Solid_FreeCAD
A macro to convert a mesh to a solid in FreeCAD

The macro internally executes 5 processes
- Analyzes the number of mesh elements, if there are more than 1 it shows a message
- Analyzes the number of faces in the mesh...if it exceeds 100,000 faces it shows a message
- Create the shell
- Perform a refinement
- Create a solid (shell and refining are removed)
  
This process is visually accompanied by a progress bar

## How to use
- Select the mesh
- Run the macro
- When the process is finished, it creates the solid object


![capture](https://github.com/andesfreedesign/Mesh2Solid_FreeCAD/blob/main/mesh2solid.gif)

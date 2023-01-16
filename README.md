# freecad-macro-MeasureDistance

This macro is just an exercise. It does technically work similar as the yellowish round measurement icons, except I have no GUI whatsoever. Simply printig to stdout. If you come here because the blue ruler is annoying, it does not snap, it cannot do angles, etc... then you are wrong here. Use the Measurement icons that do not look like a ruler. They snap perfectly fine, and do a wonderful job.

1) Copy the file MeasureDistance.FCMacro to your ~/.local/share/FreeCAD/Macro/ folder.
   (The personal macro folder could also be ~/.FreeCAD/Macro/ )
2) (Re)start freecad,
3) open Part or Part Design workbench 
4) Create some object (cube, Cone, Sketch, Pad, Cut, ...)
   - or import an STL, Part -> Create Shape from Mesh ...

5) Click a vertex at one end of the object and another vertext a the other end.
   -> select Macros -> MeasureDistance
   -> distance between the two vertices is printed to the shell where freecad was started.
6) Select an two parallel Edge of the object
   -> select Macros -> MeasureDistance
   -> The shortest distance between the edges is printed to the shell.
      If the edges are offset, then the shortest distance is from nearest vertex to nearest vertex.
      If the edges are not parallel or curved, warnings are printed.
7) Select an Edge of the object
   -> select Macros -> MeasureDistance
   -> The length of the edge is printed. (Together with "INFO: Only one Edge given. Measuring length:")



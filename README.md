# freecad-macro-MeasureDistance

1) Copy the file MeasureDistance.FCMacro to your ~/.FreeCAD/Macro/ folder.
2) (Re)start freecad,
3) open Part or Part Design workbench 
4) Create some object (cube, Cone, Sketch, Pad, Cut, ...)
   - or import an STL, Part -> Create Shape from Mesh ...

6) Select an Edge of the object
   -> select Macros -> MeasureDistance
   -> The length of the edge is printed to the python console.
7) Click a vertex at one end of the object and another vertext a the other end.
   -> select Macros -> MeasureDistance
   -> distance between the two vertices is printed to the python console.



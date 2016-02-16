Customize  
---------

_Please don't scale the .stl._ You can adjust the design according to your needs by editing the variables in the attached OpenSCAD file.  

Customizable parameters are:  

- __material thickness__ and __spaces__ between the different pieces  
- __length__ and __radius__ of the rod  
- __height__ of the pillars  
- __length__ and __height__ of the bases  

The __material saving mode__ that makes the pieces hollow can be disabled, even though they should already be robust enough.  


Print  
-----

Comment out the preview function call (put "//" before "preview\_all()") and uncomment the ones concerning the pieces that you want to make, or "print\_all()" if you want to print all pieces on one tray.  

Then, _compile and render (F6)_, _export as STL_ and _slice_ :)  

Sucessfully printed using:  

- __ABS__ and __PLA__  
- __20%__ infill  
- __0.3mm__ layer height

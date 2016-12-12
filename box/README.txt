                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:643264
Generic case and lid - improved by Printbus is licensed under the Creative Commons - Attribution - Share Alike license.
http://creativecommons.org/licenses/by-sa/3.0/

# Summary

This improves on davidmpye's generic case (box and lid) from http://www.thingiverse.com/thing:28608.  The changes should provide improved dimensioning over a wider range of parameters. The lid should fit the box better, and an option has been provided to add a mounting flange.  

As with davidmpye's design, roundCornersCube.scad from http://www.thingiverse.com/thing:8812 is used for the basic box.  nophead's polyhole.scad is used for creating the small holes.     

The Rev A files provide a more refined utilization of openSCAD for the designs.  More dimensions can be individually tailored. For example, the wall thickness, base thickness, and lid thickness can all be set independently.  A table of reference dimension data for common hardware is included in the source file. The mesh overlap between elements has been improved to minimize "ghosting" in the render view.  Echo outputs have been added to the console output for key calculation results.  The path to roundCornersCube and polyhole have been revised to openSCAD standard library locations. 
 
The provided revA STL is a sample output for a 50mm x 70mm x 15mm box and lid with 2.0mm wall thickness.  Lid mounting posts are sized for a #4 screw.   The sample box shows how board mounting posts can be added to the box bottom, and show how various hole types can be added to the sidewalls and lid.  The code for the sample posts and holes is present in the revA openSCAD source, but is commented out. The STL file is provided as a sample output, not necessarily as a box useful to anyone.  

# Instructions

Download roundedCornersCube.scad and install it in the openSCAD CUSTOM library location.   

Revise the tailorable parameters in the Generic case improved revA.scad file for the desired box configuration.   The radius for the box corners and the diameter for the lid mounting posts are derived from the hole diameter you specify for the lid corner posts. Review comments throughout the openSCAD file for more information.  Uncomment and tailor the provided sample board mounting posts and box holes, or add your own.  

Edit the top level geometry line to indicate whether you want the lid, the box, or both generated.
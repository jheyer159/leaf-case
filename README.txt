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


http://www.thingiverse.com/thing:471661
Beaglebone Black Slim Case by Scuttlebot is licensed under the GNU - GPL license.
http://creativecommons.org/licenses/GPL/2.0/

# Summary

******************************************************************   
## NEWS: Version 2 released! See below for details.  
******************************************************************  

## CASE DETAILS  

This is a slim line case for the Beaglebone Black development board that was developed with the following goals in mind:  
-Minimize volume and plastic used  
-Expose all eternal ports   
-Expose pin headers for development  
-Code with OpenSCAD for easy modification  
-Tight tolerances to secure board when moving around
-Include pin header diagram that can print on standard shipping labels  

See instruction section for printing and label details

The OpenSCAD source files are attached and can be used to modify the case with options at the top of the file. The library file is a good reference for board dimensions in other projects.  
*******************************************************  

## UPDATES  

*1-23-15:* Version 2 OpenSCAD files posted  
Cleaned up the OpenSCAD files and posted them to the source files list. The Beaglebone dimension constants were moved to an external library file to help clean up the main code file. If you want to make your own BBB accessory you might find this useful and save yourself a bunch of work!  

*12-30-14:* Version 2 released!  
Updated based on my experience carting the case around in my backpack for three months.  

* Thickened the wall slightly for better rigidity  
* Strengthened the tabs that secure the lid for better grip and to help prevent snapping off during case abuse.  
* Added extra area to the bottom of the board pegs to prevent snapping off after excessive use.  
* Used a better library for creating the rounded corners that should make for smoother slicing  
* Moved all of the dimension constants from the main OpenSCAD file to a library file to help code readability.  

*9-22-14:* Added dimensionally accurate pin header labels!  
Thanks to my amazing wife for creating this. See instructions for info  

# Instructions

*******************************************************  
##3D Printing Information  
The case does not require any external hardware at this time. The case shown was printed on a Lulzbot Taz 4 and sliced with Slic3r using the following settings:  
2 Perimeters  
2 Solid Layers top and bottom  
30% infill  
Green PLA at 190C  
*******************************************************  
##Snug Fit
The board tolerances are tight to securely hold the board in place while carrying around. This works great for the majority of users but in a few cases when a printer slightly over extrudes or is printed with a material that requires large perimeters then the beaglebone may be a bit too snug. Two options are to either reduce perimeter extrusion width or print at 102% scale. Both have been reported to work by different users. 

##Pin Header Label:   
The included label PDF file is made to print on Avery 4"x2" shipping labels that can be found at any office supply or department store. The label spacing is 0.1" to physically match the locations of the pins. Just print, cut, and line up.  
*******************************************************  
##OpenSCAD  
You will need both the base scad file and the library file in the same directory to work. The base scad file has several options at the top to modify what model is generated. The settings and their effects are listed in the comments.  

The scad files are provided open source so feel free to modify and borrow from as you wish. The library file is useful if you would like a pre-created list of all Beaglebone Black dimensions. If you do use my code for other projects a link back or reference is always appreciated but not necessary. I love to see what other can build from my work!
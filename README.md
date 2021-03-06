OBJLoader Processing library
============================

OBJ file loader library for Processing.

This library was originally developed by SAITO and Matt Ditton (AKA Polymonkey). 
https://code.google.com/p/saitoobjloader/
http://thequietvoid.com/client/objloader/

The only improvements I made are:

- added repository on GitHub
- added a `getVertices()` method that returns an array of PVector representing all the vertices of the model



Installation
============

Contributed libraries must be manually placed within  the "libraries" folder of your Processing sketchbook. To find (and change) the Processing sketchbook location on your computer, open the Preferences window from the Processing application (PDE) and look for the "Sketchbook location" 
item at the top.

Copy the contributed library's folder into the "libraries" folder at this 
location. You will need to create the "libraries" folder if this is your first 
contributed library.

By default the following locations are used for your sketchbook folder: 
-  For Mac users, the sketchbook folder is located inside
  - ~/Documents/Processing. 
-  For Windows users, the sketchbook folder is located inside 
  - 'My Documents'/Processing.

The folder structure for the OBJ loader library should be as follows:

- Processing
  - libraries
    -  OBJLoader
      -  examples
      -  library
        -  OBJLoader.jar
      -  reference
      -  src
                      
Some folders like "examples" or "src" might be missing. After library 
OBJ file loader has been successfully installed, restart the Processing 
application.

If you're having trouble, have a look at the Processing Wiki for more 
information: http://wiki.processing.org/w/How_to_Install_a_Contributed_Library

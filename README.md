# KICAD_Footprints
Custom, modified, and unusual Footprints used in my Kicad projects.

Details, please see the blog post:
https://audiodiwhy.blogspot.com/2023/09/kicad-making-switch.html

Import the .mod files into a Kicad custom footprint folder:

--File → Import Footprint from KiCad File. Select the .kicad_mod footprint file that you would like to use.\
--Double click the imported footprint.\
--Save the footprint to your project or global footprint library.

Note--footprints that come with Kicad are read only.  
Creating a new library for imported footprints:
https://learn.sparkfun.com/tutorials/beginners-guide-to-kicad/creating-a-custom-kicad-footprint-library

Getting 3D models to work  
--I have already changed any wrl's to step (for Kicad 10) \
--Get the 3D model zip from the "3D_MODELS" cslammy repo \
--Unzip it somewhere \
--Create a new Conf path in Kicad called ${CLOUD_DIR_3D} \
--Point the Conf path to where you unzipped the 3D files\
--3D files are organized by type (POT, JACK, SWITCH) etc.


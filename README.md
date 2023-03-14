# PCG-in-Minecraft
A PCG method to procedurally build a house in the Minecraft world with more than one billion variations.
Interacting with Minecraft with GPDC interface.

Tested with python 3.9 and game version 1.19.2 Java.

Script files include the following:
materials.py    Specifying the materials might be chosen for building the house.
terrain_scan_ex_water   A terrain scaner that find the best location to start building.
structure.py    Agent used to build the main structure of the house.
ext_deco.py   Agent used to build external decorations.
int_deco.py   Agent used to build internal decorations.
PCG_RL.py   Main program file.

Put all scripts into one root folder.
Specify building area and run PCG_RL.py file. Wait for house to be generated.

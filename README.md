# PCG-in-Minecraft

This project presents a procedural content generation method to build a house in the Minecraft world, with more than one billion variations. It uses GDPC interface for interacting with Minecraft.

## End-Of-Life Notice
This project has been incorporated into a broader project with similar approaches, which you can find in the following link https://github.com/RylinnM/Minecraft-World-Creation. Further development of this repository is terminated as of this moment.

## Compatibility

Tested with Python 3.9 and Minecraft game version 1.19.2 Java.

## Files

The following script files are included in this project:

- `materials.py`: Specifies the materials that might be chosen for building the house.
- `terrain_scan_ex_water`: A terrain scanner that finds the best location to start building.
- `structure.py`: Agent used to build the main structure of the house.
- `ext_deco.py`: Agent used to build external decorations.
- `int_deco.py`: Agent used to build internal decorations.
- `PCG_main.py`: Main program file.

## Usages
Before excuting the file, make sure GDPC interface is adequately installed and activated.
To run the project, put all scripts into one root folder, specify the building area, and run `PCG_main.py` file. Wait for the house to be generated.




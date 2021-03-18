# WARNING NOT YET COMPLETE, DO NOT USE, PLEASE CHECK AGAIN OR FOLLOW FOR FINAL RELASE

# AudioJacks
KiCAD footprint library and 3D models for commonly used connectors used in synths and other audio equipment.

# Directory structure
* 3Dmodels - The .step files used by KiCAD for the PCB rendering
* AudioJacks.pretty - the KiCAD footprint library
* Assets - Images and other items used for this documentation
* FreeCAD_Drawings - The modifiable FreeCAD used to generate the 3dmodels

# Installation (KiCAD 5.1)

### Footprints via footprint editor
* Copy to chosen location for your custom KiCAD libraries, this could be the default one or anywhere on your disk.
* Open the footprint editor and choose `File > Add Library` pick the `AudioJacks.pretty` folder and click open
* Choose `Global` as the file table to add it to 

### Footprints via PCBnew
* Select `Preferences > Manage footprint libraries`
* Under `Global Libraries` tap, choose the folder icon `Add existing library to table`
* Find `AudioJacks.pretty` and press open

### Using the 3D models
I am still undecided how this works, I need to investigate how best this works. Adding 3D files manually puts in an absolute directory based on it's location on the computer so when the project is shared the models can not be found.

# Licence

I have attached an MIT licence, it is free to use and modify for any use. I don't beleive in licences as they are only useful for the super wealthy who can afford gambling on litigation and in the end the only people that really win are the lawyers. Hopefully it will help if you need the proof that I won't come after you, all work here is original, no files are derivative of other copyrighted work such as manufacturer 3D models for example.

# UnityTools
Some custom tools I use for Unity stuff
* MagicaVoxelHelper - Helper class to load data from MagicaVoxel's .vox files
  * Usage: Call MagicaVoxelHelper.ReadFile() and pass in a BinaryReader of the .vox file (which should be renamed to a .bytes file so that Unity imports it correctly). It will return a list of voxel position and colors, as well as the size of the model.
 

#Cube 64 to OMX Converter

This converter is based heavily on Billy's and Elizabeth's code at
https://github.com/osPlanning/cube2omx with changes for:
* 64 bit
* MS Visual C++ 2013

#Major changes

Cube.io packing - the packing method used in the original code does
not work under MSVC++.

#Requirements
HDF5 64-bit dlls

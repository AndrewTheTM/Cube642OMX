# 2019 UPDATE

If you are using Cube 6.4.4 (June 2018) or later (and possibly a slightly earlier release) YOU DO NOT NEED THIS! Run a pilot script that looks like this:

<pre>CONVERTMAT FROM="filename.MAT" TO="filename.omx" FORMAT=OMX COMPRESSION=0</pre>

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

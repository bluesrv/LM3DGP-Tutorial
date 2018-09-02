# LM3DGP-Tutorial
Public fix to Learning Modern 3D Graphic Programming for all platforms

## To build tutorial in Ubuntu:
```
sudo apt-get install premake4
cd folder/to/tutorial
cd glsdk
premake4 gmake
make
cd ..
premake4 gmake
make
```
All file linkings and dependencies should be handled by the premake4.lua script that we ran with the above code, so this should do it all.

### Fixes from original version:

* Including "X11" as a dependencie in Ubuntu

* Adding a few variables and functions declarations in Inteprolations.h at /framework/

# Pulse Coupled Neural Netwrok (PCNN) with Remote Sensing Image
This project can be divided in several parts. Short descriptions are given below. All the necessary and detailed documentation is added with the notebook corresponding cells.

### Module 1: Remote Sensing MODIS Data
Primarily the data folder containing a .hdf file which is downloaded from NASA LAADS DAAC.
This file is MODIS Terra satellite .hdf file which contains lots of metadata. The used hdf file should be downloaded from the NASA website as this file is huge in size.

### Module 2: Basic PCNN
MODIS single band is used for implementation of basic PCNN.
#### Visualization and Oscillation
Using single band of MODIS visualization and oscillation of pulses are shown here.

### Module 3: Image Fusion Application with Improved PCNN
MODIS 34 bands are used for image fusion with improved PCNN. 
#### Improved PCNN
Here some modifications are applied from traditional PCNN. Simplified and improved version is implemented here.
#### Image Fusion
MODIS 34 bands are used for band fusion.


#### References
1. Miao, Q., & Wang, B. (2005, May). A novel adaptive multi-focus image fusion algorithm based on PCNN and sharpness. In Sensors, and Command, Control, Communications, and Intelligence (C3I) Technologies for Homeland Security and Homeland Defense IV (Vol. 5778, pp. 704-712). International Society for Optics and Photonics.
2. Image processing using pulse-coupled neural networks Book by Thomas Lindblad

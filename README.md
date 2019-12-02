# CNN Bragg spots
Code related to Journal of Synchrotron Radiation paper FV5080
Tsung-Wei Ke, Aaron S. Brewster, Stella X. Yu, Daniela Ushizima, Chao Yang, and Nicholas Sauter (2018)

Published as "Ke, Brewster, Yu, Ushizima, Yang and Sauter, “Convolutional Neural Network-based Screening Tool for X-ray Crystallography”, Journal of Synchrotron Radiation 2018.

Explanation:
Raw data (five datasets) may be downloaded from the Coherent X-ray Imaging Data Bank at the following URL:
http://cxidb.org/id-76.html
Please note that each file is large (about 13 GB). 

Data are written in HDF5 format, 2000 images per dataset.
Image data may be viewed with the program dials.image_viewer as follows:
1) Download the DIALS program from https://dials.github.io
2) Work on your local machine--slow X-connections will stall.
3) Download the FormatHDF5ImageDictionary.py file from this repository and place it in the following new directory
   created on your local filesystem;  ${HOME}/.dxtbx/
4) Use the command dials.image_viewer <*.h5 file>



# NeffStudy
Study Neff constraints S4+others

Modules should be run from the parent directory, e.g.:
  `python py/21cm.py Class`
or
  `python py/21cm.py Camb`
in order to run the Fisher forecast with either the CLASS or CAMB Boltzmann codes.

## Requirements
- numpy
- scipy
- matplotlib
- SNR data cube from Cosmic Visions (see below)
- h5py
- pickle
- CLASS and/or CAMB Boltzmann codes:
- -[CLASS code and its python wrapper classy](http://class-code.net/)
- -[CAMB code and its python wrapper](http://camb.info)

Here, the signal-to-noise ratio (SNR) is computed in a simulation from Cosmic Visions:
- [SNR Data Cube from Cosmic Visions](http://www.phas.ubc.ca/~richard/sn_lowz_expA_50K.h5). This h5py file should be kept in the parent directory.
- [Cosmic Visions Fisher repo](https://github.com/radiohep/CVFisher)


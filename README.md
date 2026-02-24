# SOLERwave

SOLERwave is a python tool developed to facilitate the investigation of large-scale coronal waves and Moreton waves.
It consists of the wave tracing tool itself and accompanying functions for file loading and handeling.

## Setup
SOLERwave requires a Python installation of 3.10 or newer. 

Further required packeges are

* jupyter 1.1.1
* numpy 2.2.3
* astropy 7.0.2
* sunpy 6.1.1  => pip install sunpy[all]
* numba 0.61.0
* moviepy 2.1.2

Alternatively the Jupyter notebook "Install_packages.ipynb" can be run after the installation of Python and Jupyter. 
It will check the availability of the packages required and download any missing. Note, it will not check the version
of packages already installed. 

## Download Observations

To Download new Observations, follow the Load_new_event Jupyter Notebook. ** !! DO NOT EXECUTE the whole Notebook at once, but cell by cell !!**.
It contains multiple examples, you might not want to download and preprocess all of them at the same time. Do not forget to 
create the "Data_folder" folder before attempting a download.

Currently the following Instruments are supported/ have been tested:
- SDO/AIA
- STEREO/SECHII
- GONG H-alpha (download is observatory specific)
- Kanzelhoehe H-alpha

## Wave Tracing Tool
In order to use the tool on the downloaded data, one of the pre-programmed Jupyter notebooks for 
events should be used. Currently one is included for the EUV observations based on a wave observed
on the 6th September 2011 by SDO/AIA in 211 Angstrom.

## Citation

If you use the tool, please cite "Baumgartner-Steinleitner et al. 2026 (in preparation)"

## Miscellaneous
This project has received funding from the European Union's Horizon Europe research and innovation program under grant agreement No 101134999.  As part of the grant agreement the tool will be made public.
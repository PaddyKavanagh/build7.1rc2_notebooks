# build7.1rc2_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (build 7.1rc2) for MIRI data within python. 

Build 7.1rc2 of the JWST calibration pipeline can be installed into an Anaconda environment as follows:

conda create -n jwst --file <URL>

where <URL> is:

Linux: http://ssb.stsci.edu/releases/jwstdp/0.7.8/dev/jwstdp-0.7.8rc2-linux-py27.0.txt

OS X: http://ssb.stsci.edu/releases/jwstdp/0.7.8/dev/jwstdp-0.7.8rc2-osx-py27.0.txt

The CRDS context should be set to jwst_0361.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0361.pmap"


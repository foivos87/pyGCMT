# pyGCMT
A python script, using ObsPy tools, to generate Global CMT solution catalogues.

<a href="https://zenodo.org/badge/latestdoi/510420825"><img src="https://zenodo.org/badge/510420825.svg" alt="DOI"></a>

There are 2 files contained in this repository:

1) A python script, pyGCMT.py, which can be launched from a terminal, to generate the GCMT catalog.
2) A jupyter notebook, pyGCMT.ipynb, which generates the GCMT catalog and a map of the focal mechanisms for the downloaded events.

There are 2 output files:

1) The CMTSOLUTIONS, which is the Global CMT convention text file, containing the catalog of the requested events
2) A temporary, temp.xml, file, which contains the same information in a QUAKEML format.

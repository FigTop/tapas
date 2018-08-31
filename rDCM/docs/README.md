Regression dynamic causal modeling (rDCM)
====================


> Copyright (C) 2016-2018 

> Stefan Frässle <stefanf@biomed.ee.ethz.ch>, Ekaterina I. Lomakina



> Translational Neuromodeling Unit (TNU)

> Institute for Biomedical Engineering

> University of Zurich & ETH Zurich


Download
-------

- Please download the latest stable versions of the rDCM Toolbox on GitHub as part of the 
  [TAPAS software releases of the TNU](https://github.com/translationalneuromodeling/tapas/releases).
- Older versions of TAPAS are available on the [TNU website](http://www.translationalneuromodeling.org/tapas).
- The latest bugfixes can be found in the [GitHub Issue Forum](https://github.com/translationalneuromodeling/tapas/issues) or by request to the authors. 
- Changes between all versions will be documented in the 
  [CHANGELOG](https://tnurepository.ethz.ch/sfraessle/rDCM/blob/master/CHANGELOG.md).




Purpose
-------

The regression dynamic causal modeling (rDCM) toobox implements a novel variant 
of DCM for fMRI that enables extremely efficient inference on effective (i.e.,
directed) connectivity among brain regions (Frässle et al., 2017, 2018). Due to its
computational efficiency, inversion of large network models becomes feasible.

The accompanying technical paper about the toolbox concept and methodology 
can be found [here](http://dx.doi.org/10.1016/j.neuroimage.2017.02.090).



Installation
------------

### Matlab ###
1. Unzip the TAPAS archive in your folder of choice
2. Open Matlab
3. Add the rDCM Toolbox to your Matlab path



Important Note
----------

Please note that rDCM is a method that is still in it's infancy and thus subject to 
various limiations. Due to these limitations, requirements of rDCM in terms of 
fMRI data quality (i.e., fast TR, high SNR) are relatively high. For data that does not
meet these conditions, the method might not give reliable results. Please refer to the 
main toolbox references for a more detailed picture.



Contact/Support
---------------

We are very happy to provide support on how to use the rDCM Toolbox. However, 
due to time constraints, we might not provide a detailed answer to your request, 
but just some general pointers and templates. Before you contact us, please try the following:

1. First, look at the [FAQ](https://tnurepository.ethz.ch/sfraessle/rDCM/wikis/FAQ) 
   (which is frequently extended) for answers to your questions.
2. For new requests, we would like to ask you to submit them as 
   [issues](https://github.com/translationalneuromodeling/tapas/issues) on our github release page for TAPAS.



References
----------

### Main Toolbox References ###
1. Frässle, S., Lomakina, E.I., Razi, A., Friston, K.J., Buhmann, J.M., Stephan, K.E., 2017. Regression DCM for fMRI. NeuroImage 155, 406–421. doi:10.1016/j.neuroimage.2017.02.090
2. Frässle, S., Lomakina, E.I., Kasper, L., Manjaly Z.M., Leff, A., Pruessmann, K.P., Buhmann, J.M., Stephan, K.E., 2018. A generative model of whole-brain effective connectivity. NeuroImage 179, 505-529. doi:10.1016/j.neuroimage.2018.05.058



Copying/License
---------------

The rDCM Toolbox is free software: you can redistribute it and/or
modify it under the terms of the GNU General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program (see the file [LICENSE](LICENSE)).  If not, see
<http://www.gnu.org/licenses/>.
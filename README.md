# ANN-model-for-CPS
An artificial neural network model for the central plasma sheet electron fluexes: A THEMIS survey.
The current project is to construct an An artificial neural network model of the electron number flux model in the Earth's central plasma sheet region.
The manuscript or paper has sunbmited to Journal of Geophysical Research: Space Physics.

The 24 ANN models for electron energies from 0.06 kev to 293 keV, which are constructed from the THEMIS based electron data, are saved as '.h5' files as below. 
## Files List:
    File Name                    Related Energy channel (# keV)
    modelCPS_ESA_1.h5                     0.06
    modelCPS_ESA_2.h5                     0.10
    modelCPS_ESA_3.h5                     0.17
    modelCPS_ESA_4.h5                     0.30
    modelCPS_ESA_5.h5                     0.50
    modelCPS_ESA_6.h5                     0.87
    modelCPS_ESA_7.h5                     1.50
    modelCPS_ESA_8.h5                     2.60
    modelCPS_ESA_9.h5                     4.50
    modelCPS_ESA_10.h5                    7.70
    modelCPS_ESA_11.h5                    13.6
    modelCPS_ESA_12.h5                    23.6
    modelCPS_SST_1.h5                     27
    modelCPS_SST_2.h5                     28
    modelCPS_SST_3.h5                     29
    modelCPS_SST_4.h5                     30
    modelCPS_SST_5.h5                     31
    modelCPS_SST_6.h5                     41
    modelCPS_SST_7.h5                     52
    modelCPS_SST_8.h5                     66
    modelCPS_SST_9.h5                     93
    modelCPS_SST_10.h5                    129    
    modelCPS_SST_11.h5                    200
    modelCPS_SST_12.h5                    293
##  These models can be loaded by the function 'model.load()' in Python.
    

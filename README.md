# ANN-model-for-CPS
An artificial neural network model for the central plasma sheet electron fluexes: A THEMIS survey.
The current project is to construct an An artificial neural network model of the electron number flux model in the Earth's central plasma sheet region.
The manuscript or paper has sunbmited to Journal of Geophysical Research: Space Physics.

The 24 ANN models for electron energies from 0.06 kev to 293 keV, which are constructed from the THEMIS based electron data, are saved as '.h5' files as below. 
## Files List:
    File Name                         Related Energy channel (# keV)
    modelCPS_ESA_1_Layer_3.h5                     0.06
    modelCPS_ESA_2_Layer_3.h5                     0.10
    modelCPS_ESA_3_Layer_3.h5                     0.17
    modelCPS_ESA_4_Layer_3.h5                     0.30
    modelCPS_ESA_5_Layer_3.h5                     0.50
    modelCPS_ESA_6_Layer_3.h5                     0.87
    modelCPS_ESA_7_Layer_3.h5                     1.50
    modelCPS_ESA_8_Layer_3.h5                     2.60
    modelCPS_ESA_9_Layer_3.h5                     4.50
    modelCPS_ESA_10_Layer_3.h5                    7.70
    modelCPS_ESA_11_Layer_3.h5                    13.6
    modelCPS_ESA_12_Layer_3.h5                    23.6
    modelCPS_SST_1_Layer_3.h5                     27
    modelCPS_SST_2_Layer_3.h5                     28
    modelCPS_SST_3_Layer_3.h5                     29
    modelCPS_SST_4_Layer_3.h5                     30
    modelCPS_SST_5_Layer_3.h5                     31
    modelCPS_SST_6_Layer_3.h5                     41
    modelCPS_SST_7_Layer_3.h5                     52
    modelCPS_SST_8_Layer_3.h5                     66
    modelCPS_SST_9_Layer_3.h5                     93
    modelCPS_SST_10_Layer_3.h5                    129    
    modelCPS_SST_11_Layer_3.h5                    200
    modelCPS_SST_12_Layer_3.h5                    293
##  These models can be loaded by the function 'model.load()' in Python.
    

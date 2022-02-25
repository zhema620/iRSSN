# iRSSN
A package providing MATLAB programmed tools for individualized Radiomics-based structural similarity network
---------------------------------------------------------------------------------------
REFERENCES:
[1] Vallières, M. et al. (2015). A radiomics model from joint FDG-PET and 
    MRI texture features for the prediction of lung metastases in soft-tissue 
    sarcomas of the extremities. Physics in Medicine and Biology, 60(14), 
    5471-5496. doi:10.1088/0031-9155/60/14/5471
---------------------------------------------------------------------------------------
This package contains 3 folders:

1. 'Textures': MATLAB codes to perform texture analysis from the input 
    region of interest (ROI). This toolbox is self-contained and can be used on its 
    own outside of the radiomics package.Please see ref. [1] for more details.


2. 'SubFunction': MATLAB codes to sort input data and calculate individualized 
structural matrix using texture features.


3. 'Example': Prepared data and folders for users to test

***************************************************************************
ACKNOWLEDGEMENTS: 'texture' code
Vallières's TextureToolbox: <https://github.com/mvallieres/radiomics/>
***************************************************************************

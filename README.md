# iRSSN
A MATLAB package for iRSSN (individualized Radiomics-based structural similarity network)
---------------------------------------------------------------------------------------
The code is written by Zhe Ma, Bin Jing and ZhuQing Long, both from Capital Medical University.
If you have any question or find any bug in the code, please don't hesitate to contact 
mz0520@ccmu.edu.cn, jiingbin@sina.com or longzhuqing16@sina.com
---------------------------------------------------------------------------------------

This package contains 3 folders:

1. 'Textures': include MATLAB functions to perform texture analysis for
    region of interest (ROI) on the image. Please see ref. [1] for more details about these features.
2. 'SubFunction': include MATLAB codes for data sorting and iRSSN calculation.
3. 'Example': an example dataset for users to test the toolbox.
     
A brief instruction for the 'Example' data:
step 1. run the main function named 'iRSSN.m' in the package folder；
step 2. in the prompted window,  you should select the normalized gray matter files generated 
by VBM (CAT 12 software) in the step; for the 'Example'  data, you should select the files in
 'images' folder;
step 3. in the newly prompted window, you should choose the atlas file in the standard space, 
for the 'Example' data, you should choose the file in 'atlas' folder; 
step 4. in the newly prompted window, you should select an empty folder in your disk in order to 
save the sorted data. Here, the sorted data are used for the convenience in calculating texture features;
step 5. in the newly prompted window, you should select an empty folder in your disk to save the 
iRSSN matrix for every subject.

After that, wait for the ending of the code, and iRSSN could be found in the folder (selected in step 5).

***************************************************************************
ACKNOWLEDGEMENTS: 'texture' toolbox
Vallières's TextureToolbox: <https://github.com/mvallieres/radiomics/>

REFERENCES:
[1] Vallières, M. et al. (2015). A radiomics model from joint FDG-PET and 
    MRI texture features for the prediction of lung metastases in soft-tissue 
    sarcomas of the extremities. Physics in Medicine and Biology, 60(14), 
    5471-5496. doi:10.1088/0031-9155/60/14/5471
***************************************************************************

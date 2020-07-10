======
fiberf
======


The purpose of this project is the first Python and Jupyter Notebook based implementation of the Nance Lab's FIBER (Frameworks for neuroImage Based Experimental Routines) pipeline. 


Description
===========

FIBERf is an implementation of a pipeline used for (Joseph, A. and Liao, R., et al. Bioengineering and Translation Medicine. 2020. (in press)). This pipeline originally was not Jupyter Notebook based but used GUIs of Cell Profiler and VAMPIRE. This specific version of FIBER is designed for immunohistochemistry stains of the ferret brain with neonatology at the University of Washington Medical Center.  

FIBERf is currently a singular Jupyter notebook that comprises:

1. Uploading images through Google Drive
2. Thresholding and segmenting immunohistochemistry images of cells
3. Analyzing cell shapes to get insight into their morphology
4. Current Build out: Utilizing the VAMPIRE package (from Denis Wirtz lab at Johns Hopkins University)to classify cells into representative images
5. Current Build Out: Built in data analysis of the phenotypic spreads of cells and distribution of cell shape features across experimental groups

Future Features:
1. Built in data visualization
2. Built in image visualization and annotation within notebook
3. Additional cell features built in
4. Integration with our package ifthresholds a component of our package ifmodels (https://github.com/Nance-Lab/ifmodels) that allows for better thresholding of cells in tissue
5. Integration with IRkernel in Jupyter Notebook for ability to use R in Jupyter Notebook for collaborators without Python background or with R preference

Next Steps:
1. Move from a singular Jupyter notebook to a package based system
2. Test Driven-Design
3. Beginning FIBERp for immunofluorescent images from piglets
4. Beginning FIBER a non-experiment specific cell morphology pipeline user friendly for labs studying cells in tissue.

Note
====

This project has been set up using PyScaffold 3.2.3. For details and usage
information on PyScaffold see https://pyscaffold.org/.

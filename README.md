# Code used to analyze human inferior temporal gyrus data with tau (AT8), neuron (HUD), and nuclei (DAPI) staining

For the manuscript: "Spatial characterization of tangle-bearing neurons and ghost tangles in the human inferior temporal gyrus with three-dimensional imaging" by Zwang et al, Brain Communications 2023

To run code in matlab, first prepare all the relevant files including:
1) Output of each channel from ilastik object classification as an H5 file, using the "object identities" selection and table in CSV format
2) Brain region segmentation with layer IDs output from Imaris and converted to tif with ImageJ.
3) Run the pixelsearchoverlap code first, then run analysis of cells by layer

Note that the files are large and the code required a computer with 128gb RAM to run in its current form.

You can find these raw data, including the output files necessary to run the code on BioImage Archive: https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD676

Saveastiff function can be accessed here: https://www.mathworks.com/matlabcentral/fileexchange/35684-multipage-tiff-stack

Zwang LMER contain the R code used to run the linear mixed effects model

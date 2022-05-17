# PhD_Digital_Appendix_1.1_ENMeval_metrics
Digital appendix materials from my PhD Thesis at the University of Otago

This repository is the first digital appendix created to suplement my PhD thesis "Resources to Aid Decision-Making in Conservation Translocations" submitted to the University of Otago in November 2021.

As these digital appendices are not intended to be stand alone, I intend to upload a pdf file of my thesis once it is accepted and finalised to provide further context for the repository content.

This first appendix provides further details of the correlative habitat suitability model replicates that were averaged to generate the models presented in Chapter 4 of my thesis "Predictive Modelling: Relict Distribution Habitat Models".

The repository is split into two folders, containing replicates of conservative and extrapolative model replicates respectively (more details of the concepts behind these model categories are presented in the paper linked here: https://www.frontiersin.org/articles/10.3389/fcosc.2021.691714/full, with further methodological details contianed in the suplementary materials of this paper). A text-file is also included that provides details and guides interpretation of the .tiff figures contained within these folders.

The conservative model and extrapolative model folders each contain a .csv file containing the settings and output metrics of the 600 replicates that were run prior to identification of optimal models and model averaging that were conducted as part of the anlayses in my thesis. These tables are outputs from the ENMeval package in R (Muscarella R, Galante PJ, Soley-Guardia M, Boria RA, Kass JM, Uriarte M, Anderson RP 2014. ENMeval: An R package for conducting spatially independent evaluations and estimating optimal model complexity for Maxent ecological niche models. Methods in Ecology and Evolution 5(11): 1198–1205.), while details of model inputs and settings are contianed within thesuplementary materials of the Fronteirs paper linked above.

Following this the folders contain a serries of .tiff files presenting evaluation plots created by the ENMeval package. Each plot relates to an individual run of the ENMeval model fitting process, of which 40 iterations were run as part of my modelling process. The appended number in each file name refers to the specific ENMeval run that the evaluation plots present data from, 1-40.

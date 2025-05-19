Hurton et al, PLoS Biology 2025

Readme for R analysis scripts
------------------
R/pca/pca_dome_stage.R.txt
R/pca_timecourse.R.txt
R/rna/enh_rnaseq.R.txt
R/kinetics/kinetics.R.txt
R/misc/misc_figs.R.txt

These scripts were written using R v4.1.0 on macOS using the following libraries
gplots
e1071
MASS
viridis


Each script can be run by starting in each directory and in R running, e.g.

> source('pca_dome_stage.R.txt')

This will produce various output files and raw figures in the output subdirectory. There are some dependencies on output files from one analysis that are needed for a subsequent one -- the output directories as provided are already populated with the results of all the analyses, so any one of the scripts can be re-run with no issues. Alternatively, if the scripts are run in the order listed, then there should be no issues even if some output files are initially missing.

Input data files from non-R analyses are located in the data subdirectories. Some public datasets are also used (stored in the public_data directory at root level)
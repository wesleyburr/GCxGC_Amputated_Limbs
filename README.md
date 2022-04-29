# GCxGC Project on Amputated Limbs

The files in this repository are the work done to take initial outputs from
a set of GCxGC scans of headspaces from decomposition targets (human feet),
looking for relevant VOCs in the scans.

There are five main files, which:

* 1: load and process the Excel sheets into .rda objects
* 2: load the .rda objects, and normalize with respect to Bromobenze, the reference standard
* 3: select, filter, clean and merge compounds using logic as described in the paper (export to .xlsx in the dat_comp directory)
* 4: repeat step 3, but relative to the normalized inputs (as per 2)
* 5: re-do the work of steps 3 and 4, but specifically set up to export to files which are suitable for PCA using the original software of the GCxGC system

Downloading this repository and starting from the file 1_Load_Review.Rmd, if each Rmd is run in turn, they should run
correctly. Do note that there is a dependency on each subsequent number on some of the previous numbers. 

# Rockfish Species ID via microhaplotyping
 
Primary Contacts: Anita Wray,
[anita.wray\@noaa.gov](mailto:anita.wray@noaa.gov)

## Objective:
This project achieved two objectives:
1. Find a sequencing panel to successfully ID rougheye from blackspotted rockfish
2. Test additional cryptic species complexes on existing sequencing panels
This repo doesn't include the other panels tested, but we were able to conclude that Diana's GTseq microhaplotyping panel works well. 

## Methods:

#### 1. Run snakemake to call microhaplotypes

Use Eric Anderson's snakemake to call microhaplotypes. See README within the SNAKEMAKE folder for more information

#### 2. Update reference with vouchers

Use Rubias to test if known vouchered specimens can be identified to species using this panel


#### 3. Run unknown samples

Use Rubias to ID unknown samples (primarily rougheye/blackspotted, but see below for all the species that are in this panel). 
!(https://github.com/anitawray-NOAA/microhaplotyping_speciesID/blob/main/Screenshot%202025-07-03%20at%2012.41.58%20PM.png)

Also run a PCA (see below)
!(https://github.com/anitawray-NOAA/microhaplotyping_speciesID/blob/main/Screenshot%202025-07-03%20at%2012.45.40%20PM.png)

## Disclaimer:

This repository is a scientific product and is not official
communication of the National Oceanic and Atmospheric Administration, or
the United States Department of Commerce. All NOAA GitHub project code
is provided on an 'as is' basis and the user assumes responsibility for
its use. Any claims against the Department of Commerce or Department of
Commerce bureaus stemming from the use of this GitHub project will be
governed by all applicable Federal law. Any reference to specific
commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce.
The Department of Commerce seal and logo, or the seal and logo of a DOC
bureau, shall not be used in any manner to imply endorsement of any
commercial product or activity by DOC or the United States Government.
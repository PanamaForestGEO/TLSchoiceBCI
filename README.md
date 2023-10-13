# TLSchoiceBCI
Code and associated data files to choose where within the BCI 50-ha plot to put three 1-ha plots for collection of terrestrial laser scanning (TLS) data GEOTREES

This code was written by Helene Muller-Landau and Camille Piponiot.  

**whereTLSonBCI_part3.pdf**  This is the file that will be of most general interest - a pdf version of the output of whereTLSonBCI_part3.Rmd, which contains the analyses and figures evaluating potential TLS plot locations on the BCI 50-ha plot. 

**whereTLSonBCI_part1a.Rmd**  Downloads the BCI 50-ha tree census data from the online repository and unzips it.  

**whereTLSonBCI_part1b.Rmd**  Calculate quadrat-level canopy height statistics for the BCI 50-ha plot, and saves these to "usedata/canht2023q20.txt" and "usedata/canht2023p5.txt".  Based on May 2023 airborne lidar data.  

**whereTLSonBCI_part2.Rmd**  Calculate quadrat-level tree census stats for the BCI 50-ha plot, and save these to "usedata/cachequad.rda" and "usedata/cachecrown.rda".

**whereTLSonBCI_part3.Rmd**  Make figures relevant for choosing where to locate the 1-ha plots for TLS data collection.  

**usedata** Contains data and data products used here.  

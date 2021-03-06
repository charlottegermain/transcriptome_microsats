# transcriptome_microsats
Scripts used in evaluating microsatellite loci developed from transcriptomes

##Overview

These scripts were used to process the output of the microsatellite finding program MISA ([Dieringer and Schlötterer, 2003](http://onlinelibrary.wiley.com/doi/10.1046/j.1471-8286.2003.00351.x/abstract)). MISA was run on the transcriptome datasets from the [1,000 Plant Transcriptome Project](http://onekp.com) and the results summarized with these and previously released scripts. 

What follows is a brief description of the scripts available here.

##Scripts and their functions:

###LocateSSRsandORFs.py
A script to compare the location of an SSR and the longest ORF in a given scaffold.
Note that for the project, ORFs were identified using [get_orfs_or_cdss.py](https://github.com/peterjc/pico_galaxy/blob/master/tools/get_orfs_or_cdss/).

###getScaffolds.py
A script to pull sequences from a fasta file based on a list and write to a new file.


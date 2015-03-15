
> Timestamp: 03-15-2015 Yanxiao Zhang troublezhang@gmail.com
============================================================

###INTRODUCTION
PePr is a ChIP-Seq Peak-calling and Prioritization pipeline 
that uses a sliding window approach and models read counts across 
replicates and between groups with a negative binomial distribution. 
PePr empirically estimates the optimal shift/fragment size and 
sliding window width, and estimates dispersion from the local genomic
area. Regions with less variability across replicates are ranked more
favorably than regions with greater variability. Optional 
post-processing steps are also made available to filter out peaks
not exhibiting the expected shift size and/or to narrow the width of peaks.

###LINKS

https://github.com/troublezhang/PePr/ # Source code
https://ones.ccmb.med.umich.edu/wiki/PePr/ # Manual
https://pypi.python.org/pypi/pepr #PyPI package index


###INSTALL & USAGE
Please visit our wiki page(https://ones.ccmb.med.umich.edu/wiki/PePr/) for instructions. 

###CITATION
Zhang Y, Lin YH, Johnson TD, Rozek LS, Sartor MA. PePr: A peak-calling prioritization pipeline to identify consistent or differential peaks from replicated ChIP-Seq data. Bioinformatics. 2014.

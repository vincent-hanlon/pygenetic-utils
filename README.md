## Introduction

This a set of miscellaneous functions I've written in python to process sequence aligned sequence reads or genomic coordinates. They are pretty bare-bones but I hope to make them nicer to use someday.

So far there are three notebooks, corresponding to three tasks:

* Calculating the mean Phred base quality of aligned reads, and removing reads below some threshold. Useful for nanopore data.
* Extracting the genomic coordinates of aligned gaps from CIGAR strings
* Merging overlapping genomic intervals in two ways: either combinining intervals with the same left coordinates, or combining intervals whose start and end coordinates are with 10% of each other (which is a little dangerous)

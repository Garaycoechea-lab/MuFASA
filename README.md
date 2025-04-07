# StReSSMAn
Short read sequencing Somatic Mutation Analysis and Filtering

# Installation Guide

## Nextflow & Conda
Make sure you have [nextflow](https://www.nextflow.io/docs/latest/index.html) available. 
This pipeline is optimized to be run on a cluster with scheduling software like SLURM available.

The Nextflow pipeline primarily uses conda environments. To install the proper tools and dependencies, use the conda env requirements (.yml) files. All Tools and Packages used in the nextflow workflow are specified in these files. 

## configuration



## FASTQ processing
All paired-end reads are assesed on read quality and multiple sequencing runs are merged before trimming 
[cutadapt](https://cutadapt.readthedocs.io/en/stable/) is used to find and remove adapter sequences, primers and poly-A tails. 

## MAPPING processing
All reads are mapped against 

### BWA-mem

## Variant Calling

## Variant Filtering

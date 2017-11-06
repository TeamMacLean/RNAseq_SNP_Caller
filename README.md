## Introduction

Rake pipeline for SNP calling from RNA seq data

## Requirements

1) ruby/rake
2) FASTQC
3) Trimmomatic
4) tophat
5) samtools
6) bcftools

## Usage:

1) rake R1=path/to/R1.fastq R2=path/to/R2.fastq sampleid=mysampleid samplename=mysample reference=path/to/reference.fasta

MIM: Maximal Inexact Matches
===

<b>Description</b>: Given two genomes r and q, and a reference and query gene, MIM finds CNEs matches between the
gene positions of the respective chromosomes of r and q.

<b>Installation</b>: To compile MIM, please follow the instructions given in file INSTALL.
```
 MIM <options>
 Standard (Mandatory):
   -r, --ref-genome-file	<str>		FASTA reference genome filename.
   -q, --query-genome-file	<str>		FASTA query genome filename.
   -e, --exons-ref-file		<str>		GTF/GFF exon coordinates for reference genome filename.
   -f, --exons-query-file	<str>		GTF/GFF exon coordinates for query genome filename.
   -g, --ref-gene-file		<str>		GTF/GFF filename containing gene data for reference genome.
   -n, --ref-gene-name		<str>		Name of gene in reference genome in which CNEs will be identified.
   -j, --query-gene-file	<str>		GTF/GFF filename containing gene data for query genome.
   -m, --query-gene-name	<str>		Name of gene in query genome in which CNEs will be identified.
   -l, --min-seq-length		<int>		Minimum length of CNEs.
   -k, --sim-threshold		<dbl>		Threshold of similarity between sequences.
   -o, --output-file		<str>		Output filename with CNEs identified.
 Optional:
   -v, --rev-complement		<int>		Choose 1 to compute reverse complement matches or 0 otherwise. Default: 0.
   -x, --remove-overlaps	<int>		Choose 1 to remove overlapping CNEs or 0 otherwise. Default: 1.
 Number of threads: 
   -T, --threads		<int>		Number of threads to use. Default: 1.
```

<b>License</b>: GNU GPLv3 License; Copyright (C) 2017 Lorraine A. K. Ayad, Solon P. Pissis, Dimitris Polychronopoulos


# xdp_sva
Our study investigated the presence of regional differences in hexanucleotide repeat number in post-mortem brain tissues of two patients with X-linked dystonia-parkinsonism (XDP), a combined dystonia-parkinsonism syndrome modified by a (CCCTCT)n repeat within the causal SINE-VNTR-Alu (SVA) retrotransposon insertion in the TAF1 gene. 
Genomic DNA was extracted from blood and post-mortem brain samples, including the basal ganglia and cortex from both patients and from the cerebellum, midbrain,
and pituitary gland from one patient and repeat sizing was performed using fragment analysis, small-pool PCR-based Southern blotting, and Oxford nanopore sequencing.
This is an upload of the bash script and FASTA for data analysis of repeat expansions in the SVA on the TAF1 gene.

Usage of the script:
sbatch repeatlengthdet.sh <Name of your .zip file containing FASTQ files> <Enrichment method: CRISPR/PCR>

Usage example:
sbatch repeatlengthdet.sh Nanopore_Data CRISPR

In addition, you can download the Oxford Nanopore sequencing data described here: https://doi.org/10.1093/pnasnexus/pgae116 via this link: https://drive.google.com/file/d/1NKq9zAy21KSY0JzxUZkQTYxMXaz4aunb/view?usp=drive_link.

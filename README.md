# Overview
This repository contains the supplementary materials associated with my MSci Research Project Thesis.  
It includes the final dataset used, the relevant risk assessment, and the HPC scripts used throughout the project.

---

# Contents

## 1. Risk Assessment
**RISK ASSESSMENT KATIE MAGILL_signed.docx**  
A copy of the signed risk assessment submitted as part of the project requirements.

---

## 2. Genome Dataset
**LIST OF GENOMES USED.xlsx**  
An Excel file containing all genomes used in the pangenome analysis, including associated metadata.

---

## 3. HPC / SLURM Job Scripts
The following HPC job scripts were used throughout the project.  
Each script corresponds to a specific analysis step.

- **ABRICATE_ANNOTATION**  
  Runs Abricate to screen genomes for virulence genes.

- **AMRFINDERPLUS_ANNOTATION**  
  Uses AMRFinderPlus to identify AMR genes.

- **BAKTA_ANNOTATION**  
  Performs genome annotation using Bakta.

- **COINFINDER_ANALYSIS**  
  Runs COINfinder to detect gene–gene associations within the pangenome.

- **EGGNOG_ANNOTATION**  
  Runs eggNOG‑mapper to assign functional categories and gene annotations.

- **GENOME_DOWNLOAD**  
  Downloads all genomes used in the project from BVBRC.

- **ORFORISE_CONVERT_TO_GFF**  
  Converts annotation TSVs into GFF format for downstream analyses.

- **ORFORISE_GFFADDER**  
  Combines ORForise‑generated GFF annotations with bakta annotation GFF.

- **OUTLIER_DETECTION**  
  Runs statistical outlier detection.

- **PANGENOME_ANALYSIS**  
  Constructs a pangenome in Pyamilyseq

- **SOURMASH_SKETCH_COMPARE**  
  Generates Sourmash sketches and performs genome similarity comparisons.

These scripts are included for transparency and reproducibility.  


# PaLCuV Genomics — MSc (Hons) Research

This repository contains the data workflows and bioinformatics analysis performed during my MSc (Hons) Plant Pathology research on Papaya Leaf Curl Virus (PaLCuV).

## Project Overview

Papaya Leaf Curl Virus (PaLCuV) is a begomovirus (family *Geminiviridae*) that causes significant yield losses in papaya production in Pakistan. Despite its prevalence, comprehensive molecular data on the genetic diversity of local isolates remains limited. This study focuses on the molecular characterization of PaLCuV field isolates from Punjab, Pakistan, targeting the Coat Protein (CP) gene, with the aim of identifying isolate diversity and assessing evolutionary relationships with known begomovirus species.

## Objectives

- Molecular detection of PaLCuV using PCR targeting the CP gene
- Sequence-based identification and comparison with global isolates via BLASTn
- Phylogenetic analysis to determine evolutionary relationships
- Recombination analysis using RDP4

## Methods

### Wet Lab

- Sample collection from papaya-growing regions of Punjab, Pakistan
- Genomic DNA extraction using the CTAB method, optimized for recalcitrant plant tissue
- PCR using self-designed primers targeting the conserved AV1/Coat Protein (CP) region (~550 bp)
- Sanger sequencing of PCR amplicons

### Bioinformatics Pipeline

- BLASTn searches against the NCBI database for homology and pairwise identity assessment
- Multiple sequence alignment — ClustalW via BioEdit
- Phylogenetic tree construction — MEGA X (Neighbor-Joining and Maximum Likelihood methods, bootstrap 1000)
- Recombination detection — RDP4
- Open Reading Frame (ORF) identification — NCBI ORF Finder

## Tools Used

| Tool | Purpose |
|------|---------|
| BioEdit | Sequence editing and alignment (ClustalW) |
| MEGA X | Phylogenetic analysis (NJ & ML trees) |
| RDP4 | Recombination detection |
| BLAST/NCBI | Homology search and identity assessment |
| NCBI ORF Finder | Open Reading Frame identification |
| Python | Sequence data handling and automation scripts |

## Repository Structure

```
/data      — raw and processed sequences (.fasta files)
/scripts   — Python scripts for automation
/results   — phylogenetic trees, alignment files
/figures   — output images
```

## Status

MSc (Hons) thesis research in progress — University of Agriculture, Faisalabad. Sequencing and initial BLASTn screening of field isolates is complete; comparative phylogenetic and recombination analysis is ongoing.

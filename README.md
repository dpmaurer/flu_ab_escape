# Influenza virus escape from imprinted antibody lineages and pan-H1 antibodies

Please note that we used large pieces of code from Jesse Bloom's lab at repositories found [here](https://github.com/jbloomlab/SARS-CoV-2-RBD_DMS_variants) and [here](https://github.com/dms-vep/dms-vep-pipeline) as well as dms_tools2 and dms_variants found [here](https://jbloomlab.github.io/dms_tools2/) and [here](https://jbloomlab.github.io/dms_variants). I highly recommend referring to these repositories and documentation for more detailed descriptions of the code.

In these studies, we used imprinted antibody lineages and pan-H1 anti-influenza antibodies to select for viral escape using DMS libraries covering the influenza HA head in multiple strains. For imprinted antibody lineages, we used both the inferred unmuated common ancestor (UCA) and mature antibodies. Here, we provide the library designs, Jupyter notebooks used for sequencing analyses, outputs used in generating figures for publication.

Raw sequencing data from the imprinted antibody selections and fitness selections of USSR77, SN89, and SI06 viral libraries can be downloaded from BioProject PRJNA1056469.

# Directories:

## library_designs
This directory holds annotated library HA sequences:

USSR77 - annotated viral HA segment for the USSR77 HA library cloned into pDM_RevGen068 (modified pHW2000)

SN89 - annotated viral HA segment for the SN89 HA library cloned into pDM_RevGen068 (modified pHW2000)

SI06 - annotated viral HA segment for the SI06 HA library cloned into pDM_RevGen068 (modified pHW2000)

SYD21 - annotated viral HA segment for the SYD21 HA library cloned into pDM_RevGen068 (modified pHW2000)

## pacbio_analysis
This directory holds the code for the analysis of the pacbio sequencing and the resulting codon and nucleotide variant tables.

## fitness_selections
This directory holds the analysis of sequencing after a low MOI passage of the viral libraries.

## antibody_selections
This directory holds the analysis of the sequencing results after infecting cells with the viral libraries in the presence of 10X the IC99 of each antibody.



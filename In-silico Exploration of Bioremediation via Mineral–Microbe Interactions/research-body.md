**Research Body**

**1. Background**

Petroleum pollution is a pressing global issue affecting soil, water, and public health. Traditional remediation methods are often energy-intensive and ecologically disruptive. Bioremediation—particularly the use of indigenous microbes in coordination with minerals—offers a sustainable alternative.

This project explores how specific microbial genes enable the breakdown of petroleum hydrocarbons and how minerals (e.g., iron oxides, clays) enhance microbial degradation efficiency. We approach the problem entirely in-silico using genome, gene, and pathway databases.

**2. Data Sourcing**

Sources of gene and protein data include:

Gene sequences from supplementary materials of French et al. (2020) — e.g., alkB, camA–camD, xylE, almA.

Public repositories: NCBI GenBank, ENA, UniProt, KEGG, MetaCyc.

Literature-derived sequences of biosurfactant-producing genes and hydrocarbon-catabolic operons.

Environmental metagenomes from petroleum-contaminated sites via MG-RAST and IMG/M.

Optional: Metadata on pH, redox, and microbial taxa from Shell Pond and similar case studies.

**3. Research Design & Methodology**

**A. Gene Mining**

Curate FASTA sequences of known hydrocarbon-degrading genes.

Perform BLAST and HMMER searches across metagenomic samples.

Annotate genes using Biopython + Entrez and UniProt APIs.

**B. Pathway Mapping**

Use KEGG and MetaCyc to reconstruct pathways for alkane, aromatic hydrocarbon, and PAH degradation.

Map gene products (e.g., monooxygenases, dioxygenases, cytochrome P450s) to specific reactions.

**C. Mineral–Microbe Modeling**

Identify microbial species known to interact with minerals (e.g., Pseudomonas, Cupriavidus).

Model how minerals serve as electron acceptors or surfaces enhancing enzymatic activity.

Integrate soil abiotic parameters (pH, moisture, redox) into microbial pathway simulations.

**D. Bioinformatics Tools**

QIIME2 for metagenomic taxonomic profiling.

BLAST and Biopython for sequence alignment and parsing.

Cytoscape and COBRApy for network and flux analysis.

**E. Visualization & Reporting**

Use Python (matplotlib/seaborn) and R for data plotting.

Final results include heatmaps of gene presence, reconstructed metabolic maps, and system models of microbial–mineral interactions.

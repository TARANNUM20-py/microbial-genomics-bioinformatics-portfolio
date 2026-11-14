# Antimicrobial Resistance Analysis

## Project: Pseudomonas aeruginosa PAO1

### Objective
Identify antimicrobial resistance-associated genes in the
Pseudomonas aeruginosa PAO1 reference genome.

### Reference genome
- Organism: Pseudomonas aeruginosa PAO1
- NCBI Assembly: GCF_000006765.1

### Tools
- Ubuntu Linux
- AMRFinderPlus 4.2.7
- AMRFinder database 2026-10-29.1

### Command used

amrfinder -n Pseudomonas.fasta -O Pseudomonas_aeruginosa -o Pseudomonas_AMR_results.tsv

### Results
Five AMR-associated gene hits were reported:
- catB7
- fosA
- blaPDC-1
- aph(3')-IIb
- blaOXA-50

### Interpretation
The detected sequences showed 100% reference coverage
and 100% identity in this analysis.

These genomic findings do not independently establish
phenotypic or clinical antimicrobial resistance.
Phenotypic antimicrobial susceptibility testing is
needed for complementary interpretation.

### Learning outcomes
- Downloading and locating a bacterial reference genome
- Running AMRFinderPlus
- Understanding AMR output fields
- Interpreting gene identity and reference coverage

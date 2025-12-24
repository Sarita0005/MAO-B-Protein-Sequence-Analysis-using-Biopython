# MAO-B-Protein-Sequence-Analysis-using-Biopython


## Overview
This project demonstrates a basic bioinformatics workflow using Biopython to analyze the protein sequence of Monoamine Oxidase B (MAO-B), an enzyme involved in dopamine metabolism and relevant to Parkinson’s disease.

The analysis focuses on sequence parsing, CDS extraction, protein translation, and basic protein characterization.

---

## Objectives
- Parse GenBank and FASTA files using Biopython
- Extract the protein-coding sequence (CDS)
- Translate nucleotide sequence into protein
- Analyze amino acid composition
- Calculate basic physicochemical properties
- Visualize hydrophobicity using Kyte–Doolittle plot

---

## Data Source
- MAO-B gene (Homo sapiens)
- Downloaded from NCBI in GenBank format

---

## Workflow
1. Read GenBank file and inspect genomic features
2. Extract CDS feature corresponding to MAO-B
3. Translate CDS into protein sequence
4. Save protein sequence in FASTA format
5. Compute amino acid counts and percentages
6. Plot amino acid composition
7. Generate Kyte–Doolittle hydrophobicity plot

---

## Tools & Libraries
- Python
- Biopython
- Pandas
- Matplotlib

---

## Key Results
- Protein length: 520 amino acids
- Molecular weight: ~58.7 kDa
- Isoelectric point (pI): ~7.2
- Mixed hydrophobic and hydrophilic regions consistent with enzymatic proteins

---

## Biological Relevance
MAO-B plays a key role in dopamine metabolism. Understanding its protein sequence properties helps in studying enzyme behavior and provides a foundation for further drug discovery or structural analysis.

---

## Skills Demonstrated
- Sequence parsing and annotation handling
- CDS extraction and translation
- Protein sequence analysis
- Data visualization
- Reproducible bioinformatics workflow

---

## Author
Sarita_Duhan

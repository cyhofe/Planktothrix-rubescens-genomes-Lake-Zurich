# *Planktothrix rubescens* genomes from Lake Zurich

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22208404.svg)](https://doi.org/10.5281/zenodo.22208404)

This repository contains genome assemblies and Prokka annotation outputs for eight cultured *Planktothrix rubescens* isolates from Lake Zurich, Switzerland. These files accompany the peer-reviewed publication:

> Hofer C, Knapp D, Posch T, Andrei A-S, Pernthaler J. 2026. Hybrid sequencing recovers highly contiguous genome assemblies from eight cultured *Planktothrix rubescens* isolates from Lake Zurich. *Microbiology Resource Announcements*, e00820-26.  
> **Publication DOI:** https://doi.org/10.1128/mra.00820-26

The underlying genome assemblies and sequencing reads are available through the European Nucleotide Archive (ENA) under BioProject [PRJEB114346](https://www.ebi.ac.uk/ena/browser/view/PRJEB114346) / study accession [ERP194653](https://www.ebi.ac.uk/ena/browser/view/ERP194653).

## Important annotation note

The files in this repository were generated locally with Prokka v1.14.6 and underlie the CDS, rRNA, tRNA, and GC statistics reported in the publication. The annotations displayed for the corresponding assemblies in GenBank were generated separately by the NCBI Prokaryotic Genome Annotation Pipeline (PGAP). Consequently, individual feature predictions and counts may differ slightly between the Prokka and PGAP annotations.

## Strains

| Strain | ENA sample accession |
| --- | --- |
| ZS_A7 | ERS30397717 |
| ZS_3A4 | ERS30397710 |
| ZS_3C4 | ERS30397712 |
| ZS_4B4 | ERS30397713 |
| ZS_3C1 | ERS30397711 |
| ZS_5C5 | ERS30397715 |
| ZS_5C6 | ERS30397716 |
| ZS_4D3 | ERS30397714 |

## Repository structure

```text
Planktothrix_rubescens_ZS_A7.Chromosome.fna
Planktothrix_rubescens_ZS_A7.Chromosome.faa
Planktothrix_rubescens_ZS_A7.Chromosome.gbk
...
```

Three files are provided for each strain:

- `.fna`: Nucleotide genome assembly in FASTA format
- `.faa`: Predicted protein sequences in amino-acid FASTA format
- `.gbk`: GenBank-format genome annotation generated with Prokka

## Annotation method

Assemblies were annotated with Prokka v1.14.6, using Prodigal for protein-coding sequence prediction. Default parameters were used unless otherwise specified in the associated publication.

## Data integrity

The archived release on Zenodo represents the dataset associated with the published article. Subsequent changes to the GitHub repository are not part of that archived release unless a new version is deposited on Zenodo.

## Citation

If you use these genome assemblies or annotations, please cite both the associated publication and the archived dataset.

**Publication:**

> Hofer C, Knapp D, Posch T, Andrei A-S, Pernthaler J. 2026. Hybrid sequencing recovers highly contiguous genome assemblies from eight cultured *Planktothrix rubescens* isolates from Lake Zurich. *Microbiology Resource Announcements*, e00820-26.  
> https://doi.org/10.1128/mra.00820-26

**Archived dataset:**

> Hofer C, Knapp D, Posch T, Andrei A-S, Pernthaler J. *Planktothrix rubescens* genomes from Lake Zurich. Zenodo.  
> https://doi.org/10.5281/zenodo.22208404

## Contact

Cyrill Hofer  
Microbial Evogenomics Laboratory, University of Zurich  
Email: cyrill.hofer@uzh.ch

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

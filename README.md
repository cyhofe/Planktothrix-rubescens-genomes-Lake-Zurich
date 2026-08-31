# *Planktothrix rubescens* genomes from Lake Zurich

**Zenodo DOI:** pending

This repository contains genome assemblies and Prokka annotation outputs for eight cultured *Planktothrix rubescens* isolates from Lake Zurich. These files underlie the genome annotation statistics reported in:

> Hofer C, Knapp D, Posch T, Andrei A-S, Pernthaler J. *Hybrid sequencing recovers highly contiguous genome assemblies from eight cultured Planktothrix rubescens isolates from Lake Zurich.*

The underlying genome assemblies and sequencing reads are available through the European Nucleotide Archive (ENA) under BioProject [PRJEB114346](https://www.ebi.ac.uk/ena/browser/view/PRJEB114346) / study accession [ERP194653](https://www.ebi.ac.uk/ena/browser/view/ERP194653).

## Important annotation note

The files in this repository were generated locally with Prokka v1.14.6 and underlie the CDS, rRNA, tRNA and GC statistics reported in the manuscript. The annotations displayed for the corresponding assemblies in GenBank were generated separately by the NCBI Prokaryotic Genome Annotation Pipeline (PGAP). Consequently, individual feature predictions and counts may differ slightly between the Prokka and PGAP annotations.

## Strains

| Strain | ENA sample accession |
|---|---|
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

- `.fna`: input assembly sequence
- `.faa`: predicted protein sequences
- `.gbk`: GenBank-format Prokka annotation

## Annotation method

Assemblies were annotated with Prokka v1.14.6. Default parameters were used unless otherwise specified in the manuscript.

## Data integrity

The archived release on Zenodo is the version associated with the manuscript. Later changes to the GitHub repository are not part of that archived release unless a new version is deposited.

## Citation

Please cite both the manuscript and the archived dataset:

> Hofer C, Knapp D, Posch T, Andrei A-S, Pernthaler J. *Planktothrix rubescens* genomes from Lake Zurich. Zenodo. https://doi.org/DOI-PENDING

The DOI and complete manuscript citation will be added after the Zenodo record and article are finalized.

## Contact

Cyrill Hofer  
Microbial Evogenomics Laboratory, University of Zurich  
Email: cyrill.hofer@uzh.ch

## License

A reuse license must be selected before the first public release. CC BY 4.0 is recommended for these annotation data, subject to institutional requirements.

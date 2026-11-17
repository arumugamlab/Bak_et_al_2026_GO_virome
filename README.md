# Supplementary data for Bak et al. 2026 GO virome study

Processed virome and 16S rRNA gene amplicon data supporting the manuscript *Gut viral signatures are associated with metabolic phenotypes and weight-loss outcomes after Roux-en-Y gastric bypass*.

This repository contains processed data from fecal samples collected before and after bariatric surgery in the Governing Obesity cohort. Viral data were generated from viral-enriched shotgun metagenomes, and prokaryotic community profiles were generated from 16S rRNA gene amplicon sequencing.

## Available files

| File | Description | Format | Size |
| --- | --- | --- | --- |
| [`GO_viral_genomes.fasta.gz`](GO_viral_genomes.fasta.gz) | FASTA file containing the 3,013 viral genomes used for downstream analyses. These sequences were estimated to be >50% complete using CheckV. | Gzipped FASTA | 24 MB |
| [`GO_viral_sequences.fasta.gz`](GO_viral_sequences.fasta.gz) | FASTA file containing viral sequences detected in the current GO cohort after mapping study reads to the viral sequence catalogue. | Gzipped FASTA | 62 MB |
| [`viral_sequence_catalogue.fasta.gz`](viral_sequence_catalogue.fasta.gz) | Full viral sequence catalogue generated from viral-enriched fecal metagenomes from this study and additional Danish fecal viral metagenomes. | Gzipped FASTA | 67 MB |
| [`viral_sequence_catalogue_vContact3_taxonomy.csv.gz`](viral_sequence_catalogue_vContact3_taxonomy.csv.gz) | vContact3-based taxonomic annotation table for the viral sequence catalogue. | Gzipped CSV | 366 KB |
| [`virome_physeq.Rdata`](virome_physeq.Rdata) | R data object containing processed virome profiles for downstream ecological and statistical analyses. | RData | 456 KB |
| [`prokaryotes_physeq.Rdata`](prokaryotes_physeq.Rdata) | R data object containing processed 16S rRNA gene ASV profiles representing the prokaryotic microbiota. | RData | 158 KB |

## Suggested citation

Please cite the associated manuscript when using these data:

Bak et al. 2026. *Gut viral signatures are associated with metabolic phenotypes and weight-loss outcomes after Roux-en-Y gastric bypass*.

## Contact

For questions about these data, please contact the Arumugam Lab at the Novo Nordisk Foundation Center for Basic Metabolic Research, University of Copenhagen.

---

*Last updated: November 2026.*

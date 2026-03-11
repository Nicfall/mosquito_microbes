# mosquito_microbes

R scripts for the analyses in **Kriefall et al. (2024)** — *Abiotic factors shape mosquito microbiomes that enhance host development* — published in [*The ISME Journal*](https://doi.org/10.1093/ismejo/wrae181).

## Overview

This study examined how abiotic larval habitat conditions (botanical detritus type, temperature, and microbial dispersal) shape the microbiome of the mosquito *Aedes albopictus*, and how specific bacterial strains interact with those conditions to influence larval development.

## Experiments

**Experiment I — Microbiome assembly:** Gnotobiotic *Ae. albopictus* larvae were reared across 12 fully factorial treatments (3 detrital infusions × 2 temperatures × 2 dispersal levels). 16S rRNA amplicon sequencing (V4 region) was used to characterize bacterial communities in adult mosquitoes and mesocosm water.

**Experiment II — Larval development:** The role of two focal strains (*Chryseobacterium* sp. CHRY1 and *Pseudomonas* sp. PSEU2) in mosquito emergence success was tested across strawberry guava and pure water infusions using gnotobiotic mesocosms.

## Bioinformatics & Analysis

- Raw reads processed with [MetaFlow|mics](https://github.com/metagenlab/MF-mics)
- Taxonomy assigned against SILVA v138.1
- Downstream R analyses use `phyloseq`, `glmmTMB`, `coxme`, and `ggeffects`

## Data Availability

Sequencing data are deposited in NCBI (see paper for accession). Annotated R code and ASV output are available in this repository.

## Citation

Kriefall NG, Seabourn PS, Yoneishi NM, Davis K, Nakayama KK, Weber DE, Hynson NA, Medeiros MCI (2024). Abiotic factors shape mosquito microbiomes that enhance host development. *The ISME Journal*, 18(1), wrae181. https://doi.org/10.1093/ismejo/wrae181

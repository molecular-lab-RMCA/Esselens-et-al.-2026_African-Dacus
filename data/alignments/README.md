# Alignments

This folder contains the sequence alignments used for phylogenetic and divergence-time analyses in the African *Dacus* phylogenomics study.

## Files

| File | Description |
|---|---|
| `dacus_nuclear_500OGs.phy` | Concatenated nuclear alignment based on 500 orthologous groups. |
| `dacus_mitochondrial_13PCGs.phy` | Concatenated mitochondrial alignment based on 13 mitochondrial protein-coding genes. |
| `dacus_chronogram_20loci.phy` | Reduced 20-locus alignment used for divergence-time estimation. |


## Dataset descriptions

### Nuclear alignment

The nuclear alignment was generated from 500 orthologous groups selected from genome-scale data. These orthogroups were present in all seven reference genomes and were selected based on alignment length and ambiguity fraction. This alignment was used for maximum-likelihood phylogenetic inference.

### Mitochondrial alignment

The mitochondrial alignment contains the 13 mitochondrial protein-coding genes:

- `cox1`
- `cox2`
- `cox3`
- `cytb`
- `nad1`
- `nad2`
- `nad3`
- `nad4`
- `nad4l`
- `nad5`
- `nad6`
- `atp6`
- `atp8`

This alignment was used for maximum-likelihood phylogenetic inference of the mitochondrial dataset.

### Chronogram alignment

The chronogram alignment contains 20 conserved marker genes used for divergence-time estimation in MCMCTree. This reduced dataset was used to estimate divergence times under a relaxed molecular-clock framework with fossil-based calibrations.


## Related folders

- `../metadata/` contains specimen-level metadata, host-use information, lure-response data, and chronogram inclusion status.
- `../trees/` contains the maximum-likelihood trees and chronogram files associated with these alignments.

## Citation

Please cite the associated manuscript and this repository when using these alignments.

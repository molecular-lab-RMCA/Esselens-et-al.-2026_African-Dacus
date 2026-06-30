# Alignments

This folder contains the sequence alignments used for phylogenetic and divergence-time analyses in the African *Dacus* phylogenomics study.

## Files

| File | Description |
|---|---|
| `dacus_nuclear_500OGs.fasta.gz` | Concatenated nuclear alignment based on 500 orthologous groups. |
| `dacus_mitochondrial_13PCGs.fasta.gz` | Concatenated mitochondrial alignment based on 13 mitochondrial protein-coding genes. |
| `dacus_chronogram_20loci.fasta.gz` | Reduced 20-locus alignment used for divergence-time estimation. |
| `partitions_nuclear.nex` | Partition file for the nuclear alignment, if applicable. |
| `partitions_mitochondrial.nex` | Partition file for the mitochondrial alignment, if applicable. |
| `oma_groups_chronogram.csv` | List of the 20 OMA groups used for the chronogram dataset. |

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

## Notes

- Alignments are provided in compressed FASTA format (`.fasta.gz`) to reduce file size.
- Missing or ambiguous positions are retained as in the final analyses.
- Taxon labels correspond to the specimen and voucher identifiers listed in the metadata files.
- The chronogram alignment contains a reduced taxon set, with one representative specimen selected per species where possible.
- For *Dacus humeralis*, representatives of the three recovered lineages were included in the chronogram dataset.

## Related folders

- `../metadata/` contains specimen-level metadata, host-use information, lure-response data, and chronogram inclusion status.
- `../trees/` contains the maximum-likelihood trees and chronogram files associated with these alignments.

## Citation

Please cite the associated manuscript and this repository when using these alignments.

# Trees

This folder contains the phylogenetic trees and chronogram files generated for the African *Dacus* phylogenomics study.

## Files

| File                              | Description                                                                                                       |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| `dacus_nuclear_500OGs.treefile`       | Maximum-likelihood tree inferred from the nuclear alignment based on 500 orthologous groups.                      |
| `dacus_mitochondrial_13PCGs.treefile` | Maximum-likelihood tree inferred from the mitochondrial alignment based on 13 mitochondrial protein-coding genes. |
| `dacus_chronogram_20loci.treefile`  | Time-calibrated chronogram inferred with MCMCTree.                                                                |


## Tree descriptions

### Nuclear tree

The nuclear tree was inferred from the concatenated nuclear alignment of 500 orthologous groups. This tree represents the main phylogenomic hypothesis of relationships among the sampled African *Dacus* specimens and related outgroups.

The tree was inferred using maximum-likelihood phylogenetic inference in IQ-TREE, with model selection performed using ModelFinder Plus and node support assessed using ultrafast bootstrap replicates.

### Mitochondrial tree

The mitochondrial tree was inferred from the concatenated alignment of 13 mitochondrial protein-coding genes:

* `cox1`
* `cox2`
* `cox3`
* `cytb`
* `nad1`
* `nad2`
* `nad3`
* `nad4`
* `nad4l`
* `nad5`
* `nad6`
* `atp6`
* `atp8`

This tree was used to compare mitochondrial phylogenetic signal with the nuclear phylogenomic tree.

### Chronogram

The chronogram was inferred from a reduced dataset of 20 conserved marker genes (see `OMA groups`). Divergence-time estimation was performed with MCMCTree under a relaxed molecular-clock framework using fossil-based calibrations.

The chronogram includes one representative *Dacus* specimen per species where possible. For *Dacus humeralis*, representatives of the three recovered lineages were included separately.


## Citation

Please cite the associated manuscript and this repository when using these tree files.


# Genetic and Pharmacologic TRPC6 Inhibition Improves Muscle Function and Survival in Mice with Moderate and Severe Muscular Dystrophy

### Introduction
We performed a bulk RNA-seq study to investigate the role of the TRPC6 in abnormal force and calcium stress-response in DMD-model mouse cardiomycytes. In this study, we looked at gene expression in mice with double knockout of dystrophin and eutrophin (DKO), and either knock out TRPC6 in this DMD model or pharmacologically inhibit the channel with the selective drug BI-749327. The manuscript can be found [here](add link when available). Here, we share the counts tables and metadata to enable downstream analysis. Unfortunately, because of a data transfer error, the raw reads are currently not available, though we will continue to work to make them available in the future. We have also attached the downstream differential gene expression analysis done by GeneWiz.

### Data
The following files are available:

- `counts.csv` and `metadata.csv`: Counts (mapped by `STAR` and counted with `featureCounts`) for this bulk RNA-seq experiment.

- `phenotype_good.txt`: Metadata for the cells in the study. In particular, this includes metadata for only the good barcodes (e.g. not those that had collisions), so those working from `gene_mult.mtx` should use this to subset good barcodes.

Please feel free to email or raise an issue if any other materials are desired!

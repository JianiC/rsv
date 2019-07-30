# RSV
This is the nextstrain build for Human Respiratory syncytial virus.

The human respiratory syncytial virus (RSV) is one of the major causes of respiratory infections, especially in infants and young children.The genome is approximately 15,000 nucleotides in length and is composed of a single strand of RNA with negative polarity. It has 10 genes encoding 11 proteins. Among them, the F and G lipoproteins are the only two that target the cell membrane, and are highly conserved among RSV isolates.
## Aims
Previous RSV sequencing studies have largely focused on partial sequencing of the G gene (200-300 nucleotides) for genotype characterization or diagnostics. Here, we build phylogeny of rsv using G gene, F gene and whole genmome sequences to examine whether current genotype assignment could recapitulate the phylogenetic signal of other genes. We aim to study the genetic diversity and phylogenetic signature of RSV and review the evolutionary systematics of RSV on a global scale.
## Data
RSV whole-genome sequences as well as different single-genome sequences (G gene, F gene) were retrieved from Genbank.

Metadata (including isolated country and date) were extracted from genbank using a little C program gbmunge https://github.com/sdwfrost/gbmunge. Isolated countries information were further coded into 6 WHO region for the analysis purpose. Sequences genotype information were also collected from genbank pages.
## Nextstrain build
Hadfield et al.,[Nextstrain](https://nextstrain.org/) real-time tracking of pathogen evolution, Bioinformatics (2018)

Referece sequences used for Nextstrain build for RSV were listed as follow:

| Dataset | Source | Accession |
| ------- | ------ | --------- |
rsv_A_F	|Genbank|LC377911
rsv_A_G	|Genbank	|KP164507
rsv_A_WGS |Refseq|NC038235
rsv_B_F	|Genbank|	KY296706
rsv_B_G	|Genbank|	KC283036
rsv_B_WGS	|Refseq	|NC001781

For Full instructions on how to set up nextstrain visit: https://nextstrain.org/

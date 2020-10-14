# Shotgun_Metagenomics

16S Sequencing vs Shotgun Metagenomic Sequencing
Which to Choose For Microbiome Studies

16S sequencing or shotgun sequencing? Almost all microbiome researchers ask themselves this question when planning a new study because the vast majority of microbiome publications utilize either 16S rRNA gene sequencing or shotgun metagenomic sequencing to generate raw data for subsequent microbial profiling or metagenomics analyses. Each method has its pros and cons so, which method should you choose?
What is 16S rRNA Gene Sequencing?

16S rRNA gene sequencing, or simply 16S sequencing, utilizes PCR to target and amplify portions of the hypervariable regions (V1-V9) of the bacterial 16S rRNA gene1. Amplicons from separate samples are then given molecular barcodes, pooled together, and sequenced. After sequencing, raw data is analyzed with a bioinformatics pipeline which includes trimming, error correction, and comparison to a 16S reference database. After the reads are assigned to a phylogenetic rank, a taxonomy profile can be generated. Similarly, ITS sequencing follows the same strategy but targeting the ITS (Internal transcribed spacer) region found in fungal genomes.
What is Shotgun Metagenomic Sequencing?

Unlike 16S sequencing, which only targets 16S rRNA genes, shotgun metagenomic sequencing sequences all given genomic DNA from a sample. The library preparation workflow is similar to regular whole genome sequencing, including random fragmentation and adapter ligation. A typical workflow for taxonomy analysis of shotgun metagenomic data includes quality trimming and comparison to a reference database comprising whole genomes (e.g. Kraken2 and Centrifuge3) or selected marker genes (MetaPhlAn4 and mOTU5) to generate a taxonomy profile. Because shotgun metagenomic sequencing covers all genetic information in a sample, the data can be used for additional analyses, e.g. metagenomic assembly and binning, metabolic function profiling, and antibiotic resistance gene profiling.


Analysis of Shotgun Metagenomic sequences.

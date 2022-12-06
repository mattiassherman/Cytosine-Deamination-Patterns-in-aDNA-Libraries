# Cytosine-Deamination-Patterns-in-aDNA-Libraries

Scripts to obtain cytosine deamination damage patterns from human ancient DNA (aDNA) libraries in bash from single fastq files (merged reads) or paired fastq files (unmerged reads), and produce customised plots in R Studios.

Files:
- Human reference genome indexing script [bash]: used to download and index the human reference genome necessary in the primary pipeline, but using the index files available with the reference genome is strongly recommended.
- aDNA cytosine deamination analysis pipeline - merged reads [bash]: used to assess the aDNA characteristics of DNA libraries available online from merged reads (1 fastq file).
- aDNA cytosine deamination analysis pipeline - unmerged reads [bash]: used for the identical function of the previous file but from unmerged reads (2 fastq files).
- Cytosine deamination plot script [R]: used to create customised plots from the damage pattern data of dsDNA or ssDNA libraries produced in the primary pipeline (txt files).

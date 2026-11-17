<p align="center">
    <picture>
        <source srcset="images/GPS_logo_dark.png" media="(prefers-color-scheme: dark)">
        <img src="images/GPS_logo_light.png" style="max-width: 100%; width: 600px;" />
    </picture>
</p>

## Welcome to the Global Pneumococcal Sequencing Project!
[The Global Pneumococcal Sequencing (GPS) Project](https://www.pneumogen.net/gps/) aims to strengthen worldwide genomic surveillance of *Streptococcus pneumoniae* through a decentralised data generation and analysis network to provide evidence for pneumococcal disease control. This GitHub organisation hosts open source tools, databases, and tutorials created under the GPS project. 

## Tool
|                        | Repository                                                                                            | Purpose                                                                                                                                                        |
|------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GPS Pipeline           | [`GlobalPneumoSeq/gps-pipeline`](https://github.com/GlobalPneumoSeq/gps-pipeline)                     | A Nextflow pipeline designed for processing raw reads (FASTQ files) of  *Streptococcus pneumoniae* samples                                                     |
| SeroBA v2              | [`GlobalPneumoSeq/seroba`](https://github.com/GlobalPneumoSeq/seroba)                                 | A k-mer based pipeline to identify the serotype from Illumina NGS reads                                                                                        |
| CPS Extractor Pipeline | [`GlobalPneumoSeq/cps_extractor`](https://github.com/GlobalPneumoSeq/cps_extractor)                   | A Nextflow pipeline designed for processing *Streptococcus pneumoniae*  reads to extract the capsular locus sequence (CPS) and check for  disruptive mutations |
| Check HP | [`GlobalPneumoSeq/check_hp`](https://github.com/GlobalPneumoSeq/check_hp)                   | Scan Bakta-generated GFF3 annotations for homopolymers in CDS promoter regions |



## Database
|                        | Repository / Link                                                                                     | Purpose                                                                                                                                                        |
|------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GPS Database           | [GPS Database Overview](https://www.pneumogen.net/gps/gps-database-overview/)                         | Access point of all publicly available GPS data and its metadata                                                                                               |
| PopPUNK GPS Database   | [PopPUNK GPS Database on Zenodo](https://doi.org/10.5281/zenodo.22794489)| [PopPUNK](https://poppunk-docs.bacpop.org/) database to assign [Global Pneumococcal Sequence Cluster (GPSC)](https://www.pneumogen.net/gps/#/gpsc) |
| GPSC Reference Genomes | [`GlobalPneumoSeq/gpsc-reference-genomes`](https://github.com/GlobalPneumoSeq/gpsc-reference-genomes) | Assemblies ( `.fasta` ) and annotations ( `.gff3`) of reference genomes for 73 common GPSCs                            |
| Standardised Colour Palettes for GPSC and Serotype | [`GlobalPneumoSeq/gps-database-processor/scripts/data`](https://github.com/GlobalPneumoSeq/gps-database-processor/tree/main/scripts/data) | The latest standardised GPSC and serotype colour palettes                            |


## Tutorial
|                        | Repository                                                                                            | Purpose                                                                                                                                                        |
|------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FASTQ to Microreact    | [`GlobalPneumoSeq/fastq-to-microreact`](https://github.com/GlobalPneumoSeq/fastq-to-microreact)       | A tutorial on how to go from raw read sequencing files (FASTQ) to a Microreact visualisation instance for *Streptococcus pneumoniae*                           |

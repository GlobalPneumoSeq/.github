<p align="center">
    <picture>
        <source srcset="images/GPS_logo_dark.png" media="(prefers-color-scheme: dark)">
        <img src="images/GPS_logo_light.png" style="max-width: 100%; width: 600px;" />
    </picture>
</p>

## Welcome to the Global Pneumococcal Sequencing Project!
The Global Pneumococcal Sequencing (GPS) Project aims to strengthen worldwide genomic surveillance of *Streptococcus pneumoniae* through a decentralised data generation and analysis network to provide evidence for pneumococcal disease control. This GitHub organisation hosts open source tools, databases, and tutorials created under the GPS project. 

## Tool
|                        | Repository                                                                                            | Purpose                                                                                                                                                        |
|------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GPS Pipeline           | [`GlobalPneumoSeq/gps-pipeline`](https://github.com/GlobalPneumoSeq/gps-pipeline)                     | A Nextflow pipeline designed for processing raw reads (FASTQ files) of  *Streptococcus pneumoniae* samples                                                     |
| SeroBA                 | [`GlobalPneumoSeq/seroba`](https://github.com/GlobalPneumoSeq/seroba)                                 | A k-mer based pipeline to identify the serotype from Illumina NGS reads                                                                                        |
| CPS Extractor Pipeline | [`GlobalPneumoSeq/cps_extractor`](https://github.com/GlobalPneumoSeq/cps_extractor)                   | A Nextflow pipeline designed for processing *Streptococcus pneumoniae*  reads to extract the capsular locus sequence (CPS) and check for  disruptive mutations |


## Database
|                        | Repository                                                                                            | Purpose                                                                                                                                                        |
|------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GPSC Reference Genomes | [`GlobalPneumoSeq/gpsc-reference-genomes`](https://github.com/GlobalPneumoSeq/gpsc-reference-genomes) | Assemblies ( `.fasta` ) and annotations ( `.gff3`) of reference genomes for 73 common Global Pneumococcal Sequence Clusters (GPSCs)                            |

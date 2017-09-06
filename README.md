# MutationTools
Collected methods of mutation detection from WGS/WES

## Mutation software
- [scalpel](http://scalpel.sourceforge.net/manual.html): Find (somatic or de novo) indel from WGS/WES 
- [MuSiC2](https://github.com/ding-lab/MuSiC2):Identifying mutational significance in cancer genomes

## Mutation & pathway enrichment
###[MuSiC](http://gmt.genome.wustl.edu/packages/genome-music/index.html)
[Example](http://wp.zxzyl.com/?p=276)

## Driver mutation from Cancer sequencing data set of multiple samples
1. [MuSiC-SMG/MutSigCV](http://software.broadinstitute.org/cancer/software/genepattern/modules/docs/MutSigCV) 
- [Docker-MutSigCV](https://hub.docker.com/r/argrosso/mutsigcv/)

Identify genes mutated more frequently than background mutation rate based on patient-based factors and genomic position-based factors.
 - The patient-based factors include:
overall mutation rate
overall mutational spectrum (e.g., the percentages of mutations that are transitions of certain types, transversions of certain types, and/or nonsense)
 - The genomic position-based factors include:
gene expression levels.
DNA replication timing.
HiC-based chromatin state estimation.

2. [OncodriveCLUST](https://bitbucket.org/bbglab/oncodriveclust) Gain-of-function--Oncogene

OncodriveCLUST is a method aimed to identify genes whose mutations are biased towards a large spatial clustering. This method is designed to exploit the feature that mutations in cancer genes, especially oncogenes, often cluster in particular positions of the protein.

Database used for OncodriveCLUST
- [CGC](http://cancer.sanger.ac.uk/census/) Belong to COSMIC
  need regist
- [DriverDBv2](http://driverdb.tms.cmu.edu.tw/driverdbv2/)
Integrated several database and annotated with several prediction software

3. [OncodriveFM](https://bitbucket.org/bbglab/oncodrivefm) Lose-of-function--Tumor superessor gene

OncodriveFM detects candidate cancer driver genes and pathways from catalogs of somatic mutations in a cohort of tumors by computing the bias towards the accumulation of functional mutations (FM bias).

4. [ActiveDriver](https://cran.r-project.org/web/packages/ActiveDriver/index.html)

A mutation analysis tool that discovers cancer driver genes with frequent mutations in protein signalling sites such as post-translational modifications (phosphorylation, ubiquitination, etc)

###



## Knowledge
- [SVs](http://biosb.nl/wp-content/uploads/2014/10/Day-2-Guryev-CNV-calling-in-Gene-Panels.pdf)

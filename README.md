# Haplotype-resolved hybrid pepper genome with trio binning
Germplasm lines are HDA149 and HDA330. Their F1 offspring is called 'F1 (HDA149xHDA330)' or simply the F1   

The input data for trio-binning assembly are:
1) Short read sequencing on HDA149
2) Short read sequencing on HDA330
3) PacBio Hifi sequencing on the F1
4) Bionano optical mapping on the F1

    
     
The two resulting genome assemblies are:
1) Capsicum_annuum_HDA149v1.0.fasta
2) Capsicum_annuum_HDA149v1.0.fasta

## The steps in genome assembly are:
1) Raw data processing   
[PacBio Hifi sequencing data on the F1 (HDA149 x HDA330)](https://github.com/USDA-ARS-GBRU/Pepper_TrioBinning/wiki/Raw-sequencing-data-processing-for-PacBio-Hifi-of-the-F1-sample-(HDA149-x-HDA330))    
[Illumina 150 bp PE sequencing data on parents (HDA149 and HDA330)](https://github.com/USDA-ARS-GBRU/Pepper_TrioBinning/wiki/Raw-sequencing-data-processing-for-short-reads-on-parents-(HDA149-and-HDA330))
2) [Binning HiFi reads](https://github.com/USDA-ARS-GBRU/Pepper_TrioBinning/wiki/Binning-HiFi-reads)
3) [Assembly of binned HiFi reads with HiCanu](https://github.com/USDA-ARS-GBRU/Pepper_TrioBinning/wiki/Assembly-of-binned-HiFi-reads-with-HiCanu)   
4) [Assembly of binned HiFi reads with hifiasm](https://github.com/USDA-ARS-GBRU/Pepper_TrioBinning/wiki/Assembly-of-binned-HiFi-reads-with-hifiasm)   
5) Bionano optical map merger with assembly
6) Homology based scaffolding workflow
7) Homology based scaffolding to other reference genomes for chromosome designation and orientation

Other scripts included here are:
1) Assembly statistics calculation
2) Assembly with hifiasm on the un-binned reads
3) Assembly with hifiasm's trio-binning method

## Figures in publication


## 

# Maize Data
Exploring NGS data of zea mays


## zmHapMap
### Current Version downloaded on `8/22/2016` using `iget`.
Maize HapMapV3.2.1 genotypes (without imputation), for more information refer to [panzea](http://cbsusrv04.tc.cornell.edu/users/panzea/filegateway.aspx?category=Genotypes).
```
icd /iplant/home/shared/panzea/hapmap3/hmp321/unimputed/
```

### Basic statistics

1. WGS data from 1,210 maize lines.
2. 83 million SNPs (30 million SNPs marked with LLD are high confidence markers)

----------

# ZeaGBS

The current version is [ZeaGBSv2.7](http://cbsusrv04.tc.cornell.edu/users/panzea/download.aspx?filegroupid=4).
I get the data via the following path on CyVerse (iPlant):
```
icd /iplant/home/shared/panzea/genotypes/GBS/v27/
iget AllZeaGBSv2.7_publicSamples_imputedV3b_agpv3_sorted.vcf.gz
```
1. It contains genotypes for 955,690 SNPs at more than 60K taxa (samples), 17,280 of which are public. 
2. AGPv3 coordinates in hapmap and VCF formats.




----------

# ZeaTx


# COSMIC v98

For annovar db use

## GRCh38/cosmic/v98/
### COSMIC mutation data
Download:

* [CosmicMutantExport.tsv.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh38/cosmic/v98/CosmicMutantExport.tsv.gz)

* [CosmicNCV.tsv](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh38/cosmic/v98/CosmicNCV.tsv.gz)

### Coding and Non-conding mutations
Download:

* [CosmicCodingMuts.vcf.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh38/cosmic/v98/VCF/CosmicCodingMuts.vcf.gz) 
    
* [CosmicNonCodingVariants.vcf.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh38/cosmic/v98/VCF/CosmicNonCodingVariants.vcf.gz)


```
prepare_annovar_user.pl -dbtype cosmic CosmicMutantExport.tsv -vcf CosmicCodingMuts.vcf > hg38_cosmic98_coding.txt
prepare_annovar_user.pl -dbtype cosmic CosmicNCV.tsv -vcf CosmicNonCodingVariants.vcf > hg38_cosmic98_noncoding.txt
```


---

## GRCh37/cosmic/v98/
### COSMIC mutation data
Download:

* [CosmicMutantExport.tsv.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh37/cosmic/v98/CosmicMutantExport.tsv.gz)

* [CosmicNCV.tsv](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh37/cosmic/v98/CosmicNCV.tsv.gz)

### Coding and Non-conding mutations
Download:

* [CosmicCodingMuts.vcf.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh37/cosmic/v98/VCF/CosmicCodingMuts.vcf.gz) 

* [CosmicNonCodingVariants.vcf.gz](https://cancer.sanger.ac.uk/cosmic/file_download/GRCh37/cosmic/v98/VCF/CosmicNonCodingVariants.vcf.gz)

```
prepare_annovar_user.pl -dbtype cosmic CosmicMutantExport.tsv -vcf CosmicCodingMuts.vcf > hg19_cosmic98_coding.txt
prepare_annovar_user.pl -dbtype cosmic CosmicNCV.tsv -vcf CosmicNonCodingVariants.vcf > hg19_cosmic98_noncoding.txt
```

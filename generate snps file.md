## Add SEQKT to your environment
``` bash
echo 'export PATH=/ocean/projects/agr250001p/shared/software/seqtk:$PATH' >> ~/.bashrc
source ~/.bashrc
```
subsample 10% fastq file using seqtk 
seqtk sample -s100 input.fastq 0.1 > subsampled.fastq
``` bash
grep -v "^#" ERR251429.vcf | shuf -n 5 > selected_snps.txt
```

Go to https://useast.ensembl.org/Tools/VEP

Paste snps and adjust filters
module loas htslib
bgzip -c vcf > vcf.gz

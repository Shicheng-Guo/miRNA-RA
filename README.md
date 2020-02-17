#### Association study to East-Asian cSNPs in microRNA identifies novel rheumatoid arthritis susceptibility genetic variants
Timeline: 

* `grep -v primary hsa.gff3 | grep -v '#'| awk '{print $1,$4,$5,$9}' OFS="\t" >hsa.gff3.hg19.bed`
* `wget https://raw.githubusercontent.com/Shicheng-Guo/miRNA-RA/master/db/hsa.gff3`
* Upload Summary Statistics (logistic regression)
* Upload dbSNP153
* Upload human microRNA hsa.gff (release 21)

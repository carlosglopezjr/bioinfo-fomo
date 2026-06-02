# Assingment for Week 1

## Choose an organims and look through its gff3 file for information on most common types of features.
The organism I've chosen is the Wester gorilla or Gorilla Gorilla. The organism has the following snapshot
- 470196	exon
- 449881	CDS
- 60150	biological_region
- 44987	mRNA
- 40686	scaffold
- 25624	five_prime_UTR
- 21794	gene
- 18704	three_prime_UTR
- 7768	ncRNA_gene
- 2071	transcript
- 2046	miRNA
- 1749	snRNA
- 843	snoRNA
- 711	lnc_RNA
- 522	pseudogene
- 522	pseudogenic_transcript
- 501	rRNA
- 163	V_gene_segment
- 46	scRNA
- 44	C_gene_segment
- 25	chromosome
- 22	tRNA

Some things that stand out: the majority of this file contains exons  and coding sequences  which suggests it is a
well documented species. It contains 25 chromosomes, 22 features with 21794 genes listed in total. Some types im unfamiliar with are the V_gene segment and the C_gene_segment which are actually variable(V) and constant(C) gene segments which refer to the region of an immune receptor which helps recognize different antigens/pathogens. The top ten feature types are exon, CDS, biological_region, mRNA, scaffold, five_prime_UTR, gene, three_prime_UTR, ncRNA_gene, and transcript.

the code to obtain the file is only one like here:

within terminal:
```bash
wget https://ftp.ensembl.org/pub/current_gff3/gorilla_gorilla/Gorilla_gorilla.gorGor4.115.gff3.gz
```

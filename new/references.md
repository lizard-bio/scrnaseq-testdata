DropSeq:
https://www.ebi.ac.uk/ena/browser/view/PRJEB36017?show=reads

CEL-Seq2 data:
https://www.ebi.ac.uk/ena/browser/view/PRJNA674526?show=reads

E-MTAB-9061

All testdatasets where sampled to 100k reads using seqkit with default random seed 
eg:

seqkit sample -2 -n 100000 -s 11  scrTG003_mm10_S1_L001_R1_001.fastq.gz -o scrTG003_mm10_S1_L001_R1_001_sub100k.fastq.gz
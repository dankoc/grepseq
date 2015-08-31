# grepseq
Automatically exported from code.google.com/p/grepseq

Useful bioinformatic tool for searching strings in a fasta file. Use: 
```bash
$ zcat hg19.fa.gz | head -n 5000 > tmp.fa
$ perl grepseq.pl ACGAT tmp.fa
chr1:14697:5:acgat
chr1:31790:5:acgat
chr1:34012:5:acgat
chr1:44720:5:acgat
chr1:46134:5:acgat
chr1:49624:5:acgat
chr1:52026:5:acgat
chr1:53886:5:acgat
chr1:55883:5:acgat
chr1:63195:5:acgat
chr1:72764:5:acgat
chr1:78699:5:acgat
chr1:85404:5:acgat
chr1:89564:5:acgat
chr1:91001:5:acgat
chr1:108869:5:acgat
chr1:109174:5:acgat
chr1:112856:5:acgat
chr1:113967:5:acgat
chr1:115670:5:acgat
chr1:119414:5:acgat
chr1:125974:5:acgat
chr1:129052:5:acgat
chr1:129330:5:acgat
chr1:135537:5:acgat
chr1:139528:5:acgat
chr1:146374:5:acgat
chr1:151042:5:acgat
chr1:155910:5:acgat
chr1:168148:5:acgat
chr1:171236:5:acgat
chr1:230693:5:acgat
chr1:232446:5:acgat
chr1:235431:5:acgat
chr1:236125:5:acgat
chr1:237329:5:acgat
```

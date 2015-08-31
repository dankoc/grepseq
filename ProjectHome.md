A grep-like command-line tool for searching a file of genomic sequences for underlying substrings. Produces the position and length of the match as well as the match itself.

Usage:
  * `grepseq [OPTIONS] 'REGEX' FILENAME`

Some examples are:
  * Search for gaps:
> `grepseq 'N+' sequence.fasta`

  * Search for SSRs (Simple Sequence Repeats):
> `grepseq '([ACTG]{2,5})\1{2,}' sequence.fasta`
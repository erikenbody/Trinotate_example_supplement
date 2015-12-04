# Trinotate_example

Supplementary material for running a Trinotate workflow example with mouse transcriptome data. 
Included:
- mouse38_cdna.fa.gz: (compressed) fasta file of mouse transcript sequences from Ensembl
- gene_transcript_map.txt: tab-delimited text file indicating the gene/transcript relationships
- split_fasta.pl: Perl script to break nucleotide and peptide fasta files into volumes of a given number of sequences. 
    Usage: split_fasta.pl <input_file> <output_volume_prefix> <num_sequences_per_volume>



A extract_fasta_seqs.py 
Script to extract one to many fasta sequences from input fasta file in a fast and more efficient way.
Requirement: Biopython
1. usage: python extract_fasta_seqs.py --headers_file seq_header_list.txt  fasta_file.fa 
2. usage: python extract_fasta_seqs.py fasta_file.fa header1 ### to get extract header1 sequence from fasta_file.fa
3. usage: python extract_fasta_seqs.py fasta_file.fa header1 header2 ### to get extract header1 header2 and sequence from fasta_file.fa

B. split_fasta.sh
bash script to split large fasta file into smaller files

Usage: fasta_file number_of_splits



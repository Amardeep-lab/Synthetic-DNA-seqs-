# Synthetic-DNA-seqs-
Here is the updated `README.md` file:

# DNA Sequences with Planted Motifs
This repository contains synthetic datasets of DNA sequences with motifs planted at random positions. The datasets are designed for research purposes and can be used to benchmark motif discovery algorithms.

## Dataset Structure
The datasets are organized as follows:

synthetic_data/
    ├── alpha_val_0.1_no_of_seq_500_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.1_no_of_seq_700_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.1_no_of_seq_900_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.1_no_of_seq_1000_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.1_no_of_seq_500_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.1_no_of_seq_700_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.1_no_of_seq_900_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.1_no_of_seq_1000_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.1_no_of_seq_500_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.1_no_of_seq_700_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.1_no_of_seq_900_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.1_no_of_seq_1000_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.01_no_of_seq_500_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.01_no_of_seq_700_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.01_no_of_seq_900_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.01_no_of_seq_1000_len_of_seq_100_len_of_motif_8
    ├── alpha_val_0.01_no_of_seq_500_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.01_no_of_seq_700_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.01_no_of_seq_900_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.01_no_of_seq_1000_len_of_seq_100_len_of_motif_9
    ├── alpha_val_0.01_no_of_seq_500_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.01_no_of_seq_700_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.01_no_of_seq_900_len_of_seq_100_len_of_motif_10
    ├── alpha_val_0.01_no_of_seq_1000_len_of_seq_100_len_of_motif_10
    └── original_motifs/
        ├── or_0.1_500_8.png
        ├── or_0.1_700_8.png
        ├── or_0.1_900_8.png
        ├── or_0.1_1000_8.png
        ├── or_0.1_500_9.png
        ├── or_0.1_700_9.png
        ├── or_0.1_900_9.png
        ├── or_0.1_1000_9.png
        ├── or_0.1_500_10.png
        ├── or_0.1_700_10.png
        ├── or_0.1_900_10.png
        ├── or_0.1_1000_10.png
        ├── or_0.01_500_8.png
        ├── or_0.01_700_8.png
        ├── or_0.01_900_8.png
        ├── or_0.01_1000_8.png
        ├── or_0.01_500_9.png
        ├── or_0.01_700_9.png
        ├── or_0.01_900_9.png
        ├── or_0.01_1000_9.png
        ├── or_0.01_500_10.png
        ├── or_0.01_700_10.png
        ├── or_0.01_900_10.png
        ├── or_0.01_1000_10.png

### Synthetic Data

The `synthetic_data` folder contains 24 datasets. Each dataset consists of DNA sequences with one motif instance planted randomly in each sequence. The datasets are named according to the following pattern:

alpha_val_<alpha_value>_no_of_seq_<number_of_sequences>_len_of_seq_100_len_of_motif_<motif_width>.txt

#### Examples
- `alpha_val_0.1_no_of_seq_900_len_of_seq_100_len_of_motif_10.txt`: Contains 900 DNA sequences, each 100 nucleotides long, with a motif of width 10 planted at a random position.
- `alpha_val_0.01_no_of_seq_700_len_of_seq_100_len_of_motif_8.txt`: Contains 700 DNA sequences, each 100 nucleotides long, with a motif of width 8 planted at a random position.

### Original Motifs

The `original_motifs` folder contains motif logos corresponding to each dataset. The motif logos are images visually representing the motifs planted in the DNA sequences. The files are named according to the following pattern:

or_<alpha_value>_<number_of_sequences>_<motif_width>.png


#### Examples

- `or_0.1_500_8.png`: Contains the motif logo for the dataset with 500 DNA sequences and a motif of width 8.
- `or_0.01_1000_9.png`: Contains the motif logo for the dataset with 1000 DNA sequences and a motif of width 9.

### File Format

The DNA sequences are provided in simple text format. Each line in a dataset file represents a single DNA sequence.

## Usage

These datasets can be used to test and benchmark motif discovery algorithms. The synthetic nature of the data allows for controlled experimentation and validation of algorithm performance.

## Acknowledgments

This work was supported by the University Grants Commission (UGC) of India, with Amardeep Singh as a Senior Research Fellow.

For any questions or issues, please contact Amardeep Singh.

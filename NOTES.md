# Day 1 Notes — BLAST

## What is BLAST?

BLAST (Basic Local Alignment Search Tool) is a bioinformatics tool used to find similarities between biological sequences.

It compares a query sequence against sequences stored in databases.

Query sequence can be:

- DNA
- RNA
- Protein

---

# Why BLAST is Used

BLAST is used for:

- Gene identification
- Functional annotation
- Finding homologous sequences
- Studying evolutionary relationships
- Analysing mutations

---

# BLAST Workflow

Sequence
↓
Database Search
↓
Local Alignment
↓
Similarity Score
↓
Result Interpretation


---

# How BLAST Works

BLAST uses a heuristic approach.

Steps:

1. Divide query sequence into small words
2. Search database for matching words
3. Extend matching regions
4. Score alignments


This makes BLAST faster than checking every possible alignment.

---

# Types of BLAST


## BLASTN

Query:
Nucleotide

Database:
Nucleotide

Used for finding similar DNA sequences.


## BLASTP

Query:
Protein

Database:
Protein

Used for protein similarity.


## BLASTX

Query:
DNA

Database:
Protein

Used for identifying possible coding regions.


## TBLASTN

Query:
Protein

Database:
Nucleotide

Used for finding related genes.

---

# Important BLAST Parameters


## Identity

Percentage of identical bases/amino acids.

Higher identity means stronger similarity.


## Query Coverage

Percentage of query sequence included in alignment.

Higher coverage gives more reliable results.


## E-value

Probability that a match occurred by chance.

Lower E-value means more significant similarity.


## Bit Score

Measures alignment quality.

Higher score indicates better alignment.


---

# Databases

## nr

Non-redundant protein database.


## nt

Nucleotide sequence database.


## RefSeq

Curated reference sequences.


## UniProt

Protein database with functional information.


---

# Key Learning

BLAST helps researchers compare sequences and understand possible biological functions.

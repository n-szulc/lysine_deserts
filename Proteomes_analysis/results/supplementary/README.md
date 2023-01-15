Tables `Table_reference_eukaryota_proteomes_summary.tsv` and `Table_reference_bacteria_proteomes_summary.tsv` contain the following information:

| Column  | Description  |
|:--|:--|
| **Taxon**  | Taxon name |
| **UniProt proteome ID**  | Proteome ID from the UniProt database|
| **NCBI taxon ID**  | Taxon ID from the NCBI |
| **Total sequences in proteome**  | Number of all sequences in proteome |

---
Tables `Table_escherichia_phages_proteomes_summary.tsv`, `Table_bacillus_phages_proteomes_summary.tsv`, and `Table_mycobacterium_phages_proteomes_summary.tsv` contain the following information:

| Column  | Description  |
|:--|:--|
| **NCBI taxon ID**  | NCBI ID of the taxon|
| **UniProt proteome ID**  | Proteome ID from the UniProt database|
| **Total sequences in proteome**  | Number of all sequences in proteome |

---

Tables `Table_phages_proteomes_summary.tsv` contains the following information:

| Column  | Description  |
|:--|:--|
| **Phages group**  | Name of the phages' group |
| **Proteomes number**  | Number of all proteomes |
| **Filtered proteomes number**  |  Number of proteomes which have less than 40 sequences (default threshold)|
| **Total sequence number in filtered proteomes**  |  Total number of sequences in filtered proteomes |
| **Fraction of sequences from filtered proteomes used for cd-hit**  |  Fraction of sequences of min. 150 aa length (default threshold) among all sequences in filtered proteomes |
| **Total number of sequences in panproteome** | Total number of sequences after clustering|
| **Median sequence length in panproteome** | Median sequence length after clustering|

---

Tables `Pupylome_summary.tsv` contains the following information:

| Column  | Description  |
|:--|:--|
| **Taxon**  | Taxon name |
| **Number of proteins in proteome**  | Total number of proteins in proteome |
| **Number of pupylated proteins**  |  Number of pupylated proteins |
| **Fraction of pupylated proteins** | Fraction of pupylated proteins in proteome|

---

Tables `Lysine_deserts_min_0.5_among_pupylated_proteins.tsv`, `Lysine_deserts_min_0.5_among_nonpupylated_proteins.tsv`,`Lysine_deserts_min_150_among_pupylated_proteins.tsv`, and `Lysine_deserts_min_150_among_nonpupylated_proteins.tsv` contain the following information:

| Column  | Description  |
|:--|:--|
| **Taxon**  | Taxon name |
| **Total number of sequences**  | Total number of proteins in proteome |
| **Total number of filtered sequences**  |  Total number of filtered proteins in proteome (fulfilling default criteria of minimum length of 150 aa and maximum predicted TMH number of 2.0)  |
| **Average length of filtered sequences** | Average sequence length of filtered proteins|
| **Number of sequences with lysine desert** | Number of sequences which have defined lysine desert among pupylome or nonpupylome (both conditions indicated in the table's title)|
| **Fraction of sequences with lysine desert** | Fraction of proteins with defined lysine desert among pupylome or nonpupylome (both conditions indicated in the table's title) among filtered proteins |

---

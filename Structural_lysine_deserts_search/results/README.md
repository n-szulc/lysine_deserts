Table `all_calc_structural_lysine_deserts.tsv` contains lists of exposed residues constituting structural lysine desert with additional calculated features in AlphaFold2 models of the human proteome obtained from the AlphaFold Protein Structure Database.

It contains the following information:

| Column  | Description  |
|:--|:--|
|**UniProtID**| UniProt ID |
|**Length**| Protein (chain) length obtained from the PDB file |
|**Seq_desert_150**| Binary value (0/1) describing if lysine desert min. 150 aa exists in sequence|
|**Seq_desert_0.5**| Binary value (0/1) describing if lysine desert min. 50% exists in sequence|
|**Seq_any_lys_cluster**| Binary value (0/1) describing occurrence of the lysine cluster (⌊80% of lysines⌋  located anywhere within 20% of the sequence) |
|**Seq_N_lys_cluster**| Binary value (0/1) describing occurrence of the lysine cluster at the N-terminus (⌊80% of lysines⌋  located within the first 20% of sequence)|
|**Seq_C_lys_cluster**|Binary value (0/1) describing occurrence of the lysine cluster at the C-terminus (⌊80% of lysines⌋  located within the last 20% of sequence)|
|**Seq_longest_desert**| Longest lysine-less region in the sequence |
|**Seq_longest_desert_start_index**| Start index of longest lysine-less region in the sequence|
|**Seq_longest_desert_end_index**| End index of longest lysine-less region in the sequence|
|**Seq_desert_percentage**| Fraction of the longest lysine-less region in the sequence|
|**Struct_residues_percentage_no_dssp_values**| Fractions of residues in chain that have no calculated SASA/RSA values due to the DSSP errors |
|**Struct_no_exposed_aa**| Number of exposed residues in the chain |
|**Struct_total_SASA**| Calculated total SASA for the chain |
|**Struct_1_best_desert_length**| Number of residues creating the 1st longest structural lysine desert in the chain |
|**Struct_1_best_desert_length_percentage**| Fraction of number of residues creating the 1st longest structural lysine desert in protein (value of protein (chain) length derived from the PDB file)|
|**Struct_1_best_desert_among_all_exposed_percentage**| Fraction of number of residues creating the 1st longest structural lysine desert among the exposed residues |
|**Struct_1_best_desert_among_total_SASA_percentage**| Fraction of SASA for residues creating the 1st longest structural lysine desert among protein's (chain's) total SASA|
|**Struct_1_best_pymol_command**|PyMOL command to visualize the 1st longest structural lysine desert |
|**Sequence**| Protein sequence derived directly from the structure|

---
> **_NOTE:_**  Same descriptions as `Struct_1_best_*` in apply to columns `Struct_2_best_*` and `Struct_3_best_*` which have information for the 2nd and 3rd longest structural lysine deserts, respectively.
---

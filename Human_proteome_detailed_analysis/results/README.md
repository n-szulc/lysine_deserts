This directory contains the table `lysine_deserts_human_proteome.tsv.gz` with information about presence of lysine deserts of defined type and other features in the reference human proteome from the UniProt database,as well as other results.

The table contains the following information:

| Column  | Description  |
|:--|:--|
| **UniProtID** | UniProt ID|
| **Gene symbol** | First gene symbol from the UniProt database|
| **All gene symbols** | All gene symbols from the UniProt database|
| **HK gene** | Indicates if the gene is considered as a housekeeping (Yes/No)|
| **Sequence** | Amino acid sequence|
| **Sequence length** | Length of amino acid sequence|
| **Subcellular location** | Protein subcellular locations derived from the UniProt database|
| **Function** | Protein functions derived from the UniProt database|
| **GO:Biological Process** | GO Biological Processes associated with the protein, derived from the UniProt database|
| **GO:Molecular Function** | GO Molecular Functions associated with the protein, derived from the UniProt database|
| **GO:Cellular Component** | GO Cellular Components associated with the protein, derived from the UniProt database|
| **Pathway** | Pathways associated with the protein, derived from the UniProt database|
| **Tissue** | Tissue specificity of the protein derived from the UniProt database|
| **Disease** | Diseases associated with the protein, derived from the UniProt database|
| **Families** | Protein families associated with the protein, derived from the UniProt database|
| **Interactors** |  Interactors of the protein derived from the UniProt database; if interactor's gene symbol is available, its gene symbol is followed with UniProt ID in parentheses, otherwise only UniProt ID is reported|
| **Protein existence** | Degree of protein existence certainty derived from the UniProt database|
| **PDB** | Information on number of protein experimental structures and methods used to obtain them, derived from the UniProt database|
| **IDR_region_start..end** | Ranges of intrinsically disordered regions (IDRs) calculated based on the pLLDT scores from AlphaFold2 models obtained from the MobiDB database |
| **IDR_region_fraction** | Sequence fractions of intrinsically disordered regions calculated based on the pLLDT scores from AlphaFold2 models obtained from the MobiDB database |
| **NumTMH** | Number of predicted transmembrane helices by the TMHMM-2.0 software |
| **Lysine desert 150** | Indicates existence (Yes/No) of a lysine desert of min. 150 aa length|
| **Lysine desert 0.5** | Indicates existence (Yes/No) of a lysine desert of min. 50% protein length|
| **Lysine cluster anywhere** | Indicates existence (Yes/No)  of lysine cluster (80% of protein's lysines in the 20% of protein's sequence) anywhere in the sequence|
| **N end lysine cluster** | Indicates existence (Yes/No)  of lysine cluster (80% of protein's lysines in the 20% of protein's sequence) on N end (first 20% of sequence)|
| **C end lysine cluster** | Indicates existence (Yes/No)  of lysine cluster (80% of protein's lysines in the 20% of protein's sequence) on C end (last 20% of sequence)|
| **Lysine cluster start index** | Index of the first lysine of the lysine cluster|
| **Lysine cluster end index** | Index of the last lysine of the lysine cluster |
| **Longest lysine desert** | Length of the longest lysine-devoid region|
| **Longest lysine desert start index** | Start index of the longest lysine-devoid region|
| **Longest lysine desert end index** | End index of the longest lysine-devoid region|
| **Lysine desert sequence fraction** | Fraction of the longest lysine-devoid region in the sequence|
| **Lysine number in sequence** | Number of lysines in sequence|
| **Lysine fraction in sequence** | Fraction of lysines in sequence|
| **Arginine fraction in sequence** | Fraction of arginines in sequence|
| **Lysine desert associated domains** | If protein has a lysine desert of any type, all protein domains that cover the longest lysine-devoid region in at least 60% are listed, otherwise states Not applicable|
| **E3 class** | Type of E3 ligase derived from the authors' manually curated list of E3s; if protein is not an E3 ligase, states Not applicable|
| **K variants** | Protein variants considering lysines, both ways (lysine mutated to another amino acid or lysine appeared due to a mutation), derived from the UniProt database|
| **K variants in lysine desert** | Protein variants considering lysine appearance within the lysine desert region or  disappearance of flanking lysines, derived from the UniProt database; if protein has no lysine desert of any kind it states Not applicable|
| **K variants description** | Description of all K variants in sequence derived from the UniProt database|

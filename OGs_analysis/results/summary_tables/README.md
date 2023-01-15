This directory contains subdirectories for each analyzed eukaryotic families/order, namely *Saccharomycetaceae/Rhabditida/Drosophilidae/Rodentia/Hominidae*, with tables containing information about their OGs with lysine desert indicated in the table's title. See `OGs_analysis/Pipeline.ipynb` for algorithm's details.

These tables contain the following information:

| Column  | Description  |
|:--|:--|
| **All gene symbols**  | All Gene Symbols mapped to MSA  |
|**Reference organism gene symbols** | Gene symbols associated with reference taxon|
| **Lysine desert type**  |  Type of found lysine desert, see Par. 3.1. of `Pipeline.ipynb` |
|  **Avg lysine desert conservation** | Average number of columns with defined fraction of non-gaps characters (default: 70%); provides information about quantity of gaps in lysine desert region.  <br> **Only for Aligned**  lysine desert type  |
| **Lysine deserts no**  | Number of lysine deserts regions.  <br> **Only for Aligned**  lysine desert type   |
|**Fraction of sequences completely lysine devoid** | Fraction of sequences (either within aligned lysine desert region in Aligned type or among entire sequences in Anywhere type) which contain region completely devoid of lysine of given length|
|**Median sequence length** | Median sequence length in MSA|
|**Median lysine desert length** | Median sequence length of lysine desert regions|
|**Ratio of median lysine desert to median sequence length** | Median lysine desert length divided by median sequence length|
|**Lysine desert start index** | Start index (sequence indexed from 1) of lysine desert region.  <br> **Only for Aligned**  lysine desert type|
|**Lysine desert end index** | End index (sequence indexed from 1) of lysine desert region.  <br> **Only for Aligned**  lysine desert type|
|**Number of sequences** | Number of sequences in MSA|
|**Ratio of number of sequences to number of taxons** | Number of sequences divided by number of taxons in MSA|
|**COG** | COG annotation for MSA obtained from eggNOG5 database|
|**Lysine cluster anywhere fraction** | Fraction of sequences in MSA which contain Lysine Cluster anywhere in their sequences|
|**Lysine cluster at N-end fraction** | Fraction of sequences in MSA which contain Lysine Cluster at their N-ends|
|**Lysine cluster at C-end fraction** | Fraction of sequences in MSA which contain Lysine Cluster at their C-ends|
|**Avg no of lysines** | Average number of lysines per sequence in MSA|
|**Avg lysines fraction** | Average fraction of lysines per sequence in MSA|
|**Avg no of arginines** | Average number of arginines per sequence in MSA|
|**Avg arginines fraction** | Average fraction of arginines per sequence in MSA|
|**Glycine no, Proline no, Alanine no, Valine no, Leucine no,  <br> Isoleucine no, Methionine no, Cysteine no, Phenylalanine no,  Tyrosine no, Tryptophan no, Histidine no, Lysine no, Arginine no,  <br> Glutamine no, Asparagine no, Glutamic acid no, Aspartic acid no, Serine no, Threonine no, Other no** | Counted number of given amino acid within lysine desert region.  <br>**Only for Aligned**  lysine desert type|
|**Total no** | Total number of amino acids in lysine desert region.  <br>**Only for Aligned** lysine desert type|

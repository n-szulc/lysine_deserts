

Files `ophistokonta_OGs.tsv.gz` and `ophistokonta_COG.tsv.gz` were downloaded from the eggNOG5 database and contain summary of Ophistokonta Orthologous Groups and COG their annotations, respectively.

---

Table `eukaryotes_vectors.tsv.gz` contains the following information:

| Column  | Description  |
|:--|:--|
| **Ophistokonta OG ID**  | eggNOG5 ID of given Orthologous Group (OG) from Ophistokonta|
| **Number of all MSA files**  | Number of all MSA files from OGs of a given eukaryotic family/order |
| **Number of selected MSA files**  |  Number of MSA files from OGs of a given eukaryotic family/order fulfilling conditions as described in par. 3 of `Download_data.ipynb` |
| **Fraction of selected MSA files** | Fraction of selected MSA files among all available MSA files from OGs of a given eukaryotic family/order |
| **Median of median lenghts of all MSA files** | Median of all median sequence lengths of all MSA files from OGs of a given eukaryotic family/order |
|**Median of median lenghts of selected MSA files** | Median of all median sequence lengths of selected MSA files fulfilling conditions as described in par. 3 of `Download_data.ipynb` from OGs of a given eukaryotic family/order |

---

This directory also contains subdirectories for each analyzed lysine desert length calculated based on  `eukaryotes_vectors.tsv.gz` , with information on given lysine desert presence in each row of the eukaryotic vectors. See `OGs_analysis/Pipeline.ipynb` for algorithm's details.

These tables contain the following information:

| Column  | Description  |
|:--|:--|
| **Total taxonomic groups number**  | Total number of selected eukaryotic groups present in the vector  |
| **Total MSA number**  |  Total number of MSA files in the vector |
|  **Ophistokonta COG** | COG annotation for Ophistokonta Orthologous Group (entire vector); note that individual MSA COG annotations may be diffrent from it  |
| ***TAXONOMIC GROUP* total MSA number**  | Total number of MSA files from *TAXONOMIC GROUP* in the vector  |
|***TAXONOMIC GROUP* lysine desert MSAs percentage** | Fraction of lysine desert containing MSA files among all MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* non-lysine desert MSAs percentage** | Fraction of non-lysine desert MSA files among all MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* lysine desert gene symbols** | Gene Symbols associated with lysine desert containing MSA files in the vector|
|***TAXONOMIC GROUP* non-lysine desert gene symbols** | Gene Symbols associated with non-lysine desert MSA files in the vector|
|***TAXONOMIC GROUP*  lysine desert MSA COG** | COG annotations of lysine desert MSA files from *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP*  non-lysine desert MSA COG** | COG annotations of non-lysine desert MSA files from *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* lysine desert MSAs with lysine cluster anywhere percentage** | Percentage of lysine desert with lysine cluster anywhere in sequence MSA files among all lysine desert MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* lysine desert MSAs with lysine cluster N-end percentage** | Percentage of lysine desert with lysine cluster at N-end MSA files among all lysine desert MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* lysine desert MSAs with lysine cluster C-end percentage** | Percentage of lysine desert with lysine cluster at C-end MSA files among all lysine desert MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* longest lysine-less regions medians among lysine desert MSAs** | Medians of longest lysine less regions in each lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* longest lysine-less regions medians among non-lysine desert MSAs** | Medians of longest lysine less regions in each non-lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* means of lysines per sequence in lysine desert MSAs** | Means of number of lysines per sequence in lysine desert MSA file from given *TAXONOMIC GROUP* in the vector |
|***TAXONOMIC GROUP* means of lysines per sequence in non-lysine desert MSAs** |Means of number of lysines per sequence in non-lysine desert MSA file from given *TAXONOMIC GROUP* in the vector |
|***TAXONOMIC GROUP* means of lysines fraction per sequence in lysine desert MSAs** | Means of fraction of lysines per sequence in lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* means of lysines fraction per sequence in non-lysine desert MSAs** |Means of fraction of lysines per sequence in non-lysine desert MSA file from given *TAXONOMIC GROUP* in the vector |
|***TAXONOMIC GROUP* means of arginines per sequence in lysine desert MSAs** |Means of number of aginines per sequence in lysine desert MSA file from given *TAXONOMIC GROUP* in the vector |
|***TAXONOMIC GROUP* means of arginines per sequence in non-lysine desert MSAs** | Means of number of aginines per sequence in non-lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* means of arginines fraction per sequence in lysine desert MSAs** | Means of fraction of aginines per sequence in lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* means of arginines fraction per sequence in non-lysine desert MSAs** |  Means of fraction of aginines per sequence in non-lysine desert MSA file from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* paths to lysine desert MSAs** | Paths to lysine desert MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* paths to non-lysine desert MSAs** | Paths to non-lysine desert MSA files from given *TAXONOMIC GROUP* in the vector|
|***TAXONOMIC GROUP* all MSAs sequence length medians** | Medians of MSA sequence length for all MSA files from given *TAXONOMIC GROUP* in the vector|

*TAXONOMIC GROUP* = *Saccharomycetaceae/Rhabditida/Drosophilidae/Rodentia/Hominidae*

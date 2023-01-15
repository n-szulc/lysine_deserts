Table `Table_summary_half_life_datasets.tsv` contains information about the number of proteins in all the analyzed half-life datasets after subsequent filtering steps.

The table is indexed by cell type.

It contains the following information:

| Column  | Description  |
|:--|:--|
|**Cell type**| Cell type|
|**Number of proteins**| Number of proteins in the initial half-life dataset for a given cell type|
|**Number of proteins mapped to the reference human proteme**| Number of proteins after mapping the half-life dataset on the reference human proteome|
|**Number of proteins used in the analysis**|Number of proteins, excluding sequences <150 aa, with the predicted number of TMH >2, and with outlier half-life values (from 0.01 and 0.99 quantile), which were used in analyzing correlation between length of a lysine-less region and half life|

---

Table `Table_summary_lysine_deserts_in_E3s.tsv` contains information about the number of E3 ligases with a given lysine desert while taking into account the type of E3 ligase.

The table is indexed by an investigated condition (given lysine desert and/or lysine cluster).

The columns display values for each investigated condition according to one of the four E3 ligases' type: HECT, RING, UBOX, or Other.

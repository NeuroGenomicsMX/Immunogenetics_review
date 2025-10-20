# About data

The data was downloading from GWAS catalog at Feb 12th, 2025. 

- [All studies v1.0.3.1](https://drive.google.com/file/d/1MkTNnks7sZ2ajqcqFFPVv9uxTvE1TQQD/view?usp=drive_link)
- [All ancestries v1.0.3.1](https://drive.google.com/file/d/1xD3agvwGcLefaLEtTlEzBwEpEZ_mcObg/view?usp=drive_link)
- [All associations v1.0.2](https://drive.google.com/file/d/1nHN4FhGwNiLhgyj8pkUOQQqcsqmqbCiQ/view?usp=drive_link)

## Data processing

To obtain [`Immune_Response_db.tsv.gz`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/data/Immune_Response_db.tsv.gz), we used the script [`P1_Data_preparation.qmd`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/P1_Data_preparation.qmd).

This script performs the following steps:

1. Loads and filters the three GWAS datasets listed above.
2. Selects associations relevant to [**immune response traits**](https://docs.google.com/spreadsheets/d/1qZhQbTgYk9l57-Xg9IkAKT106EGmaEQ6f9zqvxje-M4/edit?usp=sharing).
3. Annotates and compacts the results into a modular TSV format.
4. Compresses the output for downstream use in figure generation.

# Exploring genetic variations associated with the immune response in underrepresented populations

Data analysis performed for the "Exploring genetic variations associated with the immune response in underrepresented populations". 

### Authors

+ Hernández-Ledesma, Ana Laura (ALHL)<sub>1</sub> - email: annhled@gmail.com, [GitHub](https://github.com/annhled6), [ORCID](https://orcid.org/0000-0002-8819-7471)
+ Coss-Navarrete, Evelia Lorena (ELCN)<sub>1</sub> - email: ecossnav@gmail.com, [GitHub](https://github.com/EveliaCoss/), [WebPage](https://eveliacoss.github.io/), [ORCID](https://orcid.org/0000-0002-7087-2977)
+ Sevilla-Parra Grecia (GSP)<sub>1</sub> - [ORCID](https://orcid.org/0009-0002-6737-6873)
+ Bravo-García, María Fernanda (MFBG)<sub>1</sub> - [ORCID](https://orcid.org/0009-0003-0280-9006)
+ Schäfer, Alejandra (AS)<sub>1</sub> - [ORCID](https://orcid.org/0000-0002-2300-9230) 
+ Brunck, Marion E.G (MEGB)<sub>2</sub> - [ORCID](https://orcid.org/0000-0001-8994-8276) 
+ Medina-Rivera, Alejandra (AM)<sub>1</sub> - [ORCID](https://orcid.org/0000-0002-7912-2718)

*Affiliation*
<sub>1</sub>: Laboratorio Internacional de Investigación sobre el Genoma Humano (LIIGH), Universidad Nacional Autónoma de México (UNAM). Santiago de Querétaro, México. <sub>2</sub>: Instituto de Investigaciones Biomédicas,  Universidad Nacional Autónoma de México. Ciudad de México, México (UNAM).

### Citation

> Hernández-Ledesma, Ana Laura, et al. Año, revista. DOI

## Abstract

The immune system protects the body through tightly coordinated innate and adaptive responses shaped largely by an individual’s genetic background. Genetic variants associated with immune responses provide key pathways underlying disease susceptibility. Historically, the large majority of genomic studies have focused on European populations, potentially limiting the understanding of the relation between genetics and immune response in distinct ancestries. To assess this imbalance, we identified and characterized 206 studies from 370 recruitment sites worldwide that investigated immune-related traits in the GWAS catalog. European cohorts dominated the data, with minimal representation from African, Latin American and Native American, Oceanian, and Asian ancestries. This imbalance limits discovery of ancestry-specific biology, reduces the accuracy of risk prediction outside Europe, and limits clinical translation. Expanding ancestry diversity in genomic research is essential to fully characterize the genetic architecture of human immune traits, to ensure that discoveries in immunogenomics benefit all populations on Earth. 

## Pipeline 

All downstream analyses and figures were generated using the input file [`Immune_Response_db.tsv.gz`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/data/Immune_Response_db.tsv.gz), which compiles immune-related associations from the GWAS Catalog.

1. **Data and processing:** Data were downloaded from the GWAS Catalog (February 12th, 2025). We then selected **immune-related associations** and generated the file [`Immune_Response_db.tsv.gz`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/data/Immune_Response_db.tsv.gz) using the script [`P1_Data_preparation.qmd`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/P1_Data_preparation.qmd). For more details, see this extended [README].
2. **Global and temporal ancestry patterns:**We explored ancestry representation in immune-trait-related GWAS cohorts. We generated **Figure 1**, scripts and outputs are available in [`P2_Figure1.qmd`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/P2_Figure1.qmd).
3. **Trait and variant overview:** We characterized immune response-associated traits and their genetic context in non-European populations. We generated **Figure 2**, scripts and outputs are available in [`P3_Figure2.qmd`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/P3_Figure2.qmd).
4. **SNPs distribution across non-European populations:** We analyzed ancestry-specific immune-associated SNPs to identify patterns of genetic variation in non-European cohorts. We generated **Figure 3**, scripts and outputs are available in [`P4_Figure3.qmd`](https://github.com/NeuroGenomicsMX/Immunogenetics_review/blob/main/P4_Figure3.qmd).

## Acknowledgments

We thank the [GWAS Catalog](http://ebi.ac.uk/gwas/) team for providing open access to genetic association data. We are also grateful to our collaborators for their support throughout this project. This work was supported by Luis Aguilar, Alejandro León, and Jair Santiago García Sotelo from the Laboratorio Nacional de Visualización Científica Avanzada (LAVIS). We also thank Carina Uribe Díaz, Alejandra Castillo Carbajal, and Christian Molina Aguilar for their technical assistance.

## Contact

- Ana Hernandez (email: annhled@gmail.com, [GitHub](https://github.com/annhled6))
- Evelia Coss (email: ecossnav@gmail.com, [GitHub](https://github.com/EveliaCoss/), [WebPage](https://eveliacoss.github.io/))
- Alejandra Medina-Rivera (email: amedina@liigh.unam.mx, corresponding author contact information)

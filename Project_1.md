# Nextflow Pipeline for ONT Long Reads Metatrascriptomic data analysis

Metatranscriptomics aims to characterise target microbes functionally. Metatranscriptomics focuses on gene expression of microbes within natural environments, i.e., the metatranscriptome. This is an extension of shotgun metagenomics, which only focuses on identifying the microbes. The sample data used in this study are from the Black Soldier Fly (Hermetia illucens; BSF) larvae bred under different diets selected based on increasing lignocellulose content. These diets were: processed chicken feed (CF), chicken manure (CM), Brewer’s spent grain (BSG), and Water Hyacinth (WH). An additional diet Feed Mix (FM), consisting of the four diets in equal proportions, was also incorporated.

The different metatranscriptomes were sequenced using the PCR-cDNA approach on the ONT MinION platform. The work, using ONT,  aimed to identify and characterise lignocellulosic biomass-degrading microbes, but the mRNA enrichment protocol still retained some rRNAs, which are filtered out using SortMeRNA (Kopylova et al., 2012). The tool takes the corrected fastq files from the five metatranscriptomes, runs them against multiple rRNA databases, and sorts them into two separate files (the clean/ribodepleted fastq files and the rRNA fastq files). 

You are provided with scripts used to analyse the data. Your task is to:
1. Perform a literature search to identify any standardised metatranscriptomic workflow available.
2. Convert the scripts shared to Nextflow 
3. Expand the workflow to make use of containers and scale to the cloud

## Literature
1. Shakya, M., Lo, C. C., & Chain, P. S. G. (2019). Advances and challenges in metatranscriptomic analysis. Frontiers in Genetics, 10(SEP), 904. https://doi.org/10.3389/FGENE.2019.00904/BIBTEX
2. Sahlin, K., Sipos, B., James, P. L., & Medvedev, P. (2021). Error correction enables use of Oxford Nanopore technology for reference-free transcriptome analysis. Nature Communications, 12(1). https://doi.org/10.1038/S41467-020-20340-8
3. Joshua Batson, Gytis Dudas, Eric Haas-Stapleton, Amy L Kistler, Lucy M Li, Phoenix Logan, Kalani Ratnasiri, Hanna Retallack (2021) Single mosquito metatranscriptomics identifies vectors, emerging pathogens and reservoirs in one assay eLife 10:e68353 https://doi.org/10.7554/eLife.68353

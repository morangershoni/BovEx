# BovEx
# Pipeline to obtain and analyze  short reads to create database of short variants 
Large reference datasets of genetic variations from genome-scale sequencing technologies are key in interpreting identified variants, their functional impact, and their possible contribution to the expression of diseases and studied traits. To date, there is no such public database for genetic variation from genome-wide sequencing of broad cattle populations. To overcome this gap and enhance interpretation of bovine NGS-driven variant discovery, we obtained and analyzed raw data deposited in the SRA public repository. Short reads from 262 whole-exome sequencing samples of Bos Taurus were mapped to the Bos taurus ARS-UCD1.2 reference genome. The GATK best practice workflow was applied for variant calling. Comprehensive annotation of all recorded variants done by the Ensembl Variant Effect Predictor (VEP). We carried out an in-depth analysis of the population structure and identified the breeds comprising the database. The BovEx provides a comprehensively annotated dataset of more than 20 million short variants; ~2% are located within open reading frames, splice regions, and UTRs. More than 60 thousand of the variants are predicted deleterious. 

The pipeline file describing the required environment, the tools, and the arguments used to obtain short reads from the NCBI SRA repository, and the downstream analysis to create a database of short variants from bovine
 

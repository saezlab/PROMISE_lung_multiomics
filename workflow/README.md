This pipeline is for taxonomic profiling of metagenomics fastq files
Before you start, you have to prepare all the requirements. 
- Download the database for motus_v3 (db_mOTU)
- Download all the necessary files (human genomes) and specify exact location in workflow/config/config.yaml 
- Prepare the metadata and specify location, currently in input/metadata/clean
- Prepare your slurm and config files accordingly

To run the snakemake pipeline in bq_cluster
- go to workflow folder
- activate snakemake conda enviroment
- test dry run if it works and all the requirements are there by using **-n** parameter
- run for real **snakemake -s Snakefile --profile profile/slurm  --configfile config/config.yaml**
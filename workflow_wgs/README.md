download all the necessary human genomes and specify location in workflow/config/config.yaml 
Download the database for motus_v3 (db_mOTU)
go to workflow folder
conda activate snakemake
change the folder locations in the workflow/config/config.yaml file
test dry run if it works and which files will be generated
snakemake --use-conda -n

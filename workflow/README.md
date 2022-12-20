# to run Snakemake file

1. activate snakemake conda 
cd PATH for snakemake file
conda activate snakemake

2. test dry run if it works and which files will be generated
snakemake --use-conda -n

3. Install dependencies
snakemake --conda-create-envs-only --use-conda -c1

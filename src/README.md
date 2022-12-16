Data Loc://net/data.isilon/ag-halama/Level_4_Storage/Genecore_EMBL
user: bq_ekartal2
pwd: Q8ZPPMeRxy2Dqj

# Motus analysis
How to run

conda install -c bioconda motus

Clone run script
git clone https://git.embl.de/grp-bork/bork_it_software.git

cd bork_it_software/scripts

run the run_ngless.py with necessary parameters
run_ngless.py -h

python3 run_ngless.py -p Levade_2020_cholera -d /g/bork5/mocat/Levade_2020_cholera -a motus_2.5.0 -j 10 -m 16 -c 4 -s /g/bork5/mocat/Levade_2020_cholera/PRJNA608678

or

python run_ngless.py -p promise_lung_microbiome -d /g/bork5/mocat/environment/promise_lung_microbiome -a motus_3.0.1 -j 20 -m 16 -c 4 -s all.samples
output goes by default to /g/bork5/mocat/ngless-processing/

python run_ngless.py -p promise_lung_microbiome -d //net/data.isilon/ag-halama/Level_4_Storage/Genecore_EMBL -a motus_3.0.1 -j 20 -m 16 -c 4 -s all.samples
output goes by default to /g/bork5/mocat/ngless-processing/

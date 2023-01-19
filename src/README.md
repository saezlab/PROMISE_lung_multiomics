Data Loc://net/data.isilon/ag-halama/Level_4_Storage/Genecore_EMBL
user: bq_ekartal2
pwd: Q8ZPPMeRxy2Dqj

# to get the read counts per fastq file
for file in *.fastq; do wc -l $file; done
Obtained files from the rrnDB located at https://rrnDB.umms.med.umich.edu/static/download/

These files are from version 5.8

automated downlading tsv, fasta, NCBI.tsv, & RDP.tsv  with wget
wget --directory-prefix data/raw -nc https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8.tsv.zip
wget --directory-prefix data/raw -nc https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_16S_rRNA.fasta.zip
wget -P data/raw/ -nc https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip
wget -P data/raw/ -nc https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_pantaxa_stats_RDP.tsv.zip
unzip file with unzip
unzip -n -d data/raw/ data/raw/rrnDB-5.8.tsv.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_16S_rRNA.fasta.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_pantaxa_stats_RDP.tsv.zip

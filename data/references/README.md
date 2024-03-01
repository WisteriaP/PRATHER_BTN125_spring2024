Go to https://mothur.org/wiki/silva_reference_files/ and download Release 138’s “recreated SEED database”
Decompress file and move it to data/references/ directory

used wget, mkdir and tar to download and extract silva seed files
wget -nc -P data/references/ https://mothur.s3.us-east-2.amazonaws.com/wiki/silva.seed_v138_1.tgz
mkdir data/references/silva_seed/
tar xvzf data/references/silva.seed_v138_1.tgz -C data/references/silva_seed/

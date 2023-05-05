# GEN-8450-Final-Lab

#Download Human X chromosome data 
https://ftp.ensembl.org/pub/release-109/fasta/homo_sapiens/dna/Homo_sapiens.GRCh38.dna.chromosome.X.fa.gz

Download gene OPN1LW for red-green colorblindness
http://useast.ensembl.org/Homo_sapiens/Transcript/Summary?db=core;g=ENSG00000102076;r=X:154144243-154159032;t=ENST00000369951

#Activate gemprep for the lab
conda activate gemprep
git clone https://github.com/SystemsGenetics/GEMprep.git

grep Chromosome X | sort | unique > Xgenes.txt
grep OPN1LW | sort | unique > RGgenes.txt

#Compare the genes to see where the mutation occurs

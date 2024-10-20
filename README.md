This repo contains BLAST queries that can be run from the Linux terminal. Open the Linux terminal, then navigate to the file's directory. 
You can run the file with the following command:

bash ./perfect_hits <query_sequence.fasta> <subject_sequence.fasta> <blast_output.txt>

Make sure you install the required BLAST packages in your environment before running the above code. If you use conda, you can paste the below commands in your terminal to get the necessary packages:

conda create -n <your blast env\. name> -c bioconda blast
conda activate <your blast env\. name>

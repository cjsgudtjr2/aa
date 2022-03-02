https://blast.ncbi.nlm.nih.gov/Blast.cgi




# BLAST type

![blast type](https://user-images.githubusercontent.com/80435292/155930873-8042f9c6-e2ac-4014-8d68-c393e6c04942.png)

+ Nucleotide blast(Blstan)
  +compares nucleotide sequence databases with DNA sequences 
  
+ Protein blast(Blastp)
  + compares protein sequence database with amino acid sequence
  
+ Blastx
  + Convert the DNA input sequence into six frames and compare it with the protein sequence database.
  
+ Tblastn
  + Transform the DNA database into 6 frame and compare it with the protein sequence


------------------------
# BLAST

![blast2](https://user-images.githubusercontent.com/80435292/155930875-161351fe-d712-430c-80ee-1633de74b7a6.png)

+ Enter Query Sequence
  + Enter the query sequence in FASTA sequence

+ Choose Search Set
  + Select the database(usually use nr database)

+ Program Selection
  + Blastp
    + search similar sequences in the protein database
  + PSI-BLAST 
    + After finding the homologous sequence in the protein database, perform blast by repeating 𝑖 times based on the consensus sequence




----------------------------------

# BLAST Result


![blast3](https://user-images.githubusercontent.com/80435292/155930879-05dc116d-579c-418a-b278-d4c086bd30d1.png)

+ Check the similarity score and E-value for each alignments


![blast4](https://user-images.githubusercontent.com/80435292/155930880-4c9d5470-589e-4b45-89a6-07c470389950.png)


+ Query
  + An indication of the length below appears, and it is possible to roughly know the length of the query sequence input in this search and the similar area between the similar sequence

+ Alignments
  + The bars of several colors below indicate how long they are similar to the query sequence.


-------------------------------

# PSSM

![image](https://user-images.githubusercontent.com/80435292/156295511-a41bed37-cf89-450a-acf3-a4766d7d2ee3.png)

+ Can download PSSM file in asn file when run PSI-BLAST

![image](https://user-images.githubusercontent.com/80435292/156295545-407f68d6-6f54-47db-8946-4ee20010f930.png)

+psiblast –in_pssm <path to your checkpoint.asn> -db <any db> -num_iterations 1 -out_ascii_pssm <output file name>
![image](https://user-images.githubusercontent.com/80435292/156295556-eccbfcf8-9e62-452f-a3a2-bba8000b7e8b.png)


![image](https://user-images.githubusercontent.com/80435292/156295562-7b46ce68-19c4-4d5a-9fa9-58cca486cd3d.png)


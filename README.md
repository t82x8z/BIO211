java cBIO211 HOME ASSIGNMENT(Total of 100 points, 15% of final module marks)
Instructions:· If you have any questions regarding the techniques, please refer to practical slides. Everything required in this project has been fully covered with detailed instructions.· Make a screenshot of the key result(s). Do NOT copy everything to the report. Try to keep your results brief and concise, preferably no more than 300 words for each question (Hint: better include the explanation to the purpose and interpretations to results in your solution).· Clearly label each question and sub-question in your report.· Do NOT copy the entire result to your report. A screen shot of a small part of the key result is enough (1 page maximum for each question, including screen shot of result).· Submit your report directly to LMO in word format.
Task 1: Database search and download (10 points)1. Find the accession number (DNA sequence) of human haemoglobin A alpha chain and haemoglobin A beta chain in NCBI. (Hint: Restrict the search in human by defining the “organism” search field. See Lab1 notes Page 9.)2. Download the two sequences in FASTA format (you will need the sequences later).3. Try to blast human haemoglobin A alpha chain against human genome using NCBI blastn: http://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastnPAGE_TYPE=BlastSearchLINK_LOC=blasthome . Partially save the result with a screen shot, and give your explanation. (5 points)4. Try using human haemoglobin A beta chain for blast, save the screen shot of your result and explain. (5 points)
Task 2: Dotplot (20 points)1. Plot a dotplot of human haemoglobin A alpha chain self-comparison using dotmatcher tool with the default setting:2. Partially save the result and explain your finding. (5 points)3. Re-do the previous analysis with different settings:o Window size over which to test threshold: 15o Threshold :40Partially save the result and explain your finding. (5 points)4. Insert a block (80bp-100bp, using “Types of block mutations to perform. Insertions”) into the sequence of human haemoglobin A alpha chain with msbar tool, save the output sequence. (5 points)5. Compare the mutated sequence with the original sequence using a dotplot with dotmatcher tool. Partially save the result and explain your findings. (5 points)
Task 3: Pairwise alignments 1 (10 points)1. Align the original sequence of human haemoglobin A alpha chain with the mutated sequence you generated from Step 4 of Task 2. Using needle (global alignment). Partially save your result and explain the impact of the insertion in Step 4 of Task 2. (5 points)2. Using water tool for local alignment. Partially save your代 写BIO211 HOME ASSIGNMENTMatlab
代做程序编程语言 result and explain. (5 points)
Task 4: Pairwise alignments 2 (10 points)Align human haemoglobin A alpha chain with human haemoglobin A beta chain.1. Using needle tool for global alignment. Partially save your result and explain your findings. (5 points)2. Using water tool for local alignment. Partially save your result and explain your findings. (5 points)
Task 5: Multiple sequence alignment and phylogeny (20 points, 5 points each)1. Download the top 20 results of “Aquaporin protein” from NCBI Protein database: http://www.ncbi.nlm.nih.gov/protein/, save them in multi-fasta format. Perform. multiple sequence alignment using Tcoffee with default setting. Explain the result you get.2. Generate a phylogenetic tree from the multiple sequence alignment result (.aln) using Jalview: using method “Neighbor joining using BLOSUM62” (manually adjust the alignment if necessary). Plot the generated phylogenetic tree. Save it in Newick format. Briefly explain the results.3. Using different method to visualize the tree generated from previous step with iTOL (https://itol.embl.de/), save 2 different layouts (one rooted, and one un-rooted), and explain your result and the difference between them.4. Repeat step 2 to generate a phylogenetic tree using a different method “Average Distance using BLOSUM62”, compare the new tree with the one generated previously in step 2. Which method you think is more suitable? And please explain why. There is no standard answer, it is OK as long as the explanation makes sense.
Task 6: Secondary Structure Prediction (10 points, 5 points each)1. Predict the Secondary structure of the DESS_MYXXA protein (http://www.uniprot.org/uniprot/P02966 ) using Garnier (http://emboss.bioinformatics.nl). Explain your result.2. Compare this prediction with the record in Uniprot (http://www.uniprot.org/) and briefly explain your findings.
Task 7: 3D Structure Prediction (20 points, 10 points each)1. Use the SWISS-MODEL Workplace (https://www.ncbi.nlm.nih.gov/protein/209608/) to predict the 3D structure of the following 2 protein sequences:a. MyProtein with the Sequence:MANITVFYNEDFQGKQVDPAQMANFQNAAGKQVb. Q1D196: http://www.uniprot.org/uniprot/Q1D196Save these data and briefly explain what you find, including any error messages.2. Perform. a pairwise sequence alignment with “DESS_MYXXA” and “Q1D196”, and a pairwise sequence alignment with “DESS_MYXXA” and “MyProtein”, using the needle tool (http://emboss.bioinformatics.nl/).a. Explain the results from the alignments.b. Briefly explain why the alignment result might affect 3D protein structure prediction.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

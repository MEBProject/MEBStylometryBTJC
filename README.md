The project code and novels can be downloaded from 
https://github.com/MEBProject/MEBStylometryBTJC/tree/master

or cloned from 
https://github.com/MEBProject/MEBStylometryBTJC.git

Once downloaded you will need to install the package stylo within R packages.install('stylo')

The file classify.R can be run from the command line in linux using ./classify.R or the contents of this file can be pasted into your R environment.
Please note that this should be run with the sub-directories primary_set and secondary_set directly beneath your current working directory

The program produces several output files, the main one being final_results.txt which shows a list of the BTJC chapters and its most likely author.
There is also wordlist.txt, this gives the 5000 most frequent words across the corpus of which we're using the first 1000 words. Also included are the frequency distance tables for the Cosine distance between the novels, the main one being distance_table_1000mfw_0c.txt

The results from our analysis can be found in the file https://github.com/MEBProject/MEBStylometryBTJC/blob/master/Cosine-Distance-Table/MEB-Projectcosine_distance_table1000MFW.xlsx 

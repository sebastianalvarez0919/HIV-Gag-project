# HIV-Gag-project
Final Project for Bioinformatics, application of phylogeny tree and multiple sequence alignment viewer
HIV is a novel virus that has carried stigma around it since it was identified in the 1980s. Many people died due to the irrational fear that one could get infected purely by the virus tocuhing your skin.
However, the more scientists researched, the more complete picture we had for how it infected and could be potentially treated.
The Gag protein is one of three major coded proteins, it is also not targeted for Antiretroviral Therapy as much as the other two proteins. 
This study shows that there is plenty of diversification and unique lineages in Gag coding sequences based on conserved polymorphisms unique to their region of origin. Data was taken from studies in Thailand, Kenya and the USA.
Data was copied and pasted into a single UNIX file, which was used to created an alignment seqeunce file using mafft. The aligned file was uitlized in NCBI's Multiple Sequence Alignment viewer. The aligned sequence was also used to create a Newick format file, using iqtree, to use on R studio. the packages BiocManager, ape and ggplot were used to create the phylogeny.

# HIV-Gag-project
Final Project for Bioinformatics, application of phylogeny tree and multiple sequence alignment viewer
HIV is a novel virus that has carried stigma around it since it was identified in the 1980s. Many people died due to the irrational fear that one could get infected purely by the virus tocuhing your skin.
However, the more scientists researched, the more complete picture we had for how it infected and could be potentially treated.
The Gag protein is one of three major coded proteins, it is also not targeted for Antiretroviral Therapy as much as the other two proteins. 
This study shows that there is plenty of diversification and unique lineages in Gag coding sequences based on conserved polymorphisms unique to their region of origin. Data was taken from studies in Thailand, Kenya and the USA.
Data was copied and pasted into a single UNIX file, which was used to created an alignment seqeunce file using mafft. The aligned file was uitlized in NCBI's Multiple Sequence Alignment viewer. The aligned sequence was also used to create a Newick format file, using iqtree, to use on R studio. the packages BiocManager, ape and ggplot were used to create the phylogeny.


<img width="1117" alt="Screenshot 2023-11-27 at 7 08 08 PM" src="https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/a8e6f31b-0a69-4970-8da4-cc3446e4cf6d">

Figure 1: 
NCBI’s MSA viewer detailing the entire genome diversity for Gag complete cds throughout the three regions

<img width="1086" alt="Screenshot 2023-11-27 at 11 16 28 PM" src="https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/53cc80aa-a8b5-4864-ac9e-e06d3611fe28">

Table 1:
Phylogeny tree encompassing all 56 variants and outlier. Thai variants branched off earlier than the USA variants. There is an isolated Thai variant, JN704057.1, amongst the USA variants, indicating a different genetic makeup for the standalone Thai variant.

<img width="1412" alt="Screenshot 2023-11-27 at 7 09 36 PM" src="https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/cfb0d46c-9521-4303-96e1-b25fa35b8df0">

Figure 2: 
Conserved USA variants in aligned base pairs 1624 and 1628. The rest of the highlighted mutations were also conserved in varying levels within two other geographical regions.


<img width="1412" alt="Screenshot 2023-11-27 at 7 12 14 PM" src="https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/d65e740a-d2b5-4303-8846-3343a4fd5027">
Figure 3:
Conserved USA variants in bp 296 and 300. Non-highlighted sites show one of two highly conserved mutations throughout the 56 samples.

![Screenshot 2023-11-27 at 11 39 20 PM](https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/f51bc737-dcbd-4c43-ac26-019101ee7fe0)

Figure 4: 
Conserved mutation at bp 278 in Thai variants shown in NCBI’s MSA viewer.

![Screenshot 2023-11-27 at 11 40 32 PM](https://github.com/sebastianalvarez0919/HIV-Gag-project/assets/147643829/56defd77-a602-4a44-a4c8-0abb570c4ea1)

Figure 5: 
Conserved mutation at bp 819 in Thai variants shown in NCBI’s MSA viewer

All sources used in this project are saved in the below link: 

https://www.mybib.com/b/RX97NO 

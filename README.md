A Pedigree-Based Map of Recombination in the Domestic Dog Genome
=====================

This repository contains supporting data for:
* Campbell, CL, Bhérer, C, Morrow, BE, Boyko, AR, & Auton, A.
  A Pedigree-Based Map of Recombination in the Domestic Dog Genome.
  G3: GENES, GENOMES, GENETICS; November 1, 2016; vol. 6 no. 11 3517-3524;
  [doi:10.1534/g3.116.034678](https://doi.org/10.1534/g3.116.034678)

Crossover calls
---------------
 
+ Column descriptions for **dog_CO-calls.txt**
    - **childID** : identifier for child
    - **paternalID** : identifier for father
    - **maternalID** : identifier for mother
    - **recomb.type** : 0 for female transmissions, 1 for male
    - **chr** : chromsome in canFam3.1
    - **pos.lower** : lower bound of crossover in canFam3.1 coordinates
    - **pos** : upper bound of crossover in canFam3.1 coordinates
    - **pRecomb** : probability of recombination, given by duoHMM
    - **mID** : unique "meiosis ID" for each transmission in the format of "m\<parentID\>-\<childID\>"

Genetic maps
------------

+ Column descriptions for each genetic map within **dog_genetic_maps.tar.gz**
    - **chr** : chromosome in canFam3.1
    - **pos** : position in canFam3.1 coordinates
    - **rate** : recombination rate in cM/Mb
    - **cM** : cumulative map position in centiMorgans

Genotype data
------------

+ Genotype data, including pedigree information for 237 dogs is included in PLINK format within **dog_genotype_data.tar.gz**


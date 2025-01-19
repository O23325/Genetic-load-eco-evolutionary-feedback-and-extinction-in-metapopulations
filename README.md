## Genetic load, eco-evolutionary feedback and extinction in metapopulations




### Project Authors

| Name                       | Affiliation                                                                              | Contact                     |
|----------------------------|------------------------------------------------------------------------------------------|-----------------------------|
| Oluwafunmilola Olusanya    |                                                                                          | oluwafunmilola549@gmail.com |
| Ksenia Khudiakova          | Institute of Science and Technology, Austria, Am Campus 1, Klosterneuburg, 3400, Austria | kseniia.khudiakova@ist.ac.at|
| Himani Sachdeva            | Department of Mathematics, University of vienna, Vienna, 1090, Austria                   | himani.sachdeva@univie.ac.at|


### Project Abstract

Habitat fragmentation poses a significant risk to population survival, causing both demographic stochasticity and genetic drift within local populations to increase, thereby increasing genetic load. Higher load
causes population numbers to decline, which reduces the efficiency of selection and further increases load, resulting in a positive feedback which may drive entire populations to extinction. Here, we investigate this eco-evolutionary feedback in a metapopulation consisting of local demes connected via migration, with individuals subject to deleterious mutation at a large number of loci. We first analyse the determinants of load under soft selection, where population sizes are fixed, and then build upon this to understand hard selection, where population sizes and load co-evolve. We show that under soft selection, very little gene flow (less than one migrant per generation) is enough to prevent fixation of deleterious alleles. By contrast, much higher levels of migration are required to mitigate load and prevent extinction when selection is hard, with critical migration thresholds for metapopulation persistence increasing sharply as the genome-wide deleterious mutation rate becomes comparable to the baseline population growth rate. Moreover, critical migration thresholds are highest if deleterious mutations have intermediate selection coefficients, but lower if alleles are predominantly recessive rather than additive (due to more efficient purging of recessive load within local populations). Our analysis is based on a combination of analytical approximations and simulations, allowing for a more comprehensive understanding of the factors influencing load and extinction in fragmented populations.

<code style="color : blue"> This repository is the official implementation of the project described above.</code> 

### Layout

The repository is split into two main directories named Fortran and Mathemamtica. The Fortran directory houses codes run with Fortran and contains 7 subdirectories. Six of the subdirectories are named based on general parameter values used (for example, the directory named Ks10h002 contains results run with parameter values; per locus strength of selection scaled by the carrying capacity, $Ks = 10$ and dominance coefficient, $h = 0.02$). The last subdirectory called $\textit{differentK}$ contains results run with different values  of carrying capacity, $K$. 

Within the Fortran directory as well as in it's subdirectories are fortran simulations (.f files) named based on other specific parameters used for the run (for example, sim_noLDL6000h002Km10.f indicates a simulation run assuming no LD (i.e., no linkage disequilibrium) with parameter values; number of loci, $L = 6000$, dominance coefficient, $h = 0.02$ and the strength of migration scaled by the carrying capacity, $Km = 10$).  


The Mathematica directory houses a mathematica notebook named Manuscript.nb which consists of the Mathematica codes for the analytical work done in the project. 

### Software versions

* Mathematica version 12.1 or later
* GNU Fortran 14.1.0

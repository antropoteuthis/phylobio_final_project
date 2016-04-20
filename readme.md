- https://guides.github.com/features/mastering-markdown/
- The project must be entirely reproducible. 
- In addition to the results, the repository must include all the data (or links to data) and code needed to reproduce the results.

# Cophylogenetic analysis of hyperiid amphipods and their gelatinous planktonic hosts.

## Introduction and Goals

Hyperiid amphipods (Amphipoda:Peracarida:Eumalacostraca:Crustacea:Arthropoda) are a clade of marine crustaceans which evolved from an ancestral benthic existence, presumably attached to benthic flora and fauna, to a pelagic life style in the ocean midwaters (Laval, 1980). Several adaptations allowed them to survive in this hostile habitat, including remarkable eye architecture to see in the dim lit deep waters (Land, 1989), and body transparency to hide from the myriad of lurking predators (Johnsen, 2001). The pelagic realm extends for vast distances in 3 dimensions of liquid medium without physical interfaces such as the seafloor or the surface (Harbison, 1982). An interesting ecological adaptation of hyperiid amphipods is their association with large gelatinous planktonic animals. These hosts serve many functions to hyperiid amphipods. They serve as a substrate for them to latch on, as means of transport, as protection from predators, and as food for themselves or their progeny (Madin & Harbison, 1977). Indeed, the gelatinous hosts act a floating habitat and food source. A relatable analogy can be found in Roald Dahl's novel 'James and the Giant Peach' (Dahl, 1996).

The specificity of the interactions varies across families of hyperiid amphipods. Some are specialist parasitoids like <i>Phronima sedentaria</i> on salps (Laval, 1978). Other are more like generalist hitchhickers like <i>Hyperia medusarum</i> (Laval, 1980). The gelatinous zooplankton hosts of hyperiid amphipods present an outstanding phylogenetic diversity, including colonial radiolarians, ctenophores, hydromedusae, scyphomedusae, siphonophore colonies, salps, and doliolids. Hosts and amphipods are delicate creatures, and their association can be easily broken by stress or disturbance, such as a plankton net tow. Consequentially, in studies using traditional plankton collection methods, these relationships are overlooked. However, these interactions have been successfully described in detail by scientists in the last century, after the advent of SCUBA diving techniques, which allow the careful collection of intact specimens using jars (Haddock, 2004).


[Video of <i>Glossocephalus milne-edwardsii</i> on a ctenophore <i>Leucothea multicornis</i>.](http://cifonauta.cebimar.usp.br/video/182/)

The follwoing articles comprise a broad compendium of these studies:

[Madin LP, Harbison GR. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—I. Associations with Salpidae. Deep Sea Research. 1977 May 1;24(5):449IN1457-56IN4463.](http://www.sciencedirect.com/science/article/pii/0146629177904830)

[Harbison GR, Biggs DC, Madin LP. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—II. Associations with Cnidaria, Ctenophora and Radiolaria. Deep Sea Research. 1977 May 31;24(5):465-88.](http://www.sciencedirect.com/science/article/pii/0146629177904842)

[Laval PH. Hyperiid amphipods as crustacean parasitoids associated with gelatinous zooplankton. Oceanogr. Mar. Biol. Ann. Rev. 1980;18:11-56.](http://phlaval1.free.fr/ref/Laval-Oceanogr.Mar.Ann.Rev-1980-no18.pdf)

[de Lima MC, Valentin JL. New records of Amphipoda Hyperiidea in associations with gelatinous zooplankton. Hydrobiologia. 2001 Apr 1;448(1-3):229-35.](http://link.springer.com/article/10.1023/A:1017593120143)

[Gasca R, Haddock SH. Associations between gelatinous zooplankton and hyperiid amphipods (Crustacea: Peracarida) in the Gulf of California. InCoelenterate Biology 2003 2004 (pp. 529-535). Springer Netherlands.](https://www.researchgate.net/profile/Rebeca_Gasca/publication/226387403_Associations_between_gelatinous_zooplankton_and_hyperiid_amphipods_Crustacea_Peracarida_in_the_Gulf_of_California/links/53e255270cf216e8321a92e1.pdf)

[Gasca, R., E. Suárez-Morales, and S. H. D. Haddock. Symbiotic Associations between Crustaceans and Gelatinous Zooplankton in Deep and Surface Waters off California. Marine Biology 151 (2006): 233–42](http://download.springer.com/static/pdf/729/art%253A10.1007%252Fs00227-006-0478-y.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00227-006-0478-y&token2=exp=1454559034~acl=%2Fstatic%2Fpdf%2F729%2Fart%25253A10.1007%25252Fs00227-006-0478-y.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00227-006-0478-y*~hmac=dcf28826950c657e8db7fbadb4600ea7eb55751be7d830a11ae81cf8543ec993)

[Gasca R, Hoover R, Haddock SH. New symbiotic associations of hyperiid amphipods (Peracarida) with gelatinous zooplankton in deep waters off California. Journal of the Marine Biological Association of the United Kingdom. 2015 May 1;95(03):503-11.](http://journals.cambridge.org/abstract_S0025315414001416)

The goal of this project is to compare the evolutionary histories of hyperiid amphipods and their hosts in the ocean. To do so, I will build an association matrix from the literature above on interspecific interactions. In order to study the interactions from a phylogenetic perspective I will need a phylogeny for the hyperiid amphipods, and a phylogeny for gelatinous hosts. To do so, I will download the 18S gene sequences from NCBI Nucleotide GeneBank for the diversity of host and amphipod species and build two gene trees to serve as a proxy for each of the species phylogeny.

From these data sources, I plan to:

1) Test for phylogenetic signal in the association matrix.

2) Carry out a cophylogenetic analysis to measure congruence between the trees and identify host switching patterns or incomplete sorting events during the coevolution of parasitoids and hosts.

3) Plot the phylogenies together with the association network.

4)Identify the phylogeentic distribution of living habitat use by hyperiid amphipod, in a phylogenetic community ecology approach. Test for phylogenetic structure (clustering/overdispersion).

## Methods

Host and amphipod 18S fasta sequences were retrieved from NCBI Entrez.

The following taxa were included (and pruned out a posteriori) to increase the robustness of the analysis and reduce the effect of long branch attraction:

###Host 18S phylogeny:
Outgroup:
Euglena intermedia

Ingroups:
Rhizarians:
Globigerina bulloides
Spumellarian radiolarian (unidentified)
Choanoflagellates:
Salpingoeca rosetta
Sphaeroeca leprechaunica
Sponges:
Hippospongia lachne
Suberites ficus
Placozoan:
Trichoplax sp.
Other protostomes:
Maja brachydactyla
Helix aspersa
Other deuterostome:
Asterias forbesi

###Amphipod 18S phylogeny:
Outgroup:
Cyathura sp.
Idotea sp.

For both amphipods and hosts:
The MSA alignments were carried out using MAFFT (Method: L-INS-i, no additonal parameters).
To build the 18S phylogenies, I used RAxML with a GTR+Gamma DNA evolution model and 100 non-parametric bootstrap replicates:

raxml -T 8 -m GTRGAMMA -n EXThostML_boot100 -s host_ext_MSA.phy -p 12345 -f a -x 12345 -N 100

 and [RevBayes](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/ExtendedHosts/18S_GTRg.Rev) (see model specifications in the link). 

In both amphipods and hosts, there was a good agreement between RevBayes and RAxML trees. 

Figure 1. Host 18S GTR+Gamma RAxML tree. 100 non-parametric bootstrap replicates generated. Nodes labeled with bootstrap support values.

Figure 2. Hyperiid amphipod 18S GTR+Gamma bayesian (RevBayes) tree. Nodes labeled with bayesian posteriors.

Hyperiid amphipod bayesian GTR+Gamma tree shows good convergence in 2 independent MCMC runs (Posterior ESS: 1067, Likelihood ESS: 1040).

The ML tree was used for hosts, while the Bayesian tree was chosen for the amphipods.

For the analysis and figure creation in R I used the packages: 
ape, phytools, phangorn, adephylo, ggtree, dendextrend, picante, paco, and igraph.
[RScript link](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/associations.R)

Trees were pruned to contain only the tips for which I have association data for, and transformed into ultrametric using ape::chronos(). 

Host-amphipod cophylogenetic congruence (level of cospeciation) was tested using a Procrustean Application to Cophylogenetic Analysis paco::PACo(), and ParaFit global fit methods ape::parafit.

Phylogenetic community ecology methods used were:
Test for phylogenetic clustering picante::phylostruct(), and per habitat picante::psc().

## Results

###Phylogenetic analyses:

![Figure 1. Amphipod species 18S bayesian best tree under a GTR+Gamma DNA evolution model. Nodes labeled with bayesian posteriors.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/amphipodBayesianTre.png)
Figure 1. Amphipod species 18S bayesian best tree under a GTR+Gamma DNA evolution model. 

![Figure 2. Host species 18S RAxML maximum likelihood tree under a GTR+Gamma DNA evolution model. 100 non-parametric bootstrap replicates generated. Nodel labeled with bootstrap support values.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/hostMLtree.png)
Figure 2. Host species 18S RAxML maximum likelihood tree under a GTR+Gamma DNA evolution model.

![Figure 3.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/annotated_tree.png)
Figure 3. Host 18S tree with main clades collapsed and aligned with a picture of a representative association. Photographs by Steven Haddock and Jeff Molder.

###Association ecology:

![Figure 4.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/PS/AllSPP.png)
Figure 4. Complete association network for hyperiid amphipods and their described gelatinous hosts from the literature review.

![Figure 5.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/PS/phylospp_assoc.png)
Figure 5. Pruned association network for hyperiid amphipods and their described gelatinous hosts species included in both phylogenies.

![F8](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/amphipoddist.png)
Figure 8. Heatmap of the pairwise distances between amphipod species computed from matrix of common habitats(hosts).

![F9](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/amphipodMDS.png)
Figure 11. Multidimensional scaling plot for amphipod distance matrix used in Figure 9.

![F10](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/hostdist.png)
Figure 10. Heatmap of the pairwise distances between gelatinous host species computed from matrix of common inhabitant species (amphipods).

![F11](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/hostMDS.png)
Figure 11. Multidimensional scaling plot for host distance matrix used in Figure 10.

Host phylogeny:

After the removal of the non-host species,


Amphipod phylogeny:


###Cophylogenetic analysis

![Figure 12](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/cophylogeny.png)
Figure 12. Cophylogeny of amphipods and gelatinous hosts produced using ape::cophyloplot.

Global congruence (Parafit) between host and amphipod trees: 13.83, p-value=0.231. The trees are not significantly congruent. It is likely that the evolutionary histories of these groups were not coupled (not dominated by cospeciation events). However, there are a few possible causes that could obscure the cophylogenetic signal in the data:

1) The different phylogenetic scales comprised. The gelatinous zooplankton tree contains taxa across kingdoms of life, from radiolarians to chordates, while the amphipod tree contains species from a single order, with a much more recent common ancestor. Unlike in the case of Hyperiid amphipods (Browne, 2007) the MRCA of the hosts has probably had a very different ecology than the tip species, and there is no reason to believe the MRCAs of the main host clades (Urochordates, Ctenophores, Cnidarians...) had been pelagic, lest been associated with hyperiid amphipods at all.

2) The resolution of the the trees. 18S gene trees do not contain enough phylogenetic information to adequately resolve the true tree. Moreover, a single gene tree's evolutionary history may differ from the species tree due to incomplete lineage sorting among other causes (Maddison, 1997). There are clear topological diferences between my 18S amphipod tree and that of Hurt et al. 2013 that lead me to believe the 18S gene tree is not a sufficient estimator for this phylogeny.

3) Host switching and limited specificity. Not all hyperiid amphipods are obligate parasites/parasitoids of a narrow range of host taxa. Many, like Eupronoe minuta, dwell among a diversity of species. Host specificity varies greatly throughout the phylogeny (Figure 14) so there are reasons to believe host switching could have played a major role in shaping the cophylogeny.

![Figure 13](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/specificity.png)
Figure 13. Amphipod phylogeny showing a brownian motion reconstruction of host specifity (blue - generalist, red - specialist).

![Figure 14](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/popularity.png)
Figure 14. Gelatinous host phylogeny showing a brownian motion reconstruction of amphipod richness (blue - common target, red - rare target).

The PACo (Balbuena et al., 2013) analysis of phylogenetic structure detected a phylogenetically overdispersed pattern (Procrustes sum of squares = 9.19) in the associations data, accounting for both the host and amphipod phylogenies.

###Phylogenetic community ecology

The picante::phylostruct permutation test for phylogenetic signal in community composition (using the amphipod phylogeny and the hosts as communities) detected an overdispersed pattern (mean observed= -0.8222, expected null = -0.955), in agreement with the PACo analysis.

The mean value of the phylogenetic clustering analysis of amphipod species for all hosts was 0.9083, indicating again a slightly overdispersed structure. However the standard deviation (0.3953) was large. Some hosts (<i>Thalia democratica<i/> and <i>Iasis zonaria</i>) had a greatly overdispersed amphipod community, whilst others (<i>Cyclosalpa affinis, Eurhamphaea vexilligera</i>, and <i>Pterotrachea hippocampus<i/>) had a distinct phylogenetic clustering in their amphipod assemblage (Figure 15).

As we can see in Figure 14, thaliacean species harbor the richest assemblage of hyperiid amphipods. 


## Discussion

These results indicate...

The biggest difficulty in implementing these analyses was...

If I did these analyses again, I would...

## References

[Balbuena, Juan Antonio, Raúl Míguez-Lozano, and Isabel Blasco-Costa. "PACo: a novel procrustes application to cophylogenetic analysis." PloS one 8.4 (2013): e61048.](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0061048)

[Dahl, Roald. James and the giant peach: a children's story. Alfred A. Knopf Books for Young Readers, 1996.](http://reednovelstudies.org/downloads/James_and_The_Giant_Peach_Novel_Study_Preview.pdf)

[de Lima MC, Valentin JL. New records of Amphipoda Hyperiidea in associations with gelatinous zooplankton. Hydrobiologia. 2001 Apr 1;448(1-3):229-35.](http://link.springer.com/article/10.1023/A:1017593120143)

[Gasca R, Haddock SH. Associations between gelatinous zooplankton and hyperiid amphipods (Crustacea: Peracarida) in the Gulf of California. InCoelenterate Biology 2003 2004 (pp. 529-535). Springer Netherlands.](https://www.researchgate.net/profile/Rebeca_Gasca/publication/226387403_Associations_between_gelatinous_zooplankton_and_hyperiid_amphipods_Crustacea_Peracarida_in_the_Gulf_of_California/links/53e255270cf216e8321a92e1.pdf)

[Gasca R, Hoover R, Haddock SH. New symbiotic associations of hyperiid amphipods (Peracarida) with gelatinous zooplankton in deep waters off California. Journal of the Marine Biological Association of the United Kingdom. 2015 May 1;95(03):503-11.](http://journals.cambridge.org/abstract_S0025315414001416)

[Gasca, R., E. Suárez-Morales, and S. H. D. Haddock. Symbiotic Associations between Crustaceans and Gelatinous Zooplankton in Deep and Surface Waters off California. Marine Biology 151 (2006): 233–42](http://download.springer.com/static/pdf/729/art%253A10.1007%252Fs00227-006-0478-y.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00227-006-0478-y&token2=exp=1454559034~acl=%2Fstatic%2Fpdf%2F729%2Fart%25253A10.1007%25252Fs00227-006-0478-y.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00227-006-0478-y*~hmac=dcf28826950c657e8db7fbadb4600ea7eb55751be7d830a11ae81cf8543ec993)

[Haddock, Steven HD. "A golden age of gelata: past and future research on planktonic ctenophores and cnidarians." Coelenterate Biology 2003. Springer Netherlands, 2004. 549-556.](https://www.researchgate.net/profile/Steven_Haddock2/publication/226628084_A_golden_age_of_gelata_past_and_future_research_on_planktonic_ctenophores_and_cnidarians/links/5466abe50cf2397f7829de9f.pdf)

[Harbison GR, Biggs DC, Madin LP. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—II. Associations with Cnidaria, Ctenophora and Radiolaria. Deep Sea Research. 1977 May 31;24(5):465-88.](http://www.sciencedirect.com/science/article/pii/0146629177904842)

[Harbison, G. Richard. "The gelatinous inhabitants of the ocean interior." Oceanus 35.3 (1992): 18-23.](https://scholar.google.com/scholar?cluster=15510554334690779271&hl=en&as_sdt=5,40&sciodt=0,40)

[Hurt C, Haddock SH, Browne WE. Molecular phylogenetic evidence for the reorganization of the Hyperiid amphipods, a diverse group of pelagic crustaceans. Molecular phylogenetics and evolution. 2013 Apr 30;67(1):28-37.](http://www.sciencedirect.com/science/article/pii/S1055790313000031)

[Land, M. F. "The eyes of hyperiid amphipods: relations of optical structure to depth." Journal of Comparative Physiology A 164.6 (1989): 751-762.](http://link.springer.com/article/10.1007/BF00616747)

[Laval PH. Hyperiid amphipods as crustacean parasitoids associated with gelatinous zooplankton. Oceanogr. Mar. Biol. Ann. Rev. 1980;18:11-56.](http://phlaval1.free.fr/ref/Laval-Oceanogr.Mar.Ann.Rev-1980-no18.pdf)

[Laval, Philippe. "The barrel of the pelagic amphipod Phronima sedentaria (Forsk.)(Crustacea: Hyperiidea)." Journal of Experimental Marine Biology and Ecology 33.3 (1978): 187-211.](http://www.sciencedirect.com/science/article/pii/0022098178900084)

[Madin LP, Harbison GR. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—I. Associations with Salpidae. Deep Sea Research. 1977 May 1;24(5):449IN1457-56IN4463.](http://www.sciencedirect.com/science/article/pii/0146629177904830)





# Cophylogenetic analysis of hyperiid amphipods and their gelatinous planktonic hosts.

## Introduction and Goals

Hyperiid amphipods (Amphipoda:Peracarida:Eumalacostraca:Crustacea:Arthropoda) are a clade of marine crustaceans which evolved from an ancestral benthic existence, presumably attached to benthic flora and fauna, to a pelagic life style in the ocean midwaters (Laval, 1980). Several adaptations allowed them to survive in this hostile habitat, including remarkable eye architecture to see in the dim lit deep waters (Land, 1989), and body transparency to hide from the myriad of lurking predators (Johnsen, 2001). The pelagic realm extends for vast distances in 3 dimensions of liquid medium without physical interfaces such as the seafloor or the surface (Harbison, 1982). An interesting ecological adaptation of hyperiid amphipods is their association with large gelatinous planktonic animals. These hosts serve many functions to hyperiid amphipods. They serve as a substrate for them to latch on, as means of transport, as protection from predators, and as food for themselves or their progeny (Madin & Harbison, 1977). Indeed, the gelatinous hosts act a floating habitat and food source. A relatable analogy can be found in Roald Dahl's novel 'James and the Giant Peach' (Dahl, 1996).

[Video of <i>Glossocephalus milne-edwardsii</i> on a ctenophore <i>Leucothea multicornis</i>.](http://cifonauta.cebimar.usp.br/video/182/)

The specificity of the interactions varies across families of hyperiid amphipods. Some are specialist parasitoids like <i>Phronima sedentaria</i> on salps (Laval, 1978). Other are more like generalist hitchhickers like <i>Hyperia medusarum</i> (Laval, 1980). The gelatinous zooplankton hosts of hyperiid amphipods present an outstanding phylogenetic diversity, including colonial radiolarians, ctenophores, hydromedusae, scyphomedusae, siphonophore colonies, salps, and doliolids. Hosts and amphipods are delicate creatures, and their association can be easily broken by stress or disturbance, such as a plankton net tow. Consequentially, in studies using traditional plankton collection methods, these relationships are overlooked. However, these interactions have been successfully described in detail by scientists in the last century, after the advent of SCUBA diving techniques, which allow the careful collection of intact specimens using jars (Haddock, 2004).

The goal of this project is to compare the evolutionary histories of hyperiid amphipods and their hosts in the ocean. To do so, I will build an association matrix from the literature above on interspecific interactions. In order to study the interactions from a phylogenetic perspective I will need a phylogeny for the hyperiid amphipods, and a phylogeny for gelatinous hosts. To do so, I will download the 18S gene sequences from NCBI Nucleotide GeneBank for the diversity of host and amphipod species and build two gene trees to serve as a proxy for each of the species phylogeny.

###Specific goals:

1) Visualize the phylogenies together with the association network.

2) Carry out a cophylogenetic analysis to measure global congruence between the trees. 

3) Examine the evolution of host specificity in hyperiid amphipods, and colonization vulnerability in gelatinous hosts.

4) Identify phylogenetic patterns in the colonization of living-habitat by hyperiid amphipods, through a phylogenetic community ecology approach. Test for phylogenetic structure (clustering/overdispersion).

## Methods

### Association data:

Hyperiid amphipod - Gelatinous host associations (unquantified, recorded categorically as presence) were recorded from the literature review of the following studied:

[Madin LP, Harbison GR. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—I. Associations with Salpidae. Deep Sea Research. 1977 May 1;24(5):449IN1457-56IN4463.](http://www.sciencedirect.com/science/article/pii/0146629177904830)

[Harbison GR, Biggs DC, Madin LP. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—II. Associations with Cnidaria, Ctenophora and Radiolaria. Deep Sea Research. 1977 May 31;24(5):465-88.](http://www.sciencedirect.com/science/article/pii/0146629177904842)

[Laval PH. Hyperiid amphipods as crustacean parasitoids associated with gelatinous zooplankton. Oceanogr. Mar. Biol. Ann. Rev. 1980;18:11-56.](http://phlaval1.free.fr/ref/Laval-Oceanogr.Mar.Ann.Rev-1980-no18.pdf)

[de Lima MC, Valentin JL. New records of Amphipoda Hyperiidea in associations with gelatinous zooplankton. Hydrobiologia. 2001 Apr 1;448(1-3):229-35.](http://link.springer.com/article/10.1023/A:1017593120143)

[Gasca R, Haddock SH. Associations between gelatinous zooplankton and hyperiid amphipods (Crustacea: Peracarida) in the Gulf of California. InCoelenterate Biology 2003 2004 (pp. 529-535). Springer Netherlands.](https://www.researchgate.net/profile/Rebeca_Gasca/publication/226387403_Associations_between_gelatinous_zooplankton_and_hyperiid_amphipods_Crustacea_Peracarida_in_the_Gulf_of_California/links/53e255270cf216e8321a92e1.pdf)

[Gasca, R., E. Suárez-Morales, and S. H. D. Haddock. Symbiotic Associations between Crustaceans and Gelatinous Zooplankton in Deep and Surface Waters off California. Marine Biology 151 (2006): 233–42](http://download.springer.com/static/pdf/729/art%253A10.1007%252Fs00227-006-0478-y.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00227-006-0478-y&token2=exp=1454559034~acl=%2Fstatic%2Fpdf%2F729%2Fart%25253A10.1007%25252Fs00227-006-0478-y.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00227-006-0478-y*~hmac=dcf28826950c657e8db7fbadb4600ea7eb55751be7d830a11ae81cf8543ec993)

[Gasca R, Hoover R, Haddock SH. New symbiotic associations of hyperiid amphipods (Peracarida) with gelatinous zooplankton in deep waters off California. Journal of the Marine Biological Association of the United Kingdom. 2015 May 1;95(03):503-11.](http://journals.cambridge.org/abstract_S0025315414001416)

Most associations not resolved to the species level were discarded for this study.

[Associations file here.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/Associations.csv)

### Molecular data:

Host and amphipod 18S fasta sequences were retrieved from NCBI Batch Entrez using the GI numbers for each taxon sequence.

[Hosts sequences FASTA](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/ExtendedHosts/host_ext_oneline.fasta)

[Amphipods sequences FASTA](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/Amphipods/Interesting\ amphipods/datamphipod18S_oneline.fasta)

Additional taxa were included (and pruned out a posteriori) to increase the robustness of the analysis and reduce the effect of long branch attraction. The hyperiid amphipod tree showed a rogue taxon "*Hyperietta stephenseni*" which consistently appeared outside its genus clade and as sister group to all other species. Its 18S sequence, as annotated in NCBI differed much from every other in the alignment. This is possibly due to incorrect annotation or contamination (BLAST 2nd hit: *Epimeriella walkeri*, gammaridean amphipod -- 99% cover, E = 0.0). It has critical information as it is the only taxon for which I had available association data with radiolarians, so I could not simply remove it. Therefore, I applied a constraint (specified below) during the RAxML analysis to procrust its position in the tree, informed by alternative phylogenies (Hurt et al., 2013) and taxonomic information. *Lestrigonus schizogeneios* was also showing a similar behavior, but as it did not have critical ecological information, I decided to remove the taxon a posteriori.

For the sake of making good use of species-to-species association data for interesting species which do not have available annotated 18S sequence data, I used "sequence proxies". This artifact consists in using a sequence annotated as "Species sp." as a placeholder (or viceversa), assuming it would have an approximate phylogenetic placement to the morphospecies of interest.

<b>Host 18S taxa:</b>

**Outgroup:**
*Euglena intermedia*

**Ingroups:**
Rhizarians:
*Globigerina bulloides*. 
Spumellarian radiolarian (unidentified). 
Choanoflagellates:
*Salpingoeca rosetta*, 
*Sphaeroeca leprechaunica*. 
Sponges:
*Hippospongia lachne*, 
*Suberites ficus*. 
Placozoan:
*Trichoplax sp*. 
Other protostomes:
*Maja brachydactyla*, 
*Helix aspersa*. 
Other deuterostome:
*Asterias forbesi*.

**Sequence proxies:**
*Bolinopsis sp.* used as *Bolinopsis vitrea*.
*Pandea conica* used as *Pandea sp.*
*Solmissus sp.* as *Solmissus incissa*.
*Cavolinia sp.* as *Cavolinia longirostris*.
*Sphaerozoum punctatum* as *Sphaerozoum sp.*
*Collozoum inerme* as *Collozoum sp.*

<b>Amphipod 18S taxa:</b>

**Outgroups:**
*Cyathura carinata*, 
*Idotea baltica*.

**Ingroups:**
*Themisto abyssorum*, 
*Cystisoma pellucida*, 
*Hyperietta sibaginis*, 
*Hyperietta parviceps*, 
*Brachyscelus rapax*, 
*Phrosina semilunata*, 
*Rhabdosoma whitei*.

**Sequence proxies:** 
*Phronima sp.* used as *Phronima sedentaria*.
*Paraphronima sp.* used as *Paraphronima gracilis*.

### Phylogenetic analysis:

The MSA alignments were carried out using MAFFT (Method: L-INS-i, no additonal parameters). I used Mesquite 2.75 (Maddison, 1994) to output the alignments in Phylipp and Nexus formats for phylogenetic analysis.

To build the 18S phylogenies, I used RAxML with a GTR+Gamma DNA evolution model and 100 non-parametric bootstrap replicates:

raxml -T 8 -m GTRGAMMA -n ML_boot100 -s MSA.phy -p 12345 -f a -x 12345 -N 100

For hyperiid amphipods, I used the topological constraint parameter -g followed by a newick filename.

Constraint:
(*Hyperietta stephenseni, Hyperietta parviceps, Hyperietta sibaginis, Eupronoe minuta*);

 and [RevBayes](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/ExtendedHosts/18S_GTRg.Rev) GTR+Gamma (follow link for model specifications). 

In both amphipods and hosts, there was a good agreement between RevBayes and RAxML trees. However, only RAxML trees were used for the downstream analyses.

![FM1](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/raw_hostpleuro.png)
Supplementary figure 1. Host 18S GTR+Gamma ML (RAxML) tree. 100 non-parametric bootstrap replicates generated. Nodes labeled with bootstrap support values.

![FM2](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/constrainedRAW.png)
Supplementary figure 2. Hyperiid amphipod 18S GTR+Gamma ML (RAxML) tree. Nodes labeled with bootstrap support values.

### Eco-Evo analysis and visualization:

For the analysis and visualizations in R, I used the packages: 
ape, phytools, phangorn, adephylo, ggtree, dendextrend, picante, paco, and igraph.

[RScript link](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/associations.R)

Trees were pruned to contain only the tips for which I have association data for, and transformed into ultrametric using ape::chronos(). trees were also stored as phylogenetic distance matrices using cophenetic().

The association matrix obtained from the literature review was pruned to contain only species represented in the phylogenies used. Associations were visualized using igraph::tkplot(). Inter-host ecological distance matrix was calculated using picante::comdist(). Inter-amphipod ecological distance matrix was calculated using picante::species.dist(). Bipartite network analysis (Dormann et al., 2008) was carried out using bipartite::grouplevel().

Host-amphipod cophylogenetic congruence (level of cospeciation) was tested using ape::parafit (caillez corrected) and PACo (Balbuena et al., 2013), a Procrustean Application to Cophylogenetic Analysis paco::PACo() (r0 permutation method, cailliez correction method to allow non-euclidean phylogenetic distance matrices), and ParaFit global fit methods (Legendre et al., 2002) ape::parafit. Phylogenetic signal in generality and vulnerability traits calculated using Blomberg's K (Blomberg et al., 2003) with picante::Kcalc().
Cophylogeny plot was produced using ape::cophyloplot().

Phylogenetic community ecology methods used were:
Test for phylogenetic clustering picante::phylostruct(), and per habitat picante::psc() (Kembel and Steven, 2010).

## Results

### Phylogenetic analyses:

![F1](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/ultramphipod.png)
Figure 1. Ultrametric hyperiid amphipod species 18S GTR+Gamma ML tree. 

Amphipod phylogeny:

The amphipod 18S gene tree produced (Figure 1) accurately reconstructs the clades Physosomata, Physocephalata, Oxycephalidae, and Vibilidae.
It does not, however, reconstruct Platysceloidea nor Phronimoidea. These artifacts could be due to reduced taxon sampling and inability of the 18S gene to recapitulate the species tree.

![F2](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/ultram.png)
Figure 2. Ultrametric gelatinous zooplankton host species 18S GTR+Gamma ML tree.

Host phylogeny:

The 18S gene tree produced (Figure 2) accurately recognized the clades Radiozoa, Animalia, Ctenophora, Cnidaria, Bilateria, Salpida, Scyphozoa, Hydrozoa, and Siphonophorae. It does not resolve well the salp genus *Iasis* nor the internal ctenophore phylogeny. 

![Figure 3.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/annotated_tree.png)
Figure 3. Host 18S tree with main clades collapsed and aligned with a picture of a representative association. Photographs by Steven Haddock and Jeff Molder.

### Association ecology:

![Figure 4.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/PS/AllSPP.png)
Figure 4. Complete association network for hyperiid amphipods and their described gelatinous hosts from the literature review. Red: Hyperiid amphipods, Blue: Gelatinous hosts.

![Figure 5.](https://raw.githubusercontent.com/antropoteuthis/phylobio_final_project/master/screenshots/PS/phylospp_assoc.png)
Figure 5. Pruned association network for hyperiid amphipods and their described gelatinous hosts species included in both phylogenies. Red: Hyperiid amphipods, Blue: Gelatinous hosts.

The association data shows a complex interaction network (Figure 4), with generalists and specialists, that conserves a similar structure even with a constrained taxon sampling (Figure 5). 

![F8](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/amphidist1.png)
Figure 8. Heatmap of the pairwise distances between amphipod species computed from matrix of common habitats (hosts). Color scale: White: 0, Red: 1.

![F9](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/amphipodMDS.png)
Figure 11. Multidimensional scaling plot for amphipod distance matrix used in Figure 9.

Amphipods show interesting host sharing patterns (Figure 8) that reflect on the possible competitive interactions in environments where they may coexist, given limited host space. The species *Vibilia viatrix*, *Vibilia propinqua*, *Vibilia armata*, and *Phronima sedentaria* (well-known salp dwellers) show the greatest disparity in host association compared to the rest (Figure 9). These species also show a relatively large number of shared host species.

![F10](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/hostdist2.png)
Figure 10. Heatmap of the pairwise distances between gelatinous host species computed from matrix of common inhabitant species (amphipods). Color scale: White: 0, Red: 1.

![F11](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/hostMDS.png)
Figure 11. Multidimensional scaling plot for host distance matrix used in Figure 10.

Hosts show an even more complex association similarity matrix (Figure 10), proportional to the greater number of taxa included. The medusae *Pelagia noctiluca*, *Pandea conica*, and the salp *Salpa aspera* showed the most differentiated amphipod associations (Figure 11).

Bipartite network analysis (bipartite::grouplevel):

Hyperiid amphipods | Gelatinous hosts
------------------ | ------------------
Number of species |  
81 | 93
Mean links per species |  
4.549296 | 3.375587 
Mean shared species per species |  
0.07808642 | 0.08835905
Cluster coefficient |  
0.04891716 | 0.04167391 
Weighted cluster coefficient |  
0.2820054 | 0.3519910 
Niche overlap | 
0.02205080 | 0.03186021 
C-score |  
0.9565487 | 0.9437260 
Variance ratio |  
2.003145 | 1.141083 
Discrepancy |  
180 | 180 
Extinction slope |  
1.893307 | 1.849264 
Robustness |  
0.650927 | 0.6458423 
Functional complementarity |  
135.5728 | 141.5899 
Partner H' diversity |  
1.255991 | 1.022370 
Generality | Vulnerability 
4.549296 | 3.375587 

With a total number of links of 213, the overall discrepancy (number of missing links to a maximally connected network of 393 links - connectance: 0.5419) is 180 links. The average generality for the hyperiid amphipods included in this study is of 4-5 host species per predator, while the average vulnerability to amphipod colonization for these gelatinous animals is of 3-4 amphipod species per host. The Shannon-Weaver H' diversity index (Shannon and Weaver, 1949) of links per species is higher for hyperiid amphipods than for gelatinous hosts, although from binary data it is not informed by the frequency nor relative abundance of the associations. The robustness and extinction slope (resilience to extinction of associated taxa) for hyperiid amphipods came out higher than for gelatinous hosts, probably realted to the higher partner diversity. However, it does not make sense to talk about host robustness, as gelatinous zooplankton could probably survive just as well or better without hyperiid amphipods, given the nature of these interactions. The C-scores close to 1 indicates a signal of repulsion between species.

In order to assess the effect of my limited taxon sampling, I also carried out this analysis on the web pruned to contain only the species for which I have phylogenetic information:

Hyperiid amphipods | Gelatinous hosts
------------------ | ------------------
Number of species |  
19 | 30
Mean links per species |  
3.90566 | 2.471698 
Mean shared species per species |  
0.22807 | 0.177011
Cluster coefficient |  
0.130188 | 0.130089 
Weighted cluster coefficient |  
0.409972 | 0.540425 
Niche overlap | 
0.054903 | 0.081450 
C-score |  
0.898538 | 0.876197 
Variance ratio |  
1.283105 | 0.810557 
Discrepancy |  
35 | 35 
Extinction slope |  
2.178230 | 1.430246 
Robustness |  
0.678184 | 0.587607 
Functional complementarity |  
36.248722 | 33.370904 
Partner H' diversity |  
1.221812 | 0.742254 
Generality | Vulnerability 
3.905660 | 2.471698 

Reduced taxon sampling had a notable impact in reducing the number of links per species. However the ratio between each ecological group remains similar (complete: 1.3477, pruned: 1.580153), though slightly more extreme. Ratio of cluster coefficients remains constant, though the absolute value depends on the number of species. Apparent C-Score reduced, which could potentially bias our cophylogenetic analyses away from overdispersion. Variance ratio also reduced accordingly. Relative discrepancy to the maximum expected complexity is reduced (74/109) - thus apparent connectance increased to 0.679, together with an increase of the extinction slope for hyperiid amphipods, indicating a bias towards the overall robustness of hyperiid amphipods. Interestingly, the apparent Shannon-Weaver H' diversity index for partner associations did not change much for hyperiid amphipods, while it showed a visible decline for gelatinous hosts.

But, how far did sharing a common evolutionary history generate this association network?

### Cophylogenetic analysis:


![Figure 12](https://github.com/antropoteuthis/phylobio_final_project/raw/master/Good_Cophylo.png)
Figure 12. Cophylogeny of amphipods and gelatinous hosts produced using ape::cophyloplot.

The cophylogeny (Figure 12) shows the realtionship between common ancestry and association patterns. Global congruence (Parafit, Legendre et al., 2002) between host and amphipod trees: 31.16939 , p-value = 0.148. The trees show some congruence, not significant enough to support a shared macroevolutionary scenario. However, if branch lengths are all set to 1, the values obtained are ParaFitGlobal = 124916 , p-value = 0.067, supporting a significant cospeciative macroevolutionay scenario. This is a common sensitivity analysis for studying the evolution of continuous traits, as there is not much theoretical support to believe that the rate of molecular evolution in a random gene or genes would be correlated with phenotypic or ecological traits.

![Figure 13](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/good_specificity.png)
Figure 13. Hyperiid mphipod phylogeny showing a brownian motion reconstruction of host specifity (blue - generalist, red - specialist).

Figure 13 shows the evolution a key aspect of hyperiid amphipods' ecological role: host specificity. Host specificty could be used as a proxy of likelihood to interact as a parasite/parasitoid (with greater chance of a co-speciation history) rather than a generalist predator or hitchhiker. Blomberg's K for phylogenetic signal (Blomberg et al., 2003) in host specificity is medium, 0.3242. Interestingly, if we remove the effect of branch lengths, we get a Blomberg's K of 0.63277. Based on figure 13, The MRCA reconstruction would estimate it may have been associated with 2-3 host species.

![Figure 14](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/good_popularity.png)
Figure 14. Gelatinous host phylogeny showing a brownian motion reconstruction of associated amphipod richness - vulnerability (blue - common target, red - rare target).

From the other side of the story, Figure 14 shows the evolution of the suitability of gelatinous hosts to a broad spectrum of hyperiid amphipod species. Hosts that harbor more species, such as salps, are less likely to develop a coevolutionary armsrace against a particular amphipod species. Blomberg's K for phylogenetic signal in amphipod richness is low, 0.0689 (0.6877 with flat branch lengths, a tenfold increase). A MRCA reconstruction for this trait woul not make sense with these organisms, as their evolutionary history is very deep, well beyond the origin of hyperiid amphipods, and probably well beyond the current planktonic natural history on which they all these distant lineages converged.

The PACo (Balbuena et al., 2013) analysis of phylogenetic structure detected a slight but significant fit (Procrustes sum of squares = 17.08, goodness-of-fit: p-value = 0, number of permutations = 100), indicating the presence of co-divergence in shaping the topology of the cophylogeny.

But, which phylogeny has a stronger impact on the associations?

A mantel test of the phylogenetic distance matrices against the association-based distance matrices (as carried out in Bersier & Kehrli, 2008) for each group reveals:
Hyperiid amphipods: r = -0.127, p=0.861 (non-significant relationship).
Gelatinous zooplankton hosts: r = 0.0124, p=0.427 (non-significant relationship).

On a second approach to this question, I tried obtaining the mean Blomberg's K for each association in contrast to each of the phylogenies. The hyperiid amphipod phylogeny had a mean K of 0.5730 (SE: 0.5969), and the gelatinous host phylogeny had a mean K of 0.1583 (SE: 0.2901). The standard error values do not undermine the mean avlues, as the dispersion in this distribution is truncated to the left at 0. 

### Phylogenetic community ecology:

The picante::phylostruct permutation test for phylogenetic signal in community composition (using the amphipod phylogeny and the hosts as communities) detected an overdispersed pattern (mean observed= -1.15, expected null = -1.24), in other words, a phylogenetic repulsion signal.

![F15](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/clustering.png)
Figure 15. Phylogenetic overdispersion of amphipod species within each host.

The mean value of the phylogenetic clustering analysis of amphipod species for all hosts was 0.9083, indicating again a slightly overdispersed structure. However the standard deviation (0.3953) was large. Some hosts (<i>Thalia democratica</i> and <i>Iasis zonaria</i>) had a greatly overdispersed amphipod community, whilst others (<i>Cyclosalpa affinis, Eurhamphaea vexilligera</i>, and <i>Pterotrachea hippocampus</i>) had a distinct phylogenetic clustering in their amphipod assemblage (Figure 15).

In order to further study the effect of competition in hyperiid amphipod living habitat occupation, wrangled the data to obtain host-sharing links between amphipod species (Figure 8, 17). This can also be used for cophylogenetic analyses (Figure 16). 

![F16](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/competition_cophylo.png)
Figure 16. Cophylogeny of hyperiid amphipods with themselves, links showing one or more shared hosts.

![F17](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/competition_heatmap.png)
Figure 17. Competition probability heatmap of hyperiid amphipod species available in the phylogeny (Color scale: White: 0, Red: 1.). Dendrograms show host sharing similarities.

Parafit global fit values for this intra-clade cophylogeny (ParaFitGlobal = 2.738317 , p-value = 0.509) shows little significance. The species with more competition links with other species are *Lycaea pulex* and *Brachyscelus crusculum*. By mapping the number of hosts shared with other amphipods (reconstructed internally using Brownian motion) onto the hyperiid amphipod phylogeny (Figure 18), we observe a striking resemblance to Figure 13 on host specificity. A phylogenetic independent contrast linear regression analysis reveals a slope of 0.781 (p-value: 0.000213).

![F18](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/competition.png) 
Figure 18. Hyperiid amphipod phylogeny showing a Brownian motion reconstruction of host sharing with other amphipod species (blue - most competition, red - least competition).

Suspecting this may just be a tautological artifact, I normalized competition intensity by number of hosts interacting with each amphipod species (Figure 19). After running the same PIC linear regression, I found a non-significant relationship between host specificity and this competition intensity metric (p-value: 0.533).

![F19](https://github.com/antropoteuthis/phylobio_final_project/raw/master/screenshots/comp_norm.png)
Figure 19. Hyperiid amphipod phylogeny showing a Brownian motion reconstruction of corrected competition intensity with other amphipod species (blue - most competition, red - least competition).

## Discussion

### Phylogenetic analyses:

The trees reconstructed with 18S, though far from perfect, offered a good approximation of the species trees necessary for the downstream analyses. 
The host tree was very nicely resolved, with a very agreeable topology, with exception of the ctenophore internal phylogenetic relationships.
The amphipod tree failed to reconstruct many clades described in the recent phylogenetic literature. We may be able to conclude from these results that the 18S gene is a good estimator of phylogenetic relationships for deep relationships, but not so much for recent diversification histories. This is possibly due to its level of sequence conservatism due to its strict functional constraints.

### Association ecology:

The ecological analyses yielded fascinating results, describing the differences in association patterns from both the host and the hyperiid amphipod perspective. 

Host sharing patterns in the ecological association matrix for amphipods revealed which taxa may be more prone to competition in a host-limited environment.
The ecological similarity matrix built from the association data for hosts revealed great diversity in the number of amphipod species shared. An increased number of shared amphipod species has very different ecological implications. A gelatinous macroplankton community assemblage with many shared amphipod species would favor a greater amphipod diversity, greater chances of interspecies transfection of amphipods, and relief of predation (*sensu lato*) pressure on the host populations.

The bipartite network analysis showed species overdispersion in amphipods, possibly due to competition (Cavender-Bares et al., 2009). However, the variance ratios larger than 1 indicate positive agregation signal. I do not believe any of these indices as they are not informed by phylogenetic relationships. As niche theory would predict, "predators" have more prey connections than "prey" do (Williams and Martinez, 2000), which in a simplistic view of the ecology, it facilitates predators not running out of prey, and it relieves predation pressure from prey. A relatively low discrepancy value indicates that this network has a high connectance (or association complexity) (Blüthgen et al., 2006), this is also reflected in the robustness of amphipods to local extinction of host species. This could have been a selective pressure to increase overall generality in these species.

Reduced taxon sampling to conform to the phylogenetic data for further analyses had a noticeable effect in biasing the network topology towards a higher apparent connectance and a lower overall amphipod diversity per host. This can be translated as a lower apparent vulnerability. This could have repercussions downstream, such as blurring the phylogenetic signal of the associations to the host phylogeny, and biasing the phylogenetic distribution of vulnerability.

### Cophylogenetic analysis:

These results indicate that hyperiid amphipods and host have, to some extent, a shared evolutionary history.

Given the low global fit significance obtained, it is likely that the evolutionary histories of these groups were not completely coupled (not dominated by cospeciation events). However, there are a few possible causes that could obscure the cophylogenetic signal in the data:

1) The different phylogenetic scales comprised. The gelatinous zooplankton tree contains taxa across kingdoms of life, from radiolarians to chordates, while the amphipod tree contains species from a single suborder, with a much more recent common ancestor. Unlike in the case of Hyperiid amphipods (Browne, 2007) the MRCA of the hosts has probably had a very different ecology than the tip species, and there is no reason to believe the MRCAs of the main host clades (Urochordates, Ctenophores, Cnidarians...) had been pelagic, lest been associated with hyperiid amphipods at all.

2) The resolution of the the trees. 18S gene trees do not contain enough phylogenetic information to adequately resolve the true tree. Moreover, a single gene tree's evolutionary history may differ from the species tree due to incomplete lineage sorting among other causes (Maddison, 1997). There are clear topological diferences between my 18S amphipod tree and that of Hurt et al. 2013 that lead me to believe the 18S gene tree is not a sufficient estimator for this phylogeny.

3) Host switching and limited specificity. Not all hyperiid amphipods are obligate parasites/parasitoids of a narrow range of host taxa. Many, like *Eupronoe minuta*, dwell among a diversity of species. Host specificity varies greatly throughout the phylogeny (Figure 13) so there are reasons to believe host switching could have played a major role in shaping the cophylogeny.

Removing the effects of branch lengths had a huge impact on the results of the cophylogenetic analysis and also on the estimated phylogenetic signal in the ecological traits generality/specificity, availability/vulnerability. It is likely, and specially true for the host tree (which yielded a tenfold increase in phylogenetic signal), that the evolutionary distances between the organisms have a minor influence in determining the ecological relationships here studied. The astounding morphological and ecological adaptations that the representatives of the host lineages underwent to take on a pelagic existence (with some degree of convergence between them) probably has a much greater influence on the suitability of the host for hyperiid amphipod colonization. Nonetheless, my results show that the recent phylogenetic histories of these lineages do share some congruence with that of their associated amphipods, probably accounting for most of the global fit. 

Due to the small cophylogenetic signal, it was not possible to distinguish which phylogeny had stronger signal on the observed association data. While these cophylogenetic analyses indicate that phylogenetic signal exists in the association data with respect to both phylogenies, we cannot conclude that they are significantly different with the tests carried out here.

Only general cophylogenetic patterns were studied here. I did not attempt to reconstruct particular co-speciation or incomplete lineage sorting events in the cophylogeny. I believe the data used is not complete enough to have an accurate level of resolution for such questions. Considering the relatively recent placement of hyperiid amphipods within the host phylogeny, I assume the correlation between deep bipartitions in the host phylogeny and associations can not be due to cospeciation. Inheritance of common vulnerability traits within host lineages is probably responsible for their contribution to the cophylogenetic signal.

### Phylogenetic community ecology:

Phylogenetic community ecology analyses summarized the living habitat occupation by hyperiid amphipods. The generalized overdispersion pattern observed in the results may be accounting for competitive effects within each host. These negative ecological interactions could have shaped the host association process and the evolutionary history of hyperiid amphipods (Cavender-Bares et al., 2009). 

A cophylogenetic analysis of the competitive associations (potential, given biogeographical coexistance of the amphipod species and the shared host species) shows a non significant global fit, which rejects the hypothesis of hyperiid amphipods sharing host species having speciated together (Legendre et al. 2002). Without carrying out an independent contrast correlation and just by looking at figures 13 and 18, one can observe that the level of intraguild competition in hyperiid amphipod is likely to be correlated to host specificity, where generalist compete for more species of hosts than specialists do. However, when the competition intensity is normalized to generality, the pattern dissapears, as confirmed by the phylogenetic independent contrast analysis. It is visible that still many specialists like *Lanceola sayana* retain low competition intensities, but there is a lot of variability in the generalists unexplained by number of hosts alone.

As we can see in the figures, thaliacean species harbor the richest assemblage of hyperiid amphipods. Brownian motion reconstruction suggests the appearance of a key trait in their MRCA that rendered these animals widely favorable hosts for hyperiid amphipods. Generality and specificity in hyperiid amphipods evolved multiple times. Correlating these shifts with association type data would shed light on the evolution of this ecological trait.

## Personal discussion

### Difficulties:

The biggest difficulty in implementing these analyses was obtaining reliable trees. 18S gene trees hardly conform to the expected species trees. In the case of gelatinous hosts, adding ingroups and outgroups wass sufficient to fix the greatest anomalies. For example, in the hyperiid amphipod tree, I had to apply an external constraint to keep <i> Hyperietta stephenseni </i> from showing up as sistergroup to every other amphipod taxon due to incorrect annotation of the sequence in NCBI. 

Another difficulty I found was figuring out what tools to use for cophylogenetic analyses and where to find them. Cophylogenetics and phylogenetic community ecology are not very popular fields, so few educational resources and guides are available for newcomers and early career scientists. The cophylogenetic analyses carried out here are not the only tests that can be done. There are many others such as CopyCat (Meier-Kolthof et al., 2007), Jane (Conow et al., 2010), etcetera ... , each claiming to have a more accurate algorithm to compute congruence and infer co-evolutionary events. The interpreation of the statistics presented in these papers is not easy either. I feel that this field needs a thorough revision of the methods available, in combination with a revision of the theoretical background and assumptions. 

### Limitations:

Cophylogenetic analysis tools have been designed to study the coevolutionary scenario of closely associated parasites and hosts. In the case of hyperiid amphipods and gelatinous zooplankton, this is not exactly the case. There is a vast difference in the time scales of the phylogenies, and not all the assocations are specific. Moreover, in some of the associated species, neither the host or the amphipod needs the other partner to survive or reproduce. This defeats the purpose of traditional cophylogenetic analyses, and raises the need to develop new tools for the phylogenetic analysis of more general ecological associations such as competition, predation, and living habitat facilitation.

If I were to plan an ideal setting for these analyses, I would use concatenated sequence matrix trees with newly collected molecular data (such as transcriptomic data) for the species of interest. This way I would provide more accurate phylogenies upstream, which would greatly improve the overall accuracy of the analyses. In addition, I would put more care in making informed decisions on the alignment and tree search parameters used. I would explore the significance of each of the optional arguments, metrics, and correction methods for each one of the tools used.

Moreover, the association data used included only presence data (absences not reported), and had no information on the strength or frequency of the interaction, nor the type of interaction (parasitoidism, parasitism, predation, phoresis...). For future analyses, I would record a detailed matrix with these data to better understand these interaction types in the context of cophylogenetics. Ideally, I would develop novel tools to analyze the topology with more relaxed ecological assumptions and a simpler interpretation.

## References

[Balbuena, Juan Antonio, Raúl Míguez-Lozano, and Isabel Blasco-Costa. "PACo: a novel procrustes application to cophylogenetic analysis." PloS one 8.4 (2013): e61048.](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0061048)

[Bersier, Louis-Félix, and Patrik Kehrli. "The signature of phylogenetic constraints on food-web structure." Ecological Complexity 5.2 (2008): 132-139.](http://doc.rero.ch/record/9250/files/bersier_spc.pdf)

[Blomberg, Simon P., Theodore Garland, and Anthony R. Ives. "Testing for phylogenetic signal in comparative data: behavioral traits are more labile." Evolution 57.4 (2003): 717-745.](https://www.researchgate.net/profile/Theodore_Garland/publication/10731925_Blomberg_SP_Garland_T_Jr_Ives_AR_Testing_for_phylogenetic_signal_in_comparative_data_behavioral_traits_are_more_labile_Evolution_57_717-745/links/0912f502a5b821a033000000.pdf)

[Blüthgen, Nico, Florian Menzel, and Nils Blüthgen. "Measuring specialization in species interaction networks." BMC ecology 6.1 (2006): 1.](http://bmcecol.biomedcentral.com/articles/10.1186/1472-6785-6-9)

[Cavender‐Bares, Jeannine, et al. "The merging of community ecology and phylogenetic biology." Ecology letters 12.7 (2009): 693-715.](http://ibdev.berkeley.edu/labs/fine/Site/publications_files/cavender-bares_etal2009.pdf)

[Conow, Chris, et al. "Jane: a new tool for the cophylogeny reconstruction problem." Algorithms for Molecular Biology 5.1 (2010): 1.](http://www.biomedcentral.com/1748-7188/5/16)

[Dahl, Roald. James and the giant peach: a children's story. Alfred A. Knopf Books for Young Readers, 1996.](http://reednovelstudies.org/downloads/James_and_The_Giant_Peach_Novel_Study_Preview.pdf)

[de Lima MC, Valentin JL. New records of Amphipoda Hyperiidea in associations with gelatinous zooplankton. Hydrobiologia. 2001 Apr 1;448(1-3):229-35.](http://link.springer.com/article/10.1023/A:1017593120143)

[Dormann, Carsten F., Bernd Gruber, and Jochen Fründ. "Introducing the bipartite package: analysing ecological networks." interaction 1 (2008): 0-2413793.](http://www.uni-goettingen.de/de/document/download/96729eb9d30a6f2dc4403df15854305c.pdf/Rnews2008,8_8-11_open.pdf)

[Gasca R, Haddock SH. Associations between gelatinous zooplankton and hyperiid amphipods (Crustacea: Peracarida) in the Gulf of California. InCoelenterate Biology 2003 2004 (pp. 529-535). Springer Netherlands.](https://www.researchgate.net/profile/Rebeca_Gasca/publication/226387403_Associations_between_gelatinous_zooplankton_and_hyperiid_amphipods_Crustacea_Peracarida_in_the_Gulf_of_California/links/53e255270cf216e8321a92e1.pdf)

[Gasca R, Hoover R, Haddock SH. New symbiotic associations of hyperiid amphipods (Peracarida) with gelatinous zooplankton in deep waters off California. Journal of the Marine Biological Association of the United Kingdom. 2015 May 1;95(03):503-11.](http://journals.cambridge.org/abstract_S0025315414001416)

[Gasca, R., E. Suárez-Morales, and S. H. D. Haddock. Symbiotic Associations between Crustaceans and Gelatinous Zooplankton in Deep and Surface Waters off California. Marine Biology 151 (2006): 233–42](http://download.springer.com/static/pdf/729/art%253A10.1007%252Fs00227-006-0478-y.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00227-006-0478-y&token2=exp=1454559034~acl=%2Fstatic%2Fpdf%2F729%2Fart%25253A10.1007%25252Fs00227-006-0478-y.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00227-006-0478-y*~hmac=dcf28826950c657e8db7fbadb4600ea7eb55751be7d830a11ae81cf8543ec993)

[Haddock, Steven HD. "A golden age of gelata: past and future research on planktonic ctenophores and cnidarians." Coelenterate Biology 2003. Springer Netherlands, 2004. 549-556.](https://www.researchgate.net/profile/Steven_Haddock2/publication/226628084_A_golden_age_of_gelata_past_and_future_research_on_planktonic_ctenophores_and_cnidarians/links/5466abe50cf2397f7829de9f.pdf)

[Harbison GR, Biggs DC, Madin LP. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—II. Associations with Cnidaria, Ctenophora and Radiolaria. Deep Sea Research. 1977 May 31;24(5):465-88.](http://www.sciencedirect.com/science/article/pii/0146629177904842)

[Harbison, G. Richard. "The gelatinous inhabitants of the ocean interior." Oceanus 35.3 (1992): 18-23.](https://scholar.google.com/scholar?cluster=15510554334690779271&hl=en&as_sdt=5,40&sciodt=0,40)

[Hurt C, Haddock SH, Browne WE. Molecular phylogenetic evidence for the reorganization of the Hyperiid amphipods, a diverse group of pelagic crustaceans. Molecular phylogenetics and evolution. 2013 Apr 30;67(1):28-37.](http://www.sciencedirect.com/science/article/pii/S1055790313000031)

[Kembel, Steven W., et al. "Picante: R tools for integrating phylogenies and ecology." Bioinformatics 26.11 (2010): 1463-1464.](http://bioinformatics.oxfordjournals.org/content/26/11/1463.full)

[Land, M. F. "The eyes of hyperiid amphipods: relations of optical structure to depth." Journal of Comparative Physiology A 164.6 (1989): 751-762.](http://link.springer.com/article/10.1007/BF00616747)

[Laval PH. Hyperiid amphipods as crustacean parasitoids associated with gelatinous zooplankton. Oceanogr. Mar. Biol. Ann. Rev. 1980;18:11-56.](http://phlaval1.free.fr/ref/Laval-Oceanogr.Mar.Ann.Rev-1980-no18.pdf)

[Laval, Philippe. "The barrel of the pelagic amphipod Phronima sedentaria (Forsk.)(Crustacea: Hyperiidea)." Journal of Experimental Marine Biology and Ecology 33.3 (1978): 187-211.](http://www.sciencedirect.com/science/article/pii/0022098178900084)

[Legendre, Pierre, Yves Desdevises, and Eric Bazin. "A statistical test for host–parasite coevolution." Systematic biology 51.2 (2002): 217-234.](http://adn.biol.umontreal.ca/~numericalecology/Reprints/ParaFit_paper.pdf)

[Maddison, Wayne P. "Gene trees in species trees." Systematic biology 46.3 (1997): 523-536.](http://www.markolabhawaii.org/Marko_Lab_at_UH_Manoa/ZOOL_719_-_Readings_files/Maddison%201997.pdf)

[Madin LP, Harbison GR. The associations of Amphipoda Hyperiidea with gelatinous zooplankton—I. Associations with Salpidae. Deep Sea Research. 1977 May 1;24(5):449IN1457-56IN4463.](http://www.sciencedirect.com/science/article/pii/0146629177904830)

[Meier-Kolthoff, Jan P., et al. "COPYCAT: cophylogenetic analysis tool." Bioinformatics 23.7 (2007): 898-900.](http://bioinformatics.oxfordjournals.org/content/23/7/898.long)

[Shannon, Claude E., and Warren Weaver. "The mathematical theory of communication (Urbana, IL." (1949).](https://books.google.com/books?hl=en&lr=&id=IZ77BwAAQBAJ&oi=fnd&pg=PP1&dq=Shannon,+Weaver.+1949.+The+mathematical+theory+of+communicatio&ots=hkkwdVuQ_t&sig=1dRJDJuTuLM0HmeW9iEy63ax3MQ)

[Williams, Richard J., and Neo D. Martinez. "Simple rules yield complex food webs." Nature 404.6774 (2000): 180-183.](http://www.nature.com/nature/journal/v404/n6774/full/404180a0.html)





<div align="center">

# **Disease Project: Ornithine aminotransferase deficency**
#### Clara Jiménez, Ana Sánchez, Veronica Wangchen
#### FIB, UPC, Barcelona, Spain

</div>

<div align="justify">

## **Abstract**

Ornithine aminotransferase (OAT) is a mitochondrial enzyme involved in amino acid metabolism. Deficiency of this enzyme, caused by pathogenic variants in both copies of the OAT gene, leads to gyrate atrophy of the choroid and retina (GACR), a rare inherited disease characterised by progressive vision loss. This study investigated the molecular consequences of the Arg180Thr variant and explored the evolutionary conservation of OAT through bioinformatics analyses of nucleotide sequences, protein sequences and three-dimensional structures.

BLAST searches and sequence alignments were used to examine the human wild-type and mutant sequences and compare OAT homologues from Rattus norvegicus, Pongo abelii and Toxoplasma gondii. The Arg180Thr variant was identified as a missense substitution affecting amino acid 180. Structural comparison between the human wild-type and mutant proteins revealed minimal backbone displacement, indicating that the mutation does not substantially alter the overall protein fold. However, the substitution of arginine with threonine changes the chemical properties and size of the side chain, potentially disrupting interactions involved in substrate binding and catalytic specificity. Comparisons across species revealed greater sequence conservation between human OAT and Pongo abelii, whereas the comparison with T. gondii showed 51.2% sequence identity and 70.0% physicochemical similarity. Despite these sequence differences, their superimposed structures presented a global RMSD of 1.33 Å, indicating considerable structural similarity.

Overall, the findings suggest that the Arg180Thr variant may impair OAT function primarily through local chemical and interaction changes rather than major alterations to its three-dimensional structure. The comparative analyses also highlight the evolutionary conservation of OAT structure despite differences in amino acid sequences.

## **Keywords**

OAT, gyrate atrophy, OAT deficiency, _Toxoplasma gondii_, _Rattus norvegicus_, Arg180Thr variant, molecular basis of disease

## **Background**
This study aims to investigate the molecular basis of gyrate atrophy associated with the OAT gene, focusing on the Arg180Thr variant. Through bioinformatics analyses, the study examines the genetic and protein sequence differences between the reference and disease-associated states, explores the potential structural and functional consequences of the variant, and compares OAT across humans and other selected species to identify conserved features and assess their possible biological significance. Finally, these analyses aim to explain how changes in the OAT gene and its encoded protein may contribute to the development of the disease and affect normal biological function.

Human Ornithine Aminotransferase (hOAT), otherwise known as ornithine δ-aminotransferase (δ-OAT), is a mitochondrial enzyme involved in amino acid metabolism,  found mostly concentrated in the liver, intestines, kidneys and retina. In most tissues, OAT  catalyses the conversion of ornithine and α-ketoglutarate into glutamate-5-semialdehyde (GSA) and glutamate, maintaining the ornithine level in mitochondria stable (Sun 2017, Floriani 2026).
The reaction itself depends on pyridoxal 5'-phosphate (PLP) to act as its cofactor. Just like any other PLP dependent molecule, δ-OAT undergoes two half-reactions. For the first half, a PLP binds to each of the three monomers from OAT, forming an aldimine bridge, and when the reaction goes through the catalysis, a proton from the δ-carbon from ornithine transfers to the C4’ carbon of PLP, which modifies the aldimine between PLP and L-ornithine into an aldimine between pyridoxamine-5’-phosphate (PMP) and l-glutamate-γ-semialdehyde. Consequently, a water molecule breaks the bridge, and since PMP and GSA are unstable on their own, they fuse together and form a ring. Finally, 2-oxoglutarate enters the reaction, beginning the second half-reaction. Then, PMP gives up an amino acid, turning this last molecule into L-glutamate. This allows PMP to return to its previous PLP state and restart the catalytic activity for ornithine (Shen 1998).
Gyrate atrophy of the choroid and retina (GACR), also known as OAT deficiency, is a rare disease inherited in an autosomal recessive manner. This inheritance prevents the enzyme from working properly, and hence, it results in hyperornithinaemia. Although the OAT protein functions in mitochondria, the OAT gene is located on an autosome rather than in mitochondrial DNA. Therefore, the disease does not follow maternal mitochondrial inheritance. 

According to Palmer et al. (2023), the median age at diagnosis among the 18 patients included in their study was eight years. Common initial manifestations include myopia and night vision problems. As the disease progresses, patients may develop a gradual loss of peripheral visual field, which can eventually lead to severe visual impairment.
Despite ornithine being highly present in the process of the urea cycle, there is little evidence of it having an effect on the retinal abnormalities present in GACR. The urea cycle has as its main objective to convert ammonia, a toxic chemical formed by protein catabolism, into urea waste. The process starts in the main liver cells, the hepatocytes. Ammonia and bicarbonate are converted into carbamoyl phosphate through carbamoyl phosphate synthetase 1 (CPS1). Then, carbamoyl phosphate binds to L-ornithine via ornithine transcarbamylase to form citrulline, which is transported to the cytosol and eventually gets broken down into arginine, which is converted into urea and ornithine by arginase. Therefore, as mentioned previously, there is hardly any correlation between the OAT deficiency and the urea cycle. Furthermore, the reaction that acts as a limitant and determines the speed of the overall system is the conversion of NH₃ and bicarbonate into carbamoyl phosphate with CPS1, which indicates again that the excessively high concentrations of ornithine in the blood that brings about GACR has nothing to do with the urea cycle.
Currently, there is no definitive cure for GACR. However, dietary interventions aimed at reducing plasma ornithine levels may help manage the condition and potentially slow disease progression.

The OAT gene encodes ornithine aminotransferase, and variants affecting both copies of the gene can impair enzyme function and cause GACR. During gene expression, DNA is transcribed into RNA, which is processed to produce messenger RNA (mRNA). Alternative splicing can generate different transcripts from the same gene, potentially encoding different protein isoforms. Genetic variants can also affect the resulting protein: missense variants replace one amino acid with another, whereas nonsense variants introduce a premature stop codon. Understanding the relationship between the OAT gene, its transcripts and the encoded protein is therefore essential for selecting an appropriate reference sequence and investigating the potential consequences of the Arg180Thr variant.

Comparing OAT sequences across species helps identify evolutionarily conserved regions and amino acid residues that may be important for protein function. This study includes Rattus norvegicus and Toxoplasma gondii as homologues, while Pongo abelii was added because of its closer evolutionary relationship to humans and the substantial sequence differences observed between human OAT and T. gondii. These comparisons provide an evolutionary context for assessing sequence conservation and determining whether the residue affected by Arg180Thr is conserved across species. Nevertheless, sequence conservation alone cannot establish the functional effect of a mutation or demonstrate that the same disease occurs in other organisms.

A protein's three-dimensional structure reveals the spatial arrangement of its amino acids and can help explain how sequence changes may affect its stability or function. Examining the position of a specific residue within OAT can therefore provide insight into the potential consequences of a mutation. Comparing human OAT with homologues from other organisms also helps identify conserved structural features and differences between species. In this study, the structure of T. gondii OAT was compared with human OAT to investigate similarities and differences in their three-dimensional organisation, although structural analysis alone cannot confirm changes in enzymatic activity.

## **Results**

### _Genomics and proteomics_
Because the studied wild type sequence exhibits ten different isoforms, a search was conducted so as to determine whether the first isoform had the mutation of interest. This analysis confirmed that the mutation was present in the isoform, and thus, it was selected for the study. The CDS for said isoform has the gene located in the locus 10q26.13, found in the chromosome 10. Additionally, it contains 13 exons, and it is expressed in tissues such as the intestines, although it can also be found in 208 other cell types or tissues throughout adrenal, lung, stomach and even heart tissues. As for the mutant CDS sequence, it had a query coverage of 100%, a 0.0 E value and a 99.92% identity to the same isoform. 

Regarding the protein’s wild type, there was only one difference; only one isoform matched the given FASTA file at 100%, which was the variant 1. The search for the mutant protein sequence resulted in the same WT protein sequence, at a query coverage, E value and identity percentage of 100%, 0.0, and 99.77% respectively.

Lastly, each WT sequence was aligned to its corresponding mutation. For the nucleotide sequence mutated variant, it was revealed that there is a missense mutation in locus 539 (C>G). Concerning the comparison between the WT protein sequence and the mutated variant, there was a mutation in the amino-acid found in position 180, which is an threonin (T) instead of an arginine (R).

###  _Homologs_
When working with the sequence alignments of the three original species, which were Homo sapiens, Toxoplasma gondii and Rattus norvegicus, the last two being the homologs, it became obvious that the differences among their protein sequences were abysmal, with the exception of Arg180, which is conserved across H. sapiens and T.gondii. The longest conserved regions across the three protein sequences are formed by 7 amino-acids. This might not be considered a high conservation but, the three species are too different among them to have any longer coincidental regions. There are only four amino-acids the mutation of which is the same in both Toxoplasma gondii and Rattus norvegicus. 

Also, there are very few sequence positions with variants across the three species. Only four amino-acids the mutation of which is the same in both Toxoplasma gondii and Rattus norvegicus. Furthermore, some regions are more conserved than others. For instance, both the Query range 4: 181 to 240  and the Query range 5: 241 to 300 have 39 amino-acids conserved. However, the Query range 1: 1 to 60 and the Query range 8: 421 to 439 have 7 and 5 amino-acids conserved respectively. 

The multiple sequence alignment results showed that the addition of _Pongo abelii_ to the comparison with human OAT and _Rattus norvegicus_ facilitated the identification of highly conserved regions in both nucleotide and protein sequences.

The nucleotide alignment revealed three highly conserved regions between human OAT and P. abelii and R. norvegicus: positions 901–960 (query 16), with one and four differences, respectively; positions 361–420 (query 7), identical to P. abelii and with five differences in R. norvegicus; and positions 121–180 (query 3), with one and six differences, respectively.

Furthermore, in several positions, a substitution occurred in both species at the same time, and in most of these cases the substitution was in the same nucleotide (for instance, at position 606, where a guanine is changed to an adenine in both the orangutan and the rat).

The protein alignment identified three highly conserved regions: positions 102–166 (queries 2 and 3), identical in P. abelii and with only two differences in R. norvegicus; positions 241–300 (query 5), with one and two differences, respectively; and positions 181–240 (query 4), identical in P. abelii and with four differences in R. norvegicus.
  
Additionally, there were four positions where both species had variants (the last three also shared with _T. gondii_): 2, 180, 353 and 389.

### _Structure_

It was determined that the experimental data snapshot for the OAT wild type (WT) protein was obtained through X-Ray Diffraction, exhibiting an image resolution of 1.93Å. From what was observable, the studied protein is a polypeptide formed by 439 amino-acids. At first glance it is discernible that the protein is mostly composed by ⍺-helices, albeit after further inspection, ꞵ-sheets can be detected in the centre of the chain. 

Ornithine aminotransferase belongs to the a/b structural class, meaning that helices and sheets are alternated throughout the polypeptide chain. It is considered a globular protein, for it is found in compact units that are soluble in aqueous solutions. Furthermore, it has a PLP-dependent transferase like fold which implies that its main domain is formed by three disctinct layers; an outer layer of ⍺-helices, an inner layer of ꞵ-sheets, followed by a final outer layer of ⍺-helices. The central layer of sheets consists of seven mixed strands of order 3245671, with strands from one to six running paralel and the seventh running the opposite direction. Finally, OAT belongs to the PLP-dependent transferases superfamily.

The comparison between human OAT and its Toxoplasma gondii ortholog revealed a sequence identity of 51.2% and a physicochemical similarity of 70.0%. Despite these sequence differences, the superimposed structures showed a global RMSD of 1.33 Å, indicating a high degree of structural similarity. The alignment also revealed regions with conserved secondary structure elements, including α-helices and β-strands, alongside local differences in secondary structure and backbone displacement.
Although local backbone displacement was generally similar across most of the aligned regions there were two notable exceptions. Around positions 355–361, some residues could not be directly compared because corresponding structural information was unavailable in one of the proteins. A second region of increased displacement was observed around positions 384–388, corresponding to a loop region.

From the structure superposition of human WT and human mutant proteins it was obtained that its local backbone displacement in position 180 measures at 0.049 Å, making it practically negligible. Even though the average deviation of the entire protein structure is 0.394 Å , this is still a very minimal change (under 1 Å) and it proves that the interchanging of one single amino-acid does not cause any big structural damages. Therefore, the disease caused by the mutation must be due to chemical disadjustments.

## **Discussion**

In the molecule, the overall structure and oligomeric state remain the same, which means that the mutation does not carry extremely significant structural changes. However, the change can cause small rearranges such as Gly320’ shifting towards the active site. This can lead to steric interferences with the carboxyl group and make it difficult for the other substrates to bind onto the molecule

Also, this ⍺-carboxylate ionic interaction anchors the substrate in the one correct orientation. When arginine is lost in the mutation, the binding affinity of the carboxyl group for ornithine is also lost. A different arginine from a different position might intervene and take over.

Therefore, this mutation means two very significant things for the protein. The first one is that it increases its structural stability. The second one is that it disrupts what should be the actual positioning of the substrate in order for the molecule to undergo normal catalysis. Thus, the protein’s ability to recognise a substrate and its reaction specificity are more altered than the actual overall structure.

Between arginine and threonine there are some differing properties that are worth mentioning. Whereas arginine is a large molecule with a 174.20 g/mol molecular weight, threonine is considered to be small to medium and its molecular weight is 119.12 g/mol. The reason for this is that the first molecule features a long 3-carbon aliphatic chain ending in a complex guanidino group and the second one only a short hydroxyethyl group.

Also, arginine is highly polar and amphipathic whereas threonine is only polar. Arginine’s guanidino group is very hydrophilic but its carbon backbone offers a slight hydrophobic character closer to the main chain. Threonine is polar because its side chain contains a hydrophilic hydroxyl group (-OH) which is capable of forming hydrogen bonds. At a neutral pH, arginine has a positive charge and side chain, which is very basic, stays protonated under physiological conditions. Threonine, on the other hand, does not have a charge and its side chain is neither acidic nor basic. 
threonine and arginine have different conformational freedom. Threonine has a very small amount of freedom due to the fact that it has a ramification formed by a hydroxyl group and a methyl group and that causes it to collide with the main structure of the protein when it is trying to rotate. Biologically, that means it is a very rigid molecule and is able to maintain the -OH group facing a specific direction which is great for phosphorylation. Arginine, however, is the opposite. It has a very high conformational freedom because it has a linear chain which means that all four angles of the molecule are free. This allows the molecule to bend and move in order to latch onto other molecules such as DNA. Nonetheless, this also means that the bonds must be really strong (like multiple hydrogen bonds) in order for the molecule to stay still. 

The substitution can also change the interactions that happen between these molecules and other ones. Because arginine is polar, it is able to form salt bridges. However, threonine is neutral (or apolar) and, therefore, there is a loss of salt bridges.

Also, this ⍺-carboxylate ionic interaction anchors the substrate in the one correct orientation. When arginine is lost in the mutation, the binding affinity of the carboxyl group for ornithine is also lost. A different arginine from a different position might intervene and take over.

Therefore, this mutation means two very significant things for the protein. The first one is that it increases its structural stability. The second one is that it disrupts what should be the actual positioning of the substrate in order for the molecule to undergo normal catalysis. Thus, the protein’s ability to recognise a substrate and its reaction specificity are more altered than the actual overall structure.

The Arg180Thr mutation directly alters the active site of ornithine aminotransferase, which disrupts both substrate binding and the PLP-dependent catalytic cycle. Also, the Threonine side chain is significantly shorter than that of Arginine and also uncharged, it cannot form the necessary salt bridges with the -carboxylate group of L-ornithine, usually done by Arginine 180. Therefore, OAT loses the ability to bind onto L-ornithine in an efficient way and transaminate with 2-oxoglutarate. This loss leads to the accumulation of L-ornithine which, over time, causes the degeneration of the retinal pigment epithelium and the choroid, thus, causing blindness.

Although the relationship between OAT deficiency and elevated ornithine concentrations is well established, the precise mechanisms through which hyperornithinaemia leads to progressive retinal degeneration remain incompletely understood (Buijs et al., 2025).
One of the proposed mechanisms is that chronically elevated ornithine concentrations contribute to retinal damage, particularly by affecting the retinal pigment epithelium (RPE). The RPE is a specialised cell layer that supports photoreceptor function, maintains the retinal environment and participates in the recycling of visual pigments. Excessive ornithine may disrupt the normal functioning of RPE cells, potentially compromising their ability to support photoreceptor survival. Consequently, RPE dysfunction may contribute to the progressive degeneration of the retina and choroid observed in patients with gyrate atrophy. However, further research is needed to fully understand the mechanisms underlying this process (Buijs et al., 2025).

Not all nucleotide variants correspond to an amino-acid sequence variant because one amino-acid can correspond to more than one codon. Therefore, different combinations of nucleotides can lead to the same amino-acid combinations. For that reason, after doing the sequence alignment between the human, Toxoplasma gondii and Rattus norvegicus, the three species appear more similar at the protein level. The change in one nucleotide does not necessarily mean the change in the amino-acid. Amino-acids are defined by codons, which are groups of three nucleotides. However, not all combinations of three nucleotides have their own corresponding amino-acid. Each amino-acid is usually paired with between 2 and 4 different codons. 

If compared independently, Rattus norvegicus and Pongo abelii revealed a higher degree of conservation with the human than that of Toxoplasma gondii. Several regions of the nucleotide and protein sequences were identical or highly similar between humans and orangutans and rats, whereas greater sequence differences were observed in the comparisons involving the more distantly related species. That is due to evolution and the fact that the common ancestor of the three mammals is much closer than that of the protozoon and the human.

The results suggest that the overall fold of OAT is conserved between humans and T. gondii, despite substantial differences in their amino acid sequences. The higher physicochemical similarity compared with sequence identity suggests that some amino acid substitutions preserve chemical properties that may contribute to structural stability. The low global RMSD further supports the conservation of the overall three-dimensional structure. Nevertheless, local differences in secondary structure and backbone displacement indicate that some regions may have evolved differently. Such differences may reflect variations in local flexibility or molecular interactions, although their functional consequences cannot be established from structural comparison alone.
Furthermore,the increased backbone displacement observed around positions 384–388 may be explained by the presence of a loop region. Unlike α-helices and β-strands, loops are often more flexible and can adopt different conformations in homologous proteins. Furthermore, amino acid substitutions may alter local interactions and contribute to these structural differences. Therefore, the increased local displacement does not necessarily indicate a disruption of the overall protein fold.

When analyzing the structure of the human protein, there were a few very interesting observations made that are worth discussing. The WT versus mutant comparison showed the superposition of two pathway patterns which had little to no distance between each other, for both the 𝛽-sheets and the 𝛼-helices. This means that the overall backbone formation and the 3D folding underwent no alteration during the mutation. 

However, as shown in the picture, the side chain disposition does present with more alterations. Whereas the arginine (WT) side chain extends outwards to facilitate interactions with other molecules, the threonine (mutant) side chain is a lot shorter, which explains the loss of binding abilities.

*_limitations_*

Throughout this project, there have been some limitations related to the investigation of the protein. First of all, there were no actual lab experiments done, so some of the conclusions related to the mechanism of the disease ended up somewhat vague. This is due to the fact that the reason as to why the excess of concentration of L-ornithine causes the degradation of the retinal epithelium is not entirely clear (Montioli et al. , 2019) Moreover, when analyzing the structure superposition of the homolog proteins, the video inside the program itself would not show the entire 360º rotation of said, which made it harder to identify the different lengths of the sequence structure. 


## **Conclusions**

The key takeaway from the sequence alignment of the Wild Type and mutant protein is that the mutation overall does not affect the structure of the protein. If only it makes it more rigid and increases its stability. However, the interchange of amino acids does provoke a loss of salt bridges and steric clashes on the active site of the protein, which lead to problems with binding affinity, catalytic specificity and positioning of substrates.

Overall, the cross-species alignment between Homo sapiens, Toxoplasma gondii and Rattus norvegicus showed only primary sequence conservation in stretches of maximum seven amino acids. Mostly with Toxoplasma gondii, the other two species had very little in common, except when looking at their structure. This leads to the conclusion that structure is more conserved than sequence throughout evolution. 

The comparison revealed a high degree of sequence conservation between human OAT and Pongo abelii at both nucleotide and protein levels. In several regions, the sequences were identical or showed very few differences, consistent with the close evolutionary relationship between humans and orangutans. These findings suggest that some features of OAT have been conserved throughout evolution.

In conclusion, about the structure of the mutation it can be said that the mutation that takes place at position 180 does not cause a significant effect on the overall three dimensional folding or secondary structure characteristics. This is demonstrated by the backbone displacement, which measures less than 1 Å, making it practically negligible. Instead, the differing characteristics between arginine and threonine prove that the mechanisms of the disease are caused rather by chemical and spatial disarrangements. The threonine protein is significantly shorter and loses the ability to form salt bridges. 

Overall, the comparison between human OAT and its Toxoplasma gondii ortholog highlights the conservation of protein structure throughout evolution, despite differences in amino acid sequence. The preservation of a similar three-dimensional fold suggests that structural organisation can remain conserved even when many residues have changed, potentially reflecting evolutionary constraints on protein folding. Nevertheless, the local differences observed in certain regions, particularly in flexible loops, illustrate that structural conservation does not imply complete structural identity. Taken together, these findings emphasise the importance of considering both sequence and structural information when comparing homologous proteins.

## **Methods**
Scientific literature was consulted through databases such as PubMed and MeSH to gather information about OAT, OAT deficiency and its associated disease, as well as the functional roles of specific amino acids, including Arg180.

Scientific articles were selected based on their relevance to the project objectives, particularly the function of ornithine aminotransferase (OAT), the molecular mechanisms underlying OAT deficiency and its association with gyrate atrophy. Priority was given to peer-reviewed publications providing relevant experimental findings, clinical information or insights into the disease mechanisms. The selected articles were used to support the interpretation of the bioinformatics results and provide biological and clinical context.

BLAST was used to verify that the provided wild-type and mutant nucleotide and protein sequences corresponded to human OAT. The results were evaluated using parameters such as accession type, query coverage and E-value. The information associated with the BLAST results was also examined to identify the gene and determine its chromosomal location and locus, using additional databases such as OMIM.

The wild-type nucleotide and protein sequences were then used to identify homologous sequences from other species. BLAST searches were performed by specifying the organism of interest, allowing the identification of OAT homologues in _Rattus norvegicus_, _Pongo abelii_ and _Toxoplasma gondii_.

Sequence alignments were performed to compare the wild-type and mutant human sequences and to examine differences associated with the mutation. Multiple sequence alignments were also used to compare the human wild-type sequences with their homologues from the other species, identifying similarities and conserved regions at both the nucleotide and protein levels.

In order to compare the human sequence with the ones of the other homolog species, the option of aligning two or more sequences that the program offers was used. The tool of alignment view was the most useful when wanting to compare the three different species because it showed the sequences query-anchored with dots for identities, which allowed to clearly identify the regions in each sequence that were either conserved or changed.

The results and quantitative values generated by the bioinformatics tools were used for descriptive and comparative analysis. These included sequence alignment metrics, such as query coverage, percentage identity and E-value, as well as structural comparison metrics, such as RMSD. All values were obtained directly from the respective tools and interpreted to compare the sequences and structures. No additional calculations or statistical tests were performed.


## **Abbreviations**

Human Ornithine Aminotransferase (hOAT), Ornithine δ-aminotransferase (δ-OAT), Ornithine Aminotransferase (OAT), Gyrate Atrophy (GACR), Coding DNA Sequence (CDS), Transfer RNA (tRNA), pyridoxal 5'-phosphate (PLP), pyridoxamine-5’-phosphate (PMP), glutamate-5-semialdehyde or l-glutamate-γ-semialdehyde (GSA), wild type (WT)

## **Declarations**

The FASTA files used for sequence analysis and the structural comparison materials involving human OAT, Toxoplasma gondii OAT and the Arg180Thr variant were provided by the course instructors. The analyses and results obtained from these materials are presented in this report.

The accession number for the CDS is NM_000274, whilst the one used for the protein sequence is NP_000265

**Ana Sánchez Rebollo — Developer**: Contributed to the development and execution of project tasks, scientific analysis, interpretation of information, and communication of progress and problems.

**Veronica Wangchen — Project Manager**: Coordinated the team's workflow and communication, monitored progress and deadlines, organised meetings when necessary, and reviewed project deliverables.

**Clara Jiménez Bernal — Project Owner**: Defined and prioritised project objectives, communicated the project scope and requirements, and ensured that the work remained aligned with the project's main goal.


## **References**

Floriani F, Borri Voltattorni C, Montioli R. Current Insight into Human Ornithine Aminotransferase: A Review. Proteins. 2026;94(8):1431-1441. doi:10.1002/prot.70134

Shen BW, Hennig M, Hohenester E, Jansonius JN, Schirmer T. Crystal structure of human recombinant ornithine aminotransferase. J Mol Biol. 1998;277(1):81-102. doi:10.1006/jmbi.1997.1583

Elnahry AG, Tripathy K. Gyrate Atrophy of the Choroid and Retina. In: StatPearls. Treasure Island (FL): StatPearls Publishing; August 25, 2023. 

Sun Q. Cerebral creatine deficiency syndromes, In Biomarkers in Inborn Errors of Metabolism: Clinical Aspects and Laboratory Determination. Elsevier,
2017, pages 331-341

Buijs MJN, Balfoort BM, Brands MM, et al. Molecular and cellular mechanisms underlying gyrate atrophy: Why is the retina primarily affected?. Acta Ophthalmol. 2025;103(7):e436-e455. doi:10.1111/aos.17498

Kaczmarczyk A, Baker M, Diddle J, Yuzyuk T, Valle D, Lindstrom K. A neonate with ornithine aminotransferase deficiency; insights on the hyperammonemia-associated biochemical phenotype of gyrate atrophy. Mol Genet Metab Rep. 2022;31:100857. Published 2022 Mar 16. doi:10.1016/j.ymgmr.2022.100857

Palmer E, Stepien KM, Campbell C, et al. Clinical, biochemical and molecular analysis in a cohort of individuals with gyrate atrophy. Orphanet J Rare Dis. 2023;18(1):265. Published 2023 Sep 4. doi:10.1186/s13023-023-02840-0

Storici P, Capitani G, Müller R, Schirmer T, Jansonius JN. Crystal structure of human ornithine aminotransferase complexed with the highly specific and potent inhibitor 5-fluoromethylornithine. J Mol Biol. 1999;285(1):297-309. doi:10.1006/jmbi.1998.2289

Online Mendelian Inheritance in Man. Gyrate atrophy of choroid and retina; GACR (MIM #258870). BMC Bioinformatics. 2026;27(1):205.

Buijs MJN, Balfoort BM, Brands MM, et al. Molecular and cellular mechanisms underlying gyrate atrophy: Why is the retina primarily affected?. Acta Ophthalmol. 2025;103(7):e436-e455. doi:10.1111/aos.17498 

Bisetegn H, Debash H, Ebrahim H, et al. Global seroprevalence of Toxoplasma gondii infection among patients with mental and neurological disorders: A systematic review and meta-analysis. Health Sci Rep. 2023;6(6):e1319. Published 2023 Jun 5. doi:10.1002/hsr2.1319

Montioli R, Paiardini A, Giardina G, et al. R180T variant of δ-ornithine aminotransferase associated with gyrate atrophy: biochemical, computational, X-ray and NMR studies provide insight into its catalytic features. FEBS J. 2019;286(14):2787-2798. doi:10.1111/febs.14843

</div>

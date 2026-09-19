

## From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

## Disease Background
Early-onset familial Alzheimer’s disease (EOFAD) is a rare inherited form of Alzheimer’s disease in which symptoms typically begin before 65 years of age. Mutations in the PSEN1 (presenilin-1) gene are the most common genetic cause of familial early-onset Alzheimer’s disease. The major clinical characteristics include progressive memory loss, difficulty with thinking and problem-solving, problems with language and communication, difficulty performing familiar tasks, and changes in behavior or personality. As the disease progresses, affected individuals gradually lose the ability to perform daily activities independently. Some individuals with PSEN1 mutations may also develop neurological symptoms such as seizures or movement problems.

The brain is the main organ affected, particularly the hippocampus and cerebral cortex, which are important for memory, learning, language, and other cognitive functions. At the cellular level, neurons are mainly affected. The disease is associated with the accumulation of amyloid-beta (Aβ) plaques and tau neurofibrillary tangles, which interfere with neuronal function and contribute to neuronal damage and death. Genetically, PSEN1-related early-onset familial Alzheimer’s disease is associated with mutations in the PSEN1 gene, which is located on chromosome 14. PSEN1 encodes presenilin-1, a component of the γ-secretase complex that is involved in processing amyloid precursor protein (APP). Disease-causing PSEN1 variants can alter this processing and affect the production of amyloid-beta peptides, contributing to amyloid plaque formation, neuronal dysfunction, and progressive cognitive decline.

PSEN1-related early-onset familial Alzheimer’s disease follows an autosomal dominant inheritance pattern. This means that a disease-causing variant in one copy of the PSEN1 gene can be sufficient to cause the inherited condition. When a parent carries a pathogenic PSEN1 variant, each child has a 50% chance of inheriting the variant. In families with a pathogenic PSEN1 variant, the condition may therefore occur across multiple generations.

## Gene and Normal Protein Function

The official gene symbol is PSEN1, which stands for presenilin 1. The PSEN1 gene is located on chromosome 14, specifically at the cytogenetic location 14q24.2. It normally encodes presenilin-1, a membrane protein that is 467 amino acids long in humans. Presenilin-1 is an important component of the γ-secretase complex, a protein complex that cleaves specific proteins within their membrane-spanning regions.

Presenilin-1 functions mainly as the catalytic subunit of the γ-secretase complex. It helps the complex cleave several transmembrane proteins, including amyloid precursor protein (APP) and Notch receptors. Through these activities, PSEN1 is involved in important cellular processes such as APP processing, Notch signaling, Wnt signaling, cell adhesion, and calcium homeostasis. Presenilin-1 is mainly found in intracellular membranes, including the endoplasmic reticulum and Golgi apparatus, as well as other cellular membranes where the γ-secretase complex is present. It can also be found at the cell membrane and in membrane compartments such as endosomes.

PSEN1 participates primarily in the γ-secretase pathway, particularly in the processing of transmembrane proteins such as APP and Notch. During APP processing, γ-secretase cleaves APP and contributes to the production of amyloid-beta (Aβ) peptides. PSEN1 also participates in the Notch signaling pathway, which is important for cell differentiation and development, and contributes to processes involving Wnt signaling and calcium homeostasis. Therefore, normal PSEN1 activity is important for proper protein processing, cell signaling, neuronal function, and development.

## Documented Mutation

| Required Information       | ClinVar Information |
|----------------------------|---------------------|
| Gene                       | PSEN1  |
| Reference transcript       | NM_000021.4 |
| Exact variant notation     | NM_000021.4(PSEN1):c.617G>C (p.Gly206Ala) |
| Nucleotide change          | c.617G>C |
| Predicted protein change   | NP_000012.1:p.Gly206Ala |
| Mutation type              | Missense variant |
| ClinVar accession          | VCV000018143.33 |
| Clinical interpretation    | Pathogenic |
| Scientific reference      | *Association of common and rare variants with Alzheimer's disease in more than 13,000 diverse individuals with whole-genome sequencing from the Alzheimer's Disease Sequencing Project.* |
| ClinVar link               | [ClinVar Variation 18143](https://www.ncbi.nlm.nih.gov/clinvar/variation/18143/) |
| PubMed reference           | [PubMed](https://pubmed.ncbi.nlm.nih.gov/39428839/) |


### Mutation Hypothesis

The mutation analyzed in this study is PSEN1 c.617G>C, in which the nucleotide G is replaced by C at position 617. Only one nucleotide is affected. This substitution is predicted to be a missense mutation because it changes the amino acid at position 206 from glycine (G) to alanine (A), resulting in the predicted protein change p.Gly206Ala. Since the mutation involves the replacement of one nucleotide rather than an insertion or deletion, the reading frame is not expected to change, and no frameshift should occur.

The mutation is also predicted to cause no change in protein length. The normal PSEN1 protein is 467 amino acids long, and the mutant protein is expected to remain 467 amino acids long because only one amino acid is replaced. In terms of protein function, the mutation is predicted to potentially alter presenilin-1 activity, particularly its role in the γ-secretase complex and APP processing. Changes in this pathway may affect amyloid-beta production and are associated with the development of early-onset familial Alzheimer’s disease.

## Methods

**Obtaining the PSEN1 CDS**

The PSEN1 coding sequence (CDS) was obtained in FASTA format from a sequence database and used as the wild-type (WT) reference sequence.

**WT Protein Translationn** 

The WT CDS was translated into a protein sequence using the Transeq tool. The resulting protein FASTA file was saved for further analysis.

**Identifying the Documented Mutation**

A documented PSEN1 mutation was obtained from ClinVar. The selected variant was c.617G>C, which results in the predicted protein change p.Gly206Ala. The nucleotide substitution was introduced into the WT CDS to create the documented mutant sequence.

**Creating the Artificial Mutation**

An artificial mutation was created by substituting A with C in the first codon of the WT CDS. The mutated CDS was then translated using Transeq, producing the predicted Met1 → Leu1 amino-acid change.

**Protein Sequence Alignment**

The WT and mutant protein sequences were compared using the Needle global alignment tool. The alignments were examined for amino-acid differences, gaps, downstream changes, premature stop codons, and changes in protein length.


## Results

**Wild-Type PSEN1 CDS and Predicted Protein Characteristics**

| Item | Result |
|---|---|
| CDS length | 1,401 bp |
| Predicted protein length | 467 amino acids |
| Start codon | ATG |
| Stop codon | TGA |
| First 10 amino acids | MTELPAPLSY |
| Last 10 amino acids | DQLAFHQFYI |

**Manual Creation of the Documented PSEN1 c.617G>C Mutation**

| Required Information | Result |
|---|---|
| Original nucleotide position | 617 |
| Original sequence | GGT |
| Mutant sequence | GCT |
| Number of bases substituted | 1 |
| Number of bases inserted | 0 |
| Number of bases deleted | 0 |
| Mutation type | Missense |

**Translation Results of the Mutant PSEN1 CDS**

| Required Information | Result |
|---|---|
| Mutant CDS length | 1,401 bp |
| Mutant protein length | 467 aa |
| Reading frame | +1 |
| First amino-acid difference | Position 206 |
| WT amino acid at position 206 | Glycine |
| Mutant amino acid at position 206 | Alanine |
| Premature stop codon | Absent |
| Approximate number of amino acids affected | 1 amino acid |

## WT and Mutant PSEN1 Protein Comparison

The WT and mutant PSEN1 proteins first differ at amino-acid position 206, where glycine (Gly, G) is replaced by alanine (Ala, A). This results in the predicted change p.Gly206Ala (G206A) caused by the c.617G>C substitution. Only one amino acid is affected, with no downstream changes, deletions, or insertions.

The mutation does not change the reading frame or protein length because it is a single-nucleotide substitution. Both WT and mutant proteins remain 467 amino acids long, and no premature stop codon is produced. The mutation is therefore classified as a missense mutation, changing the codon from GGT (glycine) to GCT (alanine) at position 206.

## Artificial Mutation Experiment

The artificial mutation changed A to C in the first codon, resulting in a Met1 → Leu1 amino-acid change. The CDS and protein lengths remained unchanged, with no frameshift or premature stop codon. Because the change occurs in the start codon, it may interfere with normal translation initiation.

| Feature | Student-Created Mutation |
|---|---|
| CDS length | 1,401 bp |
| Protein length | 467 aa |
| Mutation type | Start-codon substitution |
| Nucleotide change | A>C in the first codon |
| Reading frame | Unchanged |
| Premature stop codon | No |
| Amino acid affected | Met1 → Leu1 |
| Expected functional consequence | May interfere with normal translation initiation |

## Molecular Interpretation: Gene → Mutation → Protein → Cellular Effect → Phenotype
The PSEN1 c.617G>C mutation is a single-nucleotide substitution that changes the codon from GGT to GCT, resulting in a missense mutation, p.Gly206Ala. The sequence analysis showed that only amino acid 206 changed, with no frameshift, insertion, deletion, premature stop codon, or change in protein length. PSEN1 is a component of the γ-secretase complex, which is involved in processing amyloid precursor protein (APP). Published evidence indicates that the Gly206Ala variant alters γ-secretase function and can increase the production of amyloid-β42. Increased Aβ42 can promote amyloid accumulation and plaque formation, contributing to neuronal dysfunction and neurodegeneration. These changes are associated with the development of early-onset familial Alzheimer’s disease. 

Early-onset familial Alzheimer’s disease is a degenerative brain disorder that causes progressive dementia, mainly affecting memory, judgment, and the ability to perform daily activities. Early symptoms may include forgetfulness and confusion, which gradually worsen and can lead to difficulty recognizing people, naming objects, communicating, and performing routine tasks. As the disease progresses, affected individuals may develop personality and behavioral changes, agitation, withdrawal, and loss of language skills, eventually requiring total care. The early-onset form develops from approximately the 30s to mid-60s and accounts for less than 10% of Alzheimer’s disease cases (MedlinePlus Genetics, 2019).

## Limitations
Transeq and Needle only analyze nucleotide and protein sequences. They do not account for biological factors that may affect how PSEN1 is actually expressed or functions in cells.

The artificial mutation changed the first codon and produced a Met1 → Leu1 change in Transeq. However, the tool cannot determine whether translation would actually begin with leucine or whether the altered start codon would prevent normal translation.

The predicted effects were not tested experimentally. Laboratory methods would be needed to determine the actual effect of the mutation on PSEN1 protein and cellular function.

### Conclusion

This activity investigated the molecular basis of PSEN1-associated early-onset familial Alzheimer’s disease through sequence-based analysis. The human PSEN1 reference CDS and protein sequence were retrieved and used to describe the normal structure and function of presenilin-1, an important component of the γ-secretase complex. The documented c.617G>C (p.Gly206Ala) variant was identified and manually reproduced in the CDS. Translation and Needle alignment showed that the mutation causes a single Gly206 → Ala206 substitution without changing the reading frame, protein length, or producing a premature stop codon, identifying it as a missense mutation.

An artificial mutation in the first codon was also created and resulted in a predicted Met1 → Leu1 change. These sequence changes demonstrate how a single nucleotide substitution can alter a protein sequence and potentially affect protein function. However, computational analysis can only predict molecular effects and cannot confirm actual changes in protein folding, γ-secretase activity, cellular processes, or Alzheimer’s disease phenotype. Overall, the activity demonstrated the relationship between DNA sequence, protein sequence, mutation type, and potential biological effects, while emphasizing the need for experimental evidence to confirm computational predictions.


## References
Lee, W. P., Choi, S. H., Shea, M. G., Cheng, P. L., Dombroski, B. A., Pitsillides, A. N., Heard-Costa, N. L., Wang, H., Bulekova, K., Kuzma, A. B., Leung, Y. Y., Farrell, J. J., Lin, H., Kunkle, B. W., Naj, A., Blue, E. E., Nusetor, F., Wang, D., Boerwinkle, E., Bush, W. S., … Peloso, G. M. (2024). Association of common and rare variants with Alzheimer's disease in more than 13,000 diverse individuals with whole-genome sequencing from the Alzheimer's Disease Sequencing Project. Alzheimer's & dementia : the journal of the Alzheimer's Association, 20(12), 8470–8483. https://doi.org/10.1002/alz.14283 

https://www.ncbi.nlm.nih.gov/medgen/C1843013 

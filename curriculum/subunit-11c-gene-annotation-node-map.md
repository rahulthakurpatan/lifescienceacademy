# Life Science Academy — Unit 11, Subunit 11.C: Gene Annotation

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Understand how computational methods identify genes, predict biological functions, assess genetic variation and reconstruct evolutionary relationships using sequence, structural, contextual and network evidence.

**Planned nodes:** 6. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.C.01 — Genome Organisation and Structural Gene Annotation

**Student-facing description:** Identify ORFs, coding sequences, promoters, regulatory regions, exons, introns and UTRs through prokaryotic and eukaryotic gene-prediction approaches.

**Core scope:** Reading frames and start/stop codons, ORF versus confirmed gene, prokaryotic operons and eukaryotic splicing, transcript evidence, regulatory element predictions, ab initio coding models and evidence-based annotation, alternative transcripts, noncoding RNA context, GFF/GTF coordinates and annotation quality.

**Evidence and reasoning:** Interpret a short illustrative sequence and gene model, compare predicted exons with transcript support and identify coordinate conventions.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.C.02.

### 11.C.02 — Homology-Based Gene Function Prediction

**Student-facing description:** Infer gene function from similarity searches, orthology, conserved motifs and domains, GO terms and enzyme classification while assessing annotation-transfer limitations.

**Core scope:** Sequence search and orthology inference, domain architecture and catalytic motifs, curated annotations, GO molecular function/biological process/cellular component and evidence codes, EC numbers, paralog divergence, annotation propagation errors and experimentally supported versus inferred function.

**Evidence and reasoning:** Compare candidate annotations based on alignment coverage, motif preservation and evidence; identify uncertain functional assignments.

**Progression:** Build on 11.C.01. Prepare 11.C.03.

### 11.C.03 — Context, Structure and Network-Based Functional Annotation

**Student-facing description:** Integrate conserved neighbourhood, synteny, gene fusion, phylogenetic profiles, co-expression, protein interactions, structural similarity and active-site conservation.

**Core scope:** Genomic context, operon proximity, conserved synteny, Rosetta-stone gene fusion, co-occurrence profiles, co-expression and interaction networks, guilt-by-association limits, structural folds and active-site geometry, complementary evidence integration, confidence and experimental validation.

**Evidence and reasoning:** Compare contextual evidence for unknown genes, evaluate network or structural predictions and distinguish correlation from functional causation.

**Progression:** Build on 11.C.02. Prepare 11.C.04.

### 11.C.04 — Genetic Variation and Computational Variant Analysis

**Student-facing description:** Interpret SNPs, SNVs, indels, copy-number and structural variants, polymorphism, reference genomes, VCF records and genotype–phenotype associations.

**Core scope:** SNV versus population polymorphism terminology, indels, CNV and rearrangements, reference/alternate alleles and reference bias, coordinate conventions, VCF fields and genotype/depth/quality, variant detection overview and filtering, annotation to transcripts, association versus causation and population context.

**Evidence and reasoning:** Read illustrative VCF records, classify variants and identify reference/transcript or quality limitations.

**Progression:** Build on 11.C.03. Prepare 11.C.05.

### 11.C.05 — Prediction of Deleterious Mutations and Functional Consequences

**Student-facing description:** Assess synonymous and nonsynonymous variants, conservation, stability effects and SIFT, PolyPhen-2 and CADD scores, recognising uncertainty in computational pathogenicity assessment.

**Core scope:** Missense, nonsense, frameshift, splice and regulatory effects; synonymous variants can have functional effects; evolutionary conservation, sequence and structure features, SIFT/PolyPhen-2/CADD principles and distinct score scales, calibration, prioritisation and conflicting evidence, experimental validation and clinical interpretation boundaries.

**Evidence and reasoning:** Compare example scores and evidence, distinguish predicted deleteriousness from established pathogenicity and identify limits of model generalisation.

**Progression:** Build on 11.C.04. Prepare 11.C.06.

### 11.C.06 — Computational Phylogenetics and Evolutionary Tree Reconstruction

**Student-facing description:** Compare rooted and unrooted trees, substitution models, UPGMA, neighbour-joining, parsimony, maximum likelihood, Bayesian inference and bootstrap support.

**Core scope:** Alignment and site selection, evolutionary versus observed distances, simple Jukes–Cantor correction and assumptions, UPGMA ultrametric assumption, neighbour joining, parsimony and long-branch attraction, likelihood and Bayesian principles, model choice, rooting, bootstrap versus posterior support, gene/species-tree discordance, recombination and horizontal transfer caveats.

**Evidence and reasoning:** Build small distance/parsimony examples, read trees and branch lengths, compare support measures and identify violated assumptions.

**Progression:** Build on 11.C.05. Bridge to subunit 11.D.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Gene function prediction using homology | 11.C.01–02 |
| Gene function prediction using context, structures and networks | 11.C.03 |
| Genetic variation and polymorphism | 11.C.04 |
| Deleterious mutations | 11.C.05 |
| Phylogenetics | 11.C.06 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

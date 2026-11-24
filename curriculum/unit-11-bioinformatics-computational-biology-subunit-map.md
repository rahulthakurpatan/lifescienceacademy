# Life Science Academy — Unit 11: Bioinformatics and Computational Biology

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Approved architecture — 7 subunits, 42 planned learning nodes

| Subunit | Title | Nodes | Roadmap |
|---|---|---:|---|
| 11.A | Major Bioinformatic Resources | 5 | [Node contracts](subunit-11a-major-bioinformatic-resources-node-map.md) |
| 11.B | Basic Concepts of Sequence Analysis | 7 | [Node contracts](subunit-11b-sequence-analysis-node-map.md) |
| 11.C | Gene Annotation | 6 | [Node contracts](subunit-11c-gene-annotation-node-map.md) |
| 11.D | Molecular Modelling and Dynamics | 6 | [Node contracts](subunit-11d-molecular-modelling-dynamics-node-map.md) |
| 11.E | Classification and Comparison of Protein 3D Structures | 6 | [Node contracts](subunit-11e-protein-3d-structures-node-map.md) |
| 11.F | Drug Design | 6 | [Node contracts](subunit-11f-drug-design-node-map.md) |
| 11.G | Systems Biology | 6 | [Node contracts](subunit-11g-systems-biology-node-map.md) |
| Total | | 42 | |

## Subunit descriptions and learning sequences

### 11.A — Major Bioinformatic Resources

Explore the foundations of bioinformatics and the organisation, retrieval and interpretation of biological information using sequence, gene expression, molecular structure and functional annotation databases.

- 11.A.01 — **Foundations of Bioinformatics and Biological Data Management:** Explore bioinformatics applications, biological data types, primary and derived databases, identifiers, metadata and FASTA, FASTQ and GenBank formats.
- 11.A.02 — **Nucleotide, Protein and Genome Sequence Databases:** Retrieve and compare sequence and genome records from NCBI, GenBank, ENA, DDBJ, RefSeq, UniProt and Ensembl, interpreting accession numbers and cross-references.
- 11.A.03 — **Gene Expression and Functional Genomics Databases:** Explore GEO, ArrayExpress, Expression Atlas and SRA, distinguishing raw reads, microarray and RNA-seq expression data, experimental metadata and processed profiles.
- 11.A.04 — **Macromolecular Structure Databases and Structural Resources:** Compare PDB, wwPDB, RCSB PDB, PDBe, BMRB, EMDB and AlphaFold DB records, structural formats and experimental versus predicted structures.
- 11.A.05 — **Sequence Pattern, Protein Family and Functional Databases:** Interpret PROSITE, Pfam, InterPro, PRINTS, SMART, conserved domains, motifs, sequence profiles, Gene Ontology and KEGG annotations.

### 11.B — Basic Concepts of Sequence Analysis

Develop computational approaches for comparing biological sequences, detecting conserved regions, searching databases, constructing alignments and interpreting evolutionary and genomic relationships.

- 11.B.01 — **Sequence Comparison, Identity, Similarity and Homology:** Distinguish identity, similarity and homology, relating conserved regions, substitutions and indels to orthologues, paralogues and xenologues.
- 11.B.02 — **Sequence Pattern Recognition and Repeat Finding:** Identify direct, inverted, tandem and interspersed repeats, microsatellites, palindromes, low-complexity regions, dot plots, k-mers and motif searches.
- 11.B.03 — **Scoring Matrices and Principles of Sequence Alignment:** Explain substitution probabilities, log-odds scoring, PAM and BLOSUM matrices, gap-opening and gap-extension penalties and alignment scores.
- 11.B.04 — **Pairwise Sequence Alignment and Dynamic Programming:** Apply global, local and semi-global alignment through Needleman–Wunsch and Smith–Waterman matrices, recurrence, traceback and optimal scoring.
- 11.B.05 — **Biological Database Searching with BLAST and FASTA:** Compare BLAST and FASTA heuristic searches, seed-and-extend logic, search variants, bit scores, E-values, coverage and interpretation of hits.
- 11.B.06 — **Multiple Sequence Alignment and Profile Analysis:** Compare progressive, iterative and consistency-based alignment, Clustal Omega, MUSCLE, MAFFT, guide trees, consensus, sequence logos, PSSMs and profile HMMs.
- 11.B.07 — **Sequence-Based Taxonomy and Comparative Genomics:** Connect barcoding, 16S rRNA, ITS, ANI, synteny, orthologous groups, core/accessory genomes and pangenomes with taxonomy and phylogenetic inference.

### 11.C — Gene Annotation

Understand how computational methods identify genes, predict biological functions, assess genetic variation and reconstruct evolutionary relationships using sequence, structural, contextual and network evidence.

- 11.C.01 — **Genome Organisation and Structural Gene Annotation:** Identify ORFs, coding sequences, promoters, regulatory regions, exons, introns and UTRs through prokaryotic and eukaryotic gene-prediction approaches.
- 11.C.02 — **Homology-Based Gene Function Prediction:** Infer gene function from similarity searches, orthology, conserved motifs and domains, GO terms and enzyme classification while assessing annotation-transfer limitations.
- 11.C.03 — **Context, Structure and Network-Based Functional Annotation:** Integrate conserved neighbourhood, synteny, gene fusion, phylogenetic profiles, co-expression, protein interactions, structural similarity and active-site conservation.
- 11.C.04 — **Genetic Variation and Computational Variant Analysis:** Interpret SNPs, SNVs, indels, copy-number and structural variants, polymorphism, reference genomes, VCF records and genotype–phenotype associations.
- 11.C.05 — **Prediction of Deleterious Mutations and Functional Consequences:** Assess synonymous and nonsynonymous variants, conservation, stability effects and SIFT, PolyPhen-2 and CADD scores, recognising uncertainty in computational pathogenicity assessment.
- 11.C.06 — **Computational Phylogenetics and Evolutionary Tree Reconstruction:** Compare rooted and unrooted trees, substitution models, UPGMA, neighbour-joining, parsimony, maximum likelihood, Bayesian inference and bootstrap support.

### 11.D — Molecular Modelling and Dynamics

Explore computational representations of biomolecules, molecular mechanics, force fields, energy optimisation, conformational sampling and molecular dynamics simulations to understand molecular behaviour.

- 11.D.01 — **Foundations of Molecular Modelling and Three-Dimensional Visualisation:** Interpret atomic coordinates, bond geometry, molecular coordinate systems and ball-and-stick, space-filling, ribbon and surface views using representative PyMOL and ChimeraX visualisations.
- 11.D.02 — **Molecular Mechanics and Potential Energy Functions:** Explain potential-energy surfaces and classical molecular mechanics through bond stretching, angle bending, torsions, electrostatics and van der Waals terms.
- 11.D.03 — **Force Fields and Molecular Environment Modelling:** Compare AMBER, CHARMM, GROMOS and OPLS force fields, atom types, charges, parameterisation, explicit/implicit solvent, water models and periodic boundaries.
- 11.D.04 — **Energy Minimisation and Conformational Sampling:** Compare local and global minima, steepest descent, conjugate gradients, conformational barriers, Monte Carlo sampling and Boltzmann distributions.
- 11.D.05 — **Principles of Molecular Dynamics Simulation:** Trace Newtonian motion, numerical integration, Verlet methods, initial velocities, time steps, ensembles, thermostats, barostats, equilibration and production trajectories.
- 11.D.06 — **Molecular Dynamics Analysis and Model Validation:** Analyse trajectories using RMSD, RMSF, radius of gyration, hydrogen bonds, solvent accessibility, conformational transitions and free-energy landscapes.

### 11.E — Classification and Comparison of Protein 3D Structures

Connect hierarchical protein architecture with structural classification, computational comparison, secondary and tertiary structure prediction, comparative modelling, threading and artificial intelligence-based approaches.

- 11.E.01 — **Protein Architecture and Hierarchical Structural Organisation:** Relate primary, secondary, tertiary and quaternary structure to helices, sheets, turns, motifs, domains, folds, topology and intrinsic disorder.
- 11.E.02 — **Protein Structure Classification, Comparison and Alignment:** Compare SCOP, SCOPe, CATH and ECOD classifications with structural superposition, DALI, TM-align, RMSD and TM-score.
- 11.E.03 — **Computational Prediction of Protein Secondary Structure:** Compare Chou–Fasman, GOR, evolutionary-profile and neural-network approaches including PSIPRED, assessing accuracy and limitations.
- 11.E.04 — **Homology Modelling and Comparative Protein Structure Prediction:** Trace template identification and selection, target–template alignment, backbone, loop and side-chain modelling, refinement and validation using MODELLER and SWISS-MODEL concepts.
- 11.E.05 — **Fold Recognition, Threading and Ab Initio Structure Prediction:** Compare fold libraries, sequence–structure compatibility, threading, remote homology, fragment assembly and energy-based de novo prediction.
- 11.E.06 — **Artificial Intelligence-Based Protein Structure Prediction:** Explore machine learning, coevolution, AlphaFold2, AlphaFold3 and RoseTTAFold, interpreting pLDDT, PAE, CASP benchmarks, Ramachandran plots and prediction limitations.

### 11.F — Drug Design

Investigate computational drug discovery through chemical information resources, receptor–ligand interactions, structure-based and ligand-based approaches, molecular docking, activity prediction and ADMET assessment.

- 11.F.01 — **Foundations of Computational Drug Discovery and Chemical Databases:** Explore target identification, hits, leads and optimisation, using NCI resources, PubChem, ChEMBL, DrugBank, ZINC, SMILES, InChI and fingerprints.
- 11.F.02 — **Receptor–Ligand Interactions and Molecular Recognition:** Relate binding-site complementarity, noncovalent forces, affinity, dissociation constants, binding free energy, agonism, antagonism and competition.
- 11.F.03 — **Structure-Based Drug Design and Molecular Docking:** Compare target structures, pocket identification, rigid/flexible docking, pose sampling, scoring functions, virtual screening and validation using AutoDock Vina as an example.
- 11.F.04 — **Ligand-Based Drug Design and Structure–Activity Relationships:** Explain molecular descriptors, chemical similarity, SAR, QSAR, regression, 2D/3D QSAR, model validation and applicability domains.
- 11.F.05 — **Pharmacophore Modelling and Computational Lead Optimisation:** Compare pharmacophore features, feature alignment, ligand-based screening, scaffold hopping and general principles of balancing lead properties.
- 11.F.06 — **In Silico Drug Activity Prediction and ADMET Profiling:** Assess predicted activity, absorption, distribution, metabolism, excretion and toxicity, Lipinski's rule, solubility, permeability, bioavailability, CYP interactions and experimental validation.

### 11.G — Systems Biology

Integrate biological datasets, network analysis, mathematical models and data science to understand complex biological systems, metabolic pathways, disease mechanisms, drug discovery, digital health and personalised medicine.

- 11.G.01 — **Foundations of Systems Biology and Biological Networks:** Explore reductionist and systems approaches, emergent properties, nodes and edges, metabolic, regulatory, signalling and protein interaction networks, hubs, modules and motifs.
- 11.G.02 — **Biological Data Science and Multi-Omics Integration:** Integrate genomics, transcriptomics, proteomics and metabolomics through cleaning, normalisation, missing data, feature selection, clustering, PCA, enrichment and reproducible analysis.
- 11.G.03 — **Mathematical Modelling of Biological Systems:** Compare deterministic and stochastic models, mass-action kinetics, ODEs, steady states, feedback, numerical simulation, parameter estimation and sensitivity.
- 11.G.04 — **Computational Modelling of Metabolic Pathways and Fluxes:** Connect stoichiometric matrices, mass balance, steady-state constraints, flux balance analysis, objectives, metabolic control analysis, KEGG, BioModels and SBML.
- 11.G.05 — **Disease Modelling, Artificial Intelligence and Systems Drug Discovery:** Connect disease networks and biomarkers with mathematical disease models, supervised and unsupervised learning, neural networks, target identification, repurposing and drug–target prediction.
- 11.G.06 — **Precision Medicine and Integrated Computational Biology:** Integrate personalised medicine, pharmacogenomics, multi-omics biomarkers, digital health, electronic health records, wearables, predictive modelling, privacy, bias and reproducibility.

## Revised syllabus traceability

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Sequence databases | 11.A.01–02 |
| Gene expression databases | 11.A.03 |
| 3D structure databases | 11.A.04 |
| Sequence pattern databases | 11.A.05 |
| Database searches, BLAST and FASTA | 11.B.05 |
| Sequence identity, similarity, homologues, orthologues and paralogues | 11.B.01 |
| Repeat finding | 11.B.02 |
| Scoring matrices | 11.B.03 |
| Pairwise sequence alignments | 11.B.04 |
| Multiple sequence alignments | 11.B.06 |
| Applications in taxonomy, phylogeny and comparative genomics | 11.B.07; tree methods 11.C.06 |
| Gene function prediction using homology | 11.C.01–02 |
| Gene function prediction using context, structures and networks | 11.C.03 |
| Genetic variation and polymorphism | 11.C.04 |
| Deleterious mutations | 11.C.05 |
| Phylogenetics | 11.C.06 |
| 3D visualisation and simulation | 11.D.01, 11.D.05–06 |
| Basic molecular modelling concepts and molecular mechanics | 11.D.01–02, 11.D.04 |
| Force fields | 11.D.03 |
| Protein anatomy and hierarchical organisation | 11.E.01 |
| Protein structure classification and comparison | 11.E.02 |
| Secondary structure prediction | 11.E.03 |
| Tertiary structure prediction and homology/comparative modelling | 11.E.04–06 |
| Fold recognition, threading, ab initio prediction | 11.E.05 |
| AI-based structure prediction, including AlphaFold | 11.E.06 |
| Chemical databases including NCI and PubChem | 11.F.01 |
| Receptor–ligand interactions | 11.F.02 |
| Structure-based drug design | 11.F.03 |
| Ligand-based design, SAR and QSAR | 11.F.04 |
| Pharmacophores | 11.F.05 |
| In silico drug activity and ADMET | 11.F.06 |
| Data science applications in biology, health and drug discovery | 11.G.01–02, 11.G.05–06 |
| Mathematical modelling of metabolic pathways | 11.G.03–04 |
| Mathematical modelling of disease | 11.G.03, 11.G.05 |
| Digital health and personalised medicine | 11.G.06 |

## Quantitative and computational learning map

| Concept | Nodes |
|---|---|
| Phred scores, identifiers, database evidence | 11.A.01–05 |
| Identity, repeats, k-mers and alignment scores | 11.B.01–03 |
| Dynamic programming and BLAST statistics | 11.B.04–05 |
| MSA, sequence profiles and comparative genomics | 11.B.06–07 |
| Variant interpretation and tree reconstruction | 11.C.04–06 |
| Potential energy, Boltzmann weights and integration | 11.D.02–05 |
| RMSD, RMSF and structural validation | 11.D.06, 11.E.02, 11.E.06 |
| Binding equilibria, QSAR and model validation | 11.F.02–06 |
| Network metrics, PCA and enrichment | 11.G.01–02 |
| ODEs, sensitivity and flux balance | 11.G.03–04 |
| Predictive model evaluation, digital health and fairness | 11.G.05–06 |

## Learning progression

Biological data and database records → sequence comparison and search → gene annotation and phylogenetic inference → molecular representation and dynamics → protein structural prediction and comparison → computational drug discovery → integrated biological systems and digital health. Structural prediction concepts are previewed where necessary before detailed treatment in 11.E. The sequence is pedagogical; real computational workflows may iterate across subunits.

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

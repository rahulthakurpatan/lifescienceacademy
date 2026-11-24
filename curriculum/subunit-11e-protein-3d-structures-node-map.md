# Life Science Academy — Unit 11, Subunit 11.E: Classification and Comparison of Protein 3D Structures

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Connect hierarchical protein architecture with structural classification, computational comparison, secondary and tertiary structure prediction, comparative modelling, threading and artificial intelligence-based approaches.

**Planned nodes:** 6. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.E.01 — Protein Architecture and Hierarchical Structural Organisation

**Student-facing description:** Relate primary, secondary, tertiary and quaternary structure to helices, sheets, turns, motifs, domains, folds, topology and intrinsic disorder.

**Core scope:** Protein structural hierarchy, backbone and side-chain constraints, alpha helices and beta sheets, loops and turns, motifs versus independently folding/functional domains, fold and topology, assemblies and interfaces, conformational flexibility and intrinsically disordered regions; Ramachandran basics cross-link Unit 1.G.

**Evidence and reasoning:** Identify structural features in diagrams, compare domain organisation and distinguish structural motifs from protein families.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.E.02.

### 11.E.02 — Protein Structure Classification, Comparison and Alignment

**Student-facing description:** Compare SCOP, SCOPe, CATH and ECOD classifications with structural superposition, DALI, TM-align, RMSD and TM-score.

**Core scope:** Hierarchies and differing classification principles, fold versus homologous superfamily, CATH class/architecture/topology/homologous superfamily, structural alignment and superposition, DALI distance-matrix concepts, TM-align and length-normalised TM-score, aligned coverage, RMSD sensitivity and remote homology caveats.

**Evidence and reasoning:** Compare illustrative structural alignments, interpret scores with coverage and distinguish structural analogy from supported ancestry.

**Progression:** Build on 11.E.01. Prepare 11.E.03.

### 11.E.03 — Computational Prediction of Protein Secondary Structure

**Student-facing description:** Compare Chou–Fasman, GOR, evolutionary-profile and neural-network approaches including PSIPRED, assessing accuracy and limitations.

**Core scope:** Residue propensities and neighbourhood information, Chou–Fasman and GOR historical logic, sequence profiles and neural networks, three-state and finer secondary-structure classes, PSIPRED conceptual pipeline, Q3 accuracy and confusion matrices, disorder and boundary uncertainty, benchmark leakage.

**Evidence and reasoning:** Work simple propensity predictions, interpret per-residue confidence and compute accuracy on a small labelled example.

**Progression:** Build on 11.E.02. Prepare 11.E.04.

### 11.E.04 — Homology Modelling and Comparative Protein Structure Prediction

**Student-facing description:** Trace template identification and selection, target–template alignment, backbone, loop and side-chain modelling, refinement and validation using MODELLER and SWISS-MODEL concepts.

**Core scope:** Sequence-to-template search, coverage, identity, structural quality and biological state, target–template alignment errors, backbone transfer/spatial restraints, loop and side-chain placement, refinement, model confidence and validation, MODELLER/SWISS-MODEL representative workflows, template bias and low-identity limitations.

**Evidence and reasoning:** Select a template from example evidence, diagnose alignment-induced errors and compare models using geometry and coverage.

**Progression:** Build on 11.E.03. Prepare 11.E.05.

### 11.E.05 — Fold Recognition, Threading and Ab Initio Structure Prediction

**Student-facing description:** Compare fold libraries, sequence–structure compatibility, threading, remote homology, fragment assembly and energy-based de novo prediction.

**Core scope:** Fold recognition versus ordinary sequence similarity, threading a target onto candidate structural environments, compatibility scores, remote homology, fragment assembly, conformational search, physical/statistical energy functions, ab initio/de novo terminology and limitations, folding landscapes versus prediction of final structures.

**Evidence and reasoning:** Rank simplified fold candidates, compare comparative, threading and de novo strategies for different evidence scenarios.

**Progression:** Build on 11.E.04. Prepare 11.E.06.

### 11.E.06 — Artificial Intelligence-Based Protein Structure Prediction

**Student-facing description:** Explore machine learning, coevolution, AlphaFold2, AlphaFold3 and RoseTTAFold, interpreting pLDDT, PAE, CASP benchmarks, Ramachandran plots and prediction limitations.

**Core scope:** Training and inference concepts, MSA coevolution and learned representations, representative AlphaFold2/3 and RoseTTAFold capabilities and differences, confidence versus experimental accuracy, per-residue pLDDT and pairwise PAE where supplied, complex/interface confidence, CASP assessment, geometry including Ramachandran and clash checks, disorder, ligands, alternative conformations and experimental validation; verify current tool capabilities at lesson stage.

**Evidence and reasoning:** Interpret illustrative confidence plots and validation reports, distinguish local confidence from relative domain placement and assess whether a prediction answers the biological question.

**Progression:** Build on 11.E.05. Bridge to subunit 11.F.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Protein anatomy and hierarchical organisation | 11.E.01 |
| Protein structure classification and comparison | 11.E.02 |
| Secondary structure prediction | 11.E.03 |
| Tertiary structure prediction and homology/comparative modelling | 11.E.04–06 |
| Fold recognition, threading, ab initio prediction | 11.E.05 |
| AI-based structure prediction, including AlphaFold | 11.E.06 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

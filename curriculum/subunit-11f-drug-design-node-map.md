# Life Science Academy — Unit 11, Subunit 11.F: Drug Design

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Investigate computational drug discovery through chemical information resources, receptor–ligand interactions, structure-based and ligand-based approaches, molecular docking, activity prediction and ADMET assessment.

**Planned nodes:** 6. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.F.01 — Foundations of Computational Drug Discovery and Chemical Databases

**Student-facing description:** Explore target identification, hits, leads and optimisation, using NCI resources, PubChem, ChEMBL, DrugBank, ZINC, SMILES, InChI and fingerprints.

**Core scope:** Drug discovery stages and attrition, target identification versus experimental validation, hit/lead concepts, NCI chemical resources and PubChem substance/compound/bioassay distinctions, ChEMBL assay activity, DrugBank and ZINC resource scope, SMILES/InChI, stereochemistry and identifiers, fingerprints and provenance, assay units and conditions.

**Evidence and reasoning:** Interpret example chemical records and assay metadata, compare structural identifiers and distinguish a reported hit from a validated lead.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.F.02.

### 11.F.02 — Receptor–Ligand Interactions and Molecular Recognition

**Student-facing description:** Relate binding-site complementarity, noncovalent forces, affinity, dissociation constants, binding free energy, agonism, antagonism and competition.

**Core scope:** Molecular recognition, binding-pocket geometry and flexibility, hydrogen bonds, hydrophobic and electrostatic interactions, desolvation and entropy, equilibrium Kd and Ka, standard binding free energy and units, occupancy under simple assumptions, affinity versus efficacy, agonist/antagonist and competitive binding, IC50 versus Kd caveats.

**Evidence and reasoning:** Calculate simple occupancy and free-energy relations and interpret binding versus functional assay curves.

**Progression:** Build on 11.F.01. Prepare 11.F.03.

### 11.F.03 — Structure-Based Drug Design and Molecular Docking

**Student-facing description:** Compare target structures, pocket identification, rigid/flexible docking, pose sampling, scoring functions, virtual screening and validation using AutoDock Vina as an example.

**Core scope:** Structure-based design principles, target quality and binding-site context, ligand and receptor flexibility, conceptual docking search and scoring, pose versus score, virtual screening and ranking, AutoDock Vina as illustrative tool, redocking and benchmark concepts, false positives and experimental confirmation; benign model examples only, not optimisation of harmful compounds.

**Evidence and reasoning:** Interpret illustrative docking poses and ranking data, compare scoring uncertainty and explain why docking scores are not measured affinity.

**Progression:** Build on 11.F.02. Prepare 11.F.04.

### 11.F.04 — Ligand-Based Drug Design and Structure–Activity Relationships

**Student-facing description:** Explain molecular descriptors, chemical similarity, SAR, QSAR, regression, 2D/3D QSAR, model validation and applicability domains.

**Core scope:** Ligand-based assumptions, descriptors and fingerprints, Tanimoto similarity, qualitative SAR, quantitative regression/classification, 2D versus 3D descriptors, alignment dependence, assay comparability, train/test splits and scaffold-aware validation, overfitting, applicability domain and uncertainty; avoid equating correlation with mechanism.

**Evidence and reasoning:** Compute a small similarity or regression example, interpret validation metrics and detect leakage or out-of-domain prediction.

**Progression:** Build on 11.F.03. Prepare 11.F.05.

### 11.F.05 — Pharmacophore Modelling and Computational Lead Optimisation

**Student-facing description:** Compare pharmacophore features, feature alignment, ligand-based screening, scaffold hopping and general principles of balancing lead properties.

**Core scope:** Donor/acceptor, hydrophobic, aromatic and charged features, spatial arrangements and conformational flexibility, ligand- and structure-derived pharmacophore concepts, feature mapping and virtual screening, scaffold hopping as conceptual similarity transfer, multi-property optimisation trade-offs and experimental confirmation; use benign examples without actionable harmful compound optimisation.

**Evidence and reasoning:** Interpret feature maps, compare hypothetical matches and reason about competing properties without claiming clinical benefit.

**Progression:** Build on 11.F.04. Prepare 11.F.06.

### 11.F.06 — In Silico Drug Activity Prediction and ADMET Profiling

**Student-facing description:** Assess predicted activity, absorption, distribution, metabolism, excretion and toxicity, Lipinski's rule, solubility, permeability, bioavailability, CYP interactions and experimental validation.

**Core scope:** ADMET dimensions, physicochemical properties and rule-of-five heuristic with exceptions, solubility/permeability, distribution and protein binding, metabolism and CYP interactions, clearance/excretion, exposure versus activity, computational toxicity and activity prediction, uncertainty, applicability domain, experimental validation and distinction from human safety/efficacy; no medication recommendations.

**Evidence and reasoning:** Interpret representative property and model-confidence tables, identify trade-offs and distinguish prediction from measured pharmacokinetics or clinical evidence.

**Progression:** Build on 11.F.05. Bridge to subunit 11.G.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Chemical databases including NCI and PubChem | 11.F.01 |
| Receptor–ligand interactions | 11.F.02 |
| Structure-based drug design | 11.F.03 |
| Ligand-based design, SAR and QSAR | 11.F.04 |
| Pharmacophores | 11.F.05 |
| In silico drug activity and ADMET | 11.F.06 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

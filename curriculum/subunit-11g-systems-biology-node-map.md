# Life Science Academy — Unit 11, Subunit 11.G: Systems Biology

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Integrate biological datasets, network analysis, mathematical models and data science to understand complex biological systems, metabolic pathways, disease mechanisms, drug discovery, digital health and personalised medicine.

**Planned nodes:** 6. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.G.01 — Foundations of Systems Biology and Biological Networks

**Student-facing description:** Explore reductionist and systems approaches, emergent properties, nodes and edges, metabolic, regulatory, signalling and protein interaction networks, hubs, modules and motifs.

**Core scope:** System boundaries and emergent behaviour, directed/undirected and weighted networks, degree and centrality concepts, hubs and modules, feedback/feedforward motifs, metabolic and regulatory networks versus physical protein interactions, network evidence and incompleteness, network topology versus dynamics.

**Evidence and reasoning:** Read small network graphs, calculate degree and identify motifs, distinguish observed associations from mechanistic interactions.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.G.02.

### 11.G.02 — Biological Data Science and Multi-Omics Integration

**Student-facing description:** Integrate genomics, transcriptomics, proteomics and metabolomics through cleaning, normalisation, missing data, feature selection, clustering, PCA, enrichment and reproducible analysis.

**Core scope:** Data matrices and metadata, quality control, missingness, scaling/normalisation and batch effects, exploratory statistics, clustering and PCA interpretation, pathway enrichment and multiple-testing correction, multi-omics integration by matched samples and features, feature selection inside validation folds, reproducible workflows and provenance.

**Evidence and reasoning:** Interpret PCA and clustering plots, compare normalisation choices, recognise confounding and assess enrichment evidence.

**Progression:** Build on 11.G.01. Prepare 11.G.03.

### 11.G.03 — Mathematical Modelling of Biological Systems

**Student-facing description:** Compare deterministic and stochastic models, mass-action kinetics, ODEs, steady states, feedback, numerical simulation, parameter estimation and sensitivity.

**Core scope:** Variables, parameters, units and initial conditions, mass-action rate laws and ODE construction, steady state versus equilibrium, simple feedback and stability, deterministic versus stochastic descriptions, numerical integration concepts, parameter identifiability and fitting, sensitivity and uncertainty, experimental testing and model scope.

**Evidence and reasoning:** Construct a simple reaction ODE, solve or approximate a steady state, interpret parameter-sensitivity plots and distinguish fit from prediction.

**Progression:** Build on 11.G.02. Prepare 11.G.04.

### 11.G.04 — Computational Modelling of Metabolic Pathways and Fluxes

**Student-facing description:** Connect stoichiometric matrices, mass balance, steady-state constraints, flux balance analysis, objectives, metabolic control analysis, KEGG, BioModels and SBML.

**Core scope:** Metabolic network reconstruction, reactions and compartments, S matrix, flux vector and Sv=0 assumption, exchange reactions and bounds, linear-programming objective and alternate optima, FBA versus kinetic modelling, flux variability concept, metabolic control coefficients and distributed control, KEGG pathways, BioModels repository and SBML exchange format, experimental flux validation.

**Evidence and reasoning:** Solve a small mass-balance/FBA example, compare alternative objectives and identify unmeasured or underdetermined fluxes.

**Progression:** Build on 11.G.03. Prepare 11.G.05.

### 11.G.05 — Disease Modelling, Artificial Intelligence and Systems Drug Discovery

**Student-facing description:** Connect disease networks and biomarkers with mathematical disease models, supervised and unsupervised learning, neural networks, target identification, repurposing and drug–target prediction.

**Core scope:** Disease-associated network modules and perturbations, representative mechanistic and statistical disease models, progression and response variables, supervised/unsupervised ML, neural networks concept, training/validation/test design, biomarker and target prioritisation, repurposing and interaction prediction, class imbalance, calibration, interpretability and independent experimental validation; use public benign educational examples.

**Evidence and reasoning:** Interpret model outputs and validation metrics, compare mechanistic and predictive models, detect leakage and distinguish associations from demonstrated therapeutic effects.

**Progression:** Build on 11.G.04. Prepare 11.G.06.

### 11.G.06 — Precision Medicine and Integrated Computational Biology

**Student-facing description:** Integrate personalised medicine, pharmacogenomics, multi-omics biomarkers, digital health, electronic health records, wearables, predictive modelling, privacy, bias and reproducibility.

**Core scope:** Personalised and precision medicine concepts, pharmacogenomics, patient-specific molecular profiles, disease stratification, biomarker validity, treatment-response prediction, digital health and electronic health records, wearable/remote-monitoring data, interoperability, missingness and measurement bias, consent/privacy, fairness and population generalisation, external/prospective validation and clinical oversight; no individual diagnosis or treatment recommendation.

**Evidence and reasoning:** Assess hypothetical health-data and model-validation scenarios, compare subgroup performance, distinguish technical accuracy from clinical utility and identify privacy risks.

**Progression:** Build on 11.G.05. Integrate Unit 11 and connect systems modelling to subsequent biotechnology and methods units.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Data science applications in biology, health and drug discovery | 11.G.01–02, 11.G.05–06 |
| Mathematical modelling of metabolic pathways | 11.G.03–04 |
| Mathematical modelling of disease | 11.G.03, 11.G.05 |
| Digital health and personalised medicine | 11.G.06 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

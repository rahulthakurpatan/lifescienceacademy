# Life Science Academy — Unit 11, Subunit 11.D: Molecular Modelling and Dynamics

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Explore computational representations of biomolecules, molecular mechanics, force fields, energy optimisation, conformational sampling and molecular dynamics simulations to understand molecular behaviour.

**Planned nodes:** 6. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.D.01 — Foundations of Molecular Modelling and Three-Dimensional Visualisation

**Student-facing description:** Interpret atomic coordinates, bond geometry, molecular coordinate systems and ball-and-stick, space-filling, ribbon and surface views using representative PyMOL and ChimeraX visualisations.

**Core scope:** Cartesian coordinates and distance, angles and dihedrals, coordinate units, molecular representations, chains and selections, surfaces, experimental versus predicted models, missing atoms and alternate conformations, conformers and visualisation choices, example PyMOL/ChimeraX concepts without version-specific dependence.

**Evidence and reasoning:** Calculate atomic distances and choose representations appropriate to molecular questions; interpret an illustrative structural view.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.D.02.

### 11.D.02 — Molecular Mechanics and Potential Energy Functions

**Student-facing description:** Explain potential-energy surfaces and classical molecular mechanics through bond stretching, angle bending, torsions, electrostatics and van der Waals terms.

**Core scope:** Classical approximation and limitations, harmonic bonds and angles, periodic torsions, Coulomb interactions and dielectric assumptions, Lennard–Jones attraction/repulsion, bonded versus non-bonded energy, potential-energy gradients and forces, units and additive approximations; quantum effects not generally captured.

**Evidence and reasoning:** Calculate illustrative energy terms, read energy-versus-distance curves and relate forces to energy gradients.

**Progression:** Build on 11.D.01. Prepare 11.D.03.

### 11.D.03 — Force Fields and Molecular Environment Modelling

**Student-facing description:** Compare AMBER, CHARMM, GROMOS and OPLS force fields, atom types, charges, parameterisation, explicit/implicit solvent, water models and periodic boundaries.

**Core scope:** Functional forms versus parameter sets, atom typing, partial charges, protonation assumptions and parameter compatibility, explicit versus implicit solvent, representative water models, ions, periodic boxes, minimum-image and cutoff concepts, long-range electrostatics including PME, transferability and sampling limitations.

**Evidence and reasoning:** Evaluate conceptual model choices, identify incompatible parameters and explain effects of solvent and boundary assumptions.

**Progression:** Build on 11.D.02. Prepare 11.D.04.

### 11.D.04 — Energy Minimisation and Conformational Sampling

**Student-facing description:** Compare local and global minima, steepest descent, conjugate gradients, conformational barriers, Monte Carlo sampling and Boltzmann distributions.

**Core scope:** Energy minimisation versus thermal dynamics, gradient methods, convergence criteria and local minima, conformational landscapes and barriers, Monte Carlo proposal/acceptance and Metropolis principle, Boltzmann weights, sampling versus optimisation, enhanced sampling overview and free-energy versus potential-energy distinctions.

**Evidence and reasoning:** Interpret landscapes and simple Boltzmann/acceptance calculations; compare minimisation and equilibrium sampling objectives.

**Progression:** Build on 11.D.03. Prepare 11.D.05.

### 11.D.05 — Principles of Molecular Dynamics Simulation

**Student-facing description:** Trace Newtonian motion, numerical integration, Verlet methods, initial velocities, time steps, ensembles, thermostats, barostats, equilibration and production trajectories.

**Core scope:** Forces and Newton's equations, Verlet and velocity-Verlet concepts, integration errors and timestep constraints, temperature and kinetic energy, NVE/NVT/NPT ensembles, thermostat/barostat roles and assumptions, initial coordinates and velocities, equilibration versus production, replicate simulations and boundary conditions.

**Evidence and reasoning:** Work a small conceptual integration step, compare ensembles and interpret energy/temperature traces for stability.

**Progression:** Build on 11.D.04. Prepare 11.D.06.

### 11.D.06 — Molecular Dynamics Analysis and Model Validation

**Student-facing description:** Analyse trajectories using RMSD, RMSF, radius of gyration, hydrogen bonds, solvent accessibility, conformational transitions and free-energy landscapes.

**Core scope:** Coordinate alignment before RMSD, reference choice, RMSF by residue, Rg and compactness, hydrogen-bond geometric criteria, SASA, trajectory clustering and collective variables, free-energy landscape from equilibrium probabilities with sampling caveats, convergence, autocorrelation, effective samples, replicas and experimental comparison.

**Evidence and reasoning:** Calculate simple RMSD/RMSF examples and interpret trajectory plots without equating a plateau with proof of convergence.

**Progression:** Build on 11.D.05. Bridge to subunit 11.E.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| 3D visualisation and simulation | 11.D.01, 11.D.05–06 |
| Basic molecular modelling concepts and molecular mechanics | 11.D.01–02, 11.D.04 |
| Force fields | 11.D.03 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

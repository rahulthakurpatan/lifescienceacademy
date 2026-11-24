# Life Science Academy — Unit 11, Subunit 11.B: Basic Concepts of Sequence Analysis

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Develop computational approaches for comparing biological sequences, detecting conserved regions, searching databases, constructing alignments and interpreting evolutionary and genomic relationships.

**Planned nodes:** 7. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.B.01 — Sequence Comparison, Identity, Similarity and Homology

**Student-facing description:** Distinguish identity, similarity and homology, relating conserved regions, substitutions and indels to orthologues, paralogues and xenologues.

**Core scope:** DNA, RNA and protein representations; aligned identity with explicit denominator, similarity dependent on scoring scheme; homology as common ancestry, orthology after speciation, paralogy after duplication, xenology involving horizontal transfer; conserved motifs, indels, divergence and chance similarity.

**Evidence and reasoning:** Calculate percent identity for a supplied alignment and distinguish sequence resemblance from evidence of evolutionary relatedness.

**Progression:** Build on relevant preceding computational nodes and biological foundations. Prepare 11.B.02.

### 11.B.02 — Sequence Pattern Recognition and Repeat Finding

**Student-facing description:** Identify direct, inverted, tandem and interspersed repeats, microsatellites, palindromes, low-complexity regions, dot plots, k-mers and motif searches.

**Core scope:** Repeat types and orientation, reverse complement versus textual palindrome, tandem repeats and microsatellites, interspersed repeat families, low-complexity masking, dot plots and window thresholds, k-mer counts, exact and approximate matching, motif degeneracy and false positives; representative repeat-finding resources.

**Evidence and reasoning:** Read dot plots, count k-mers, identify repeat orientation and explain masking trade-offs.

**Progression:** Build on 11.B.01. Prepare 11.B.03.

### 11.B.03 — Scoring Matrices and Principles of Sequence Alignment

**Student-facing description:** Explain substitution probabilities, log-odds scoring, PAM and BLOSUM matrices, gap-opening and gap-extension penalties and alignment scores.

**Core scope:** Match/mismatch scoring, amino-acid substitution frequencies, background frequencies and log odds, PAM evolutionary-distance convention, BLOSUM sequence-clustering convention, selecting matrices, linear and affine gap costs with stated convention, scores versus statistical significance.

**Evidence and reasoning:** Compute small alignment scores, compare matrix choices and explain PAM/BLOSUM numbering without treating them as interchangeable scales.

**Progression:** Build on 11.B.02. Prepare 11.B.04.

### 11.B.04 — Pairwise Sequence Alignment and Dynamic Programming

**Student-facing description:** Apply global, local and semi-global alignment through Needleman–Wunsch and Smith–Waterman matrices, recurrence, traceback and optimal scoring.

**Core scope:** Dynamic-programming decomposition, initialisation, match/mismatch and gap recurrence, global versus local zero reset, semi-global terminal-gap conventions, traceback and tied optima, affine-gap extension concept, complexity and assumptions, exact optimum relative to scoring scheme.

**Evidence and reasoning:** Fill small alignment matrices by hand, trace optimal paths and compare local and global results.

**Progression:** Build on 11.B.03. Prepare 11.B.05.

### 11.B.05 — Biological Database Searching with BLAST and FASTA

**Student-facing description:** Compare BLAST and FASTA heuristic searches, seed-and-extend logic, search variants, bit scores, E-values, coverage and interpretation of hits.

**Core scope:** BLASTN/P/X, TBLASTN/X, PSI-BLAST iterative profile concept, FASTA search algorithm versus FASTA format, word hits, extension and significance, raw and bit scores, E-value dependence on search space, query/subject coverage, identity, masking, database selection, multiple hits and contamination, sensitivity/speed trade-offs.

**Evidence and reasoning:** Interpret representative search output, compare E-values across search settings and distinguish significant similarity from functional proof.

**Progression:** Build on 11.B.04. Prepare 11.B.06.

### 11.B.06 — Multiple Sequence Alignment and Profile Analysis

**Student-facing description:** Compare progressive, iterative and consistency-based alignment, Clustal Omega, MUSCLE, MAFFT, guide trees, consensus, sequence logos, PSSMs and profile HMMs.

**Core scope:** Multiple alignment objectives and computational difficulty, progressive guide trees versus inferred phylogeny, iterative refinement and consistency, gap placement and poorly aligned regions, consensus and conservation, sequence logos and background assumptions, position-specific scoring matrices, HMM match/insert/delete states, alignment validation.

**Evidence and reasoning:** Read MSA and logo examples, compute simple consensus/PSSM values and assess ambiguous regions before downstream inference.

**Progression:** Build on 11.B.05. Prepare 11.B.07.

### 11.B.07 — Sequence-Based Taxonomy and Comparative Genomics

**Student-facing description:** Connect barcoding, 16S rRNA, ITS, ANI, synteny, orthologous groups, core/accessory genomes and pangenomes with taxonomy and phylogenetic inference.

**Core scope:** Marker choice and resolution, COI and plant barcodes as context, 16S/ITS, average nucleotide identity and contextual thresholds, genome quality and contamination, orthologous gene sets, synteny, genome rearrangements, core/accessory/pangenome definitions and sampling dependence, sequence-based phylogenetic application; detailed tree algorithms 11.C.06 and biological taxonomy Unit 9.

**Evidence and reasoning:** Compare marker and genome evidence, interpret synteny and pangenome diagrams and explain why a single similarity threshold is not universally decisive.

**Progression:** Build on 11.B.06. Bridge to subunit 11.C.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Database searches, BLAST and FASTA | 11.B.05 |
| Sequence identity, similarity, homologues, orthologues and paralogues | 11.B.01 |
| Repeat finding | 11.B.02 |
| Scoring matrices | 11.B.03 |
| Pairwise sequence alignments | 11.B.04 |
| Multiple sequence alignments | 11.B.06 |
| Applications in taxonomy, phylogeny and comparative genomics | 11.B.07; tree methods 11.C.06 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

# Life Science Academy — Unit 11, Subunit 11.A: Major Bioinformatic Resources

## Sources and scope

- Official revised CSIR–UGC–DBT NET Life Sciences & Biotechnology syllabus, printed page 12, Unit 11: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260121115025355Merged_Syllabus_CSIR-DBT_21Jan2026.pdf
- All seven revised headings and explicit topic groups were checked against the official page before deployment. The 42-node breakdown is Academy instructional design, not an official subdivision. Digital health is explicitly included in 11.G.06.
- Older CSIR/MP SET topic overlaps are supported through cross-links to molecular biology, genetics, evolution and methods; the older Unit 11 is Evolution and Behavior, not a standalone bioinformatics unit.
- Reference starting points for full lessons: NCBI (https://www.ncbi.nlm.nih.gov/), EMBL-EBI (https://www.ebi.ac.uk/), UniProt (https://www.uniprot.org/), wwPDB (https://www.wwpdb.org/), InterPro (https://www.ebi.ac.uk/interpro/), Gene Ontology (https://geneontology.org/), AlphaFold DB (https://alphafold.ebi.ac.uk/), PubChem (https://pubchem.ncbi.nlm.nih.gov/), BioModels (https://www.ebi.ac.uk/biomodels/), SBML (https://sbml.org/); Durbin et al., Biological Sequence Analysis; Lesk, Introduction to Bioinformatics; Leach, Molecular Modelling; Alon, An Introduction to Systems Biology. Verify specific source claims, resource availability, versions and tool capabilities during lesson development.

## Subunit contract

Explore the foundations of bioinformatics and the organisation, retrieval and interpretation of biological information using sequence, gene expression, molecular structure and functional annotation databases.

**Planned nodes:** 5. See [Unit 11 master map](unit-11-bioinformatics-computational-biology-subunit-map.md) for full syllabus traceability and quantitative learning map.

## Node contracts

### 11.A.01 — Foundations of Bioinformatics and Biological Data Management

**Student-facing description:** Explore bioinformatics applications, biological data types, primary and derived databases, identifiers, metadata and FASTA, FASTQ and GenBank formats.

**Core scope:** Distinguish sequence, read, expression, structural and annotation data; accession versus version and stable identifier; primary archives versus curated and integrated resources; FASTA headers, FASTQ quality encoding and Phred scores, GenBank feature tables, metadata, provenance, reference assemblies and reproducible retrieval.

**Evidence and reasoning:** Read example records, calculate simple Phred error probabilities and identify metadata or identifier mismatches.

**Progression:** Build on biomolecular, genetic and molecular biology foundations; introduce computation without programming prerequisites. Prepare 11.A.02.

### 11.A.02 — Nucleotide, Protein and Genome Sequence Databases

**Student-facing description:** Retrieve and compare sequence and genome records from NCBI, GenBank, ENA, DDBJ, RefSeq, UniProt and Ensembl, interpreting accession numbers and cross-references.

**Core scope:** INSDC collaboration, nucleotide archives, RefSeq curation and reference assemblies, UniProtKB reviewed Swiss-Prot and unreviewed TrEMBL, isoforms, taxonomic identifiers, Ensembl genome browsers, coordinates and strand, annotations and cross-database identifiers; avoid equating a predicted protein with experimentally verified function.

**Evidence and reasoning:** Trace a public example gene from nucleotide to protein record and genome coordinates; compare provenance and annotation evidence.

**Progression:** Build on 11.A.01. Prepare 11.A.03.

### 11.A.03 — Gene Expression and Functional Genomics Databases

**Student-facing description:** Explore GEO, ArrayExpress, Expression Atlas and SRA, distinguishing raw reads, microarray and RNA-seq expression data, experimental metadata and processed profiles.

**Core scope:** GEO series/sample/platform identifiers, SRA run records, ArrayExpress/BioStudies and Expression Atlas, sample conditions and biological replicates, raw counts versus normalised expression, microarray probes, bulk and single-cell context, batch effects, study design and public data access; detailed statistical workflows in 11.G.02 and methods in Unit 14.

**Evidence and reasoning:** Read sample metadata and expression matrices, compare conditions and spot missing controls or batch confounding.

**Progression:** Build on 11.A.02. Prepare 11.A.04.

### 11.A.04 — Macromolecular Structure Databases and Structural Resources

**Student-facing description:** Compare PDB, wwPDB, RCSB PDB, PDBe, BMRB, EMDB and AlphaFold DB records, structural formats and experimental versus predicted structures.

**Core scope:** PDB archive and partner portals, PDBx/mmCIF and legacy PDB coordinates, experimental method, resolution where applicable, chains, biological assembly versus asymmetric unit, ligands, missing residues and validation reports; BMRB NMR data, EMDB density maps and predicted structure confidence in AlphaFold DB; versions and provenance.

**Evidence and reasoning:** Inspect illustrative structural records, distinguish map, coordinates and model, and compare evidence and quality indicators.

**Progression:** Build on 11.A.03. Prepare 11.A.05.

### 11.A.05 — Sequence Pattern, Protein Family and Functional Databases

**Student-facing description:** Interpret PROSITE, Pfam, InterPro, PRINTS, SMART, conserved domains, motifs, sequence profiles, Gene Ontology and KEGG annotations.

**Core scope:** Motif versus domain versus family, regular-expression patterns, fingerprints and profile HMMs, PROSITE patterns/profiles, Pfam, InterPro integration, PRINTS and SMART, conserved-domain resources, GO terms and evidence codes, KEGG pathways; database access and release changes, false positives and domain architecture.

**Evidence and reasoning:** Compare motif and domain matches and use evidence codes to distinguish direct experiments from inferred annotation.

**Progression:** Build on 11.A.04. Bridge to subunit 11.B.

## Syllabus topic mapping

| Official topic group (paraphrased) | Assigned nodes |
|---|---|
| Sequence databases | 11.A.01–02 |
| Gene expression databases | 11.A.03 |
| 3D structure databases | 11.A.04 |
| Sequence pattern databases | 11.A.05 |

## Editorial and progression contract

- Curriculum architecture only, not completed textbook lessons. No fabricated lesson links, sitemap changes or chapter-completion counter changes.
- Original accessible connected academic English, BSc foundations to MSc/NET/SET depth, no programming prerequisite; define mathematical notation and units, develop algorithms step by step, include original diagrams, worked examples, representative public records and outputs, limitations, misconceptions and explained Part B/Part C-style questions.
- Balanced conceptual workload: 5–7 nodes per subunit, 42 total. Retain all approved topics and explicit digital health coverage. Examples and tool names support scientific concepts; verify current versions before publication and avoid presenting predictions as experimental proof.
- Boundaries: Unit 1 owns biomolecular chemistry and structure foundations; Units 2–3 genome organisation and molecular mechanisms; Unit 4 signalling and disease biology; Unit 8 inheritance/mutation mechanisms; Unit 9 taxonomy/evolution; Unit 10 ecological models; Unit 14 experimental and statistical methods. Unit 11 owns computational representation, inference, algorithms, validation and systems integration.
- Computational results are hypotheses or evidence with stated assumptions, uncertainty, provenance and validation. Use public non-sensitive educational examples; protect health-data privacy and distinguish model outputs from clinical decisions. No actionable optimisation of harmful agents or personal clinical guidance.

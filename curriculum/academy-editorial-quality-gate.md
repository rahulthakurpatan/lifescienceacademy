# Life Science Academy — Scientific Teaching Quality Gate (Manual + Automation)

**Authority:** This operational editorial standard implements the user's no-thin-content requirement across both manual ChatGPT runs and hourly builder runs. Adopted 2026-11-22 after a comparative audit exposed disproportionate table-driven brevity in Node 1.A.2.22.

## 1. The invariant

The Academy teaches the scientific story, from a novice's first question to the reasoning depth needed for CSIR-NET Life Sciences, revised Life Sciences & Biotechnology where applicable, and State SET Life Sciences. The goal is *understanding*, not filling menu items, sections, table rows, or a character-count quota.

A node should guide the learner through: motivating observation → question and prerequisite concepts → chronological or causal discovery → experiments/evidence → formal theory and mechanisms → mathematics/derivations with units and approximations → independently worked examples → relevant authentic biological interpretation → limitations/exceptions → explained reasoning questions → consolidation and next-topic link. Include only stages genuinely relevant to this specific node. Good English is simple, humane, precise, connected and academically serious.

**PUBLISHING RULE: science and teaching quality outrank run cadence.** If a node cannot meet the full quality standard in one run, save an isolated recoverable draft and report it; do not merge thin content to main simply to publish on schedule.

## 2. Teaching prose must be evaluated separately from presentation volume

**DO NOT use raw HTML characters or counts of sections, questions, table cells or SVG markup as stand-alone quality evidence.** Measure and inspect:
- Visible narrative/prose words *outside tables, question option lists, metadata, CSS/JS and diagrams*.
- The length and clarity of coherent teaching passages, including intermediate reasoning and bridges.
- Whether the student can derive important formulas rather than merely read them.
- Whether at least one experimentally or scientifically grounded worked explanation is present for each substantial claim.
- Whether questions and examples explain *why*, what assumptions apply and why distractors fail.
- Whether there are substantial missing conceptual links hidden by high section/question counts.

For broad integrative nodes, use substantial completed Academy chapters as **comparators**, never as mandatory word-count quotas. Audited examples (actual 2026-11-22 GitHub HTML extraction):
- Node 1.A.2.12: ~22,472 visible narrative words outside tables; ~488 paragraphs; ~2% of article HTML from table markup.
- Node 1.A.2.18: ~13,711 visible narrative words outside tables; ~307 paragraphs; ~2% from tables.
- Node 1.A.2.21: ~8,430 visible narrative words; ~147 paragraphs; ~7% from tables.
- Node 1.A.2.22: only ~3,233 visible narrative words; ~77 paragraphs; ~45% article HTML from tables. **This is BELOW THE DESIRED DEPTH STANDARD for its broad integrative scope and needs substantive re-development.**

These are baseline diagnostic measurements, not scientific statements or mechanical length minimums. More characters alone do not repair superficial instruction. Filler, duplicated paragraphs, repetitive examples or artificial section inflation are prohibited.

## 3. Independent scientific teaching review: mandatory publication questions

1. **Prerequisites** — Can a beginner understand terminology and each step without importing outside assumptions?
2. **Scientific question** — Why does the concept need to exist? Where did historical observations/experiments challenge the earlier model? Where historical chronology is not relevant, is there a causal learning sequence?
3. **Theory** — Does each major concept receive enough coherent explanation for a student to explain it back without memorizing a slogan? Does it answer WHY as well as WHAT?
4. **Mechanisms** — Are causal explanations clearly separated from analogy, correlation, empirical observation and theory?
5. **Mathematics** — Are equations derived where meaningful? Is every symbol, sign, unit, assumption, numerical conversion and domain of validity explained? Independently check numerical answers.
6. **Evidence** — Are historical and experimental claims linked to trustworthy specific sources, and are inferences no stronger than evidence?
7. **Biology** — Is each biological application authentic, and are ion/configuration/oxidation-state models distinguished from protein/cell physiology?
8. **Exceptions** — Are important departures, boundary conditions, alternate models and uncertainty included?
9. **Pedagogy** — Are substantial narrative paragraphs present between examples/questions, with natural explanations and transitions? Do sections genuinely flow?
10. **Student examination practice** — Are original MCQs, assertion–reason, calculations and data-interpretation problems nontrivial? Are correct and wrong-option explanations sufficiently instructive? Never label as official past year without verified provenance.
11. **Editorial independence** — Is content substantially original, not copied, not redundant with neighboring nodes, and not a rephrased list of repeated definitions?
12. **QA & publication** — Does the finished lesson have preserved reader controls, valid anchors, accessible diagrams, canonical, links, sitemap/menu consistency and an idempotent Git update?

**If the broad chapter fails narrative-depth, scientific-context, worked-reasoning or evidence checks, it fails the gate even if it has 60 questions and 200,000 HTML characters.**

## 4. Required final QA evidence (record in checkpoint or publication report)

Report **separately**:
- Actual visible teaching narrative word estimate (excluding tables/UI code) and how derived.
- Total article visible words, table-heavy share warning and proportion of truly explanatory prose.
- Comparison with at least one best adjacent/exemplar chapter of relevant scope.
- Specific theory sections and derivations genuinely covered; not simply their headings.
- Worked examples with nontrivial steps; distractor-level explanations in practice.
- Credible references used to check statements and original diagrams audited.
- Tests performed and those not performed; never assert live Pages verified from a commit alone.
- Any unresolved academic gap. If unresolved, **do not publish**.

Typical target is comparable explanatory care to the strongest relevant published chapters, not a fixed number of characters. Escalate to a careful human-like review if the article is unusually short or heavily table-driven for its breadth.

## 5. Mandatory repair note: Node 1.A.2.22

This already-published chapter is **flagged for substantial narrative re-development** following user feedback. Do not delete or duplicate it, and do not claim a new node should take priority solely because Node 22's menu status is "published".

When a manual or automatic execution has time and explicit scope to repair it, improve the **existing** path `notes/unit-01/subunit-1a/topic-1a2/node-22-electronic-configuration-biology-integrated-csir-net-practice.html` in a safe branch, retaining page URL, reader design, menu, sitemap, and correct science.

Specific gaps to address before clearing the quality hold:
- A connected, motivating and experimentally grounded narrative of how ion gradients/electronic states inform biological interpretations.
- Carefully defined and derived electrochemical potential and Nernst relation within topic scope; multiple thorough numerical solutions with assumptions, activity and voltage signs.
- Deep but appropriately bounded explanations of Na/K ATPase stoichiometry, K/Na selectivity, Mg–ATP chemical association and calcium as second messenger, with molecular/transport evidence clearly distinguished from atomic electron configuration.
- Detailed Fe/Cu redox and heme/iron-sulfur contexts, avoiding false spin-only or simplistic oxidation-state claims; compare measured evidence to models.
- Convert short, table-cell-only 'worked examples' and one-line case summaries into genuinely solved stories where they teach hard concepts. Explain why plausible wrong exam choices fail.
- Expanded authentic interpretation problems, case histories, comparison charts/diagrams only when pedagogically useful, and citations attached to important factual claims.
- Preserve topic boundary: do not turn Node 22 into full membrane physiology, all coordination chemistry or Topic 1.A.3 periodic-properties lessons.
- Full scientific and technical QA, latest main refresh and conditional non-force commit required. Only mark quality repair complete after real expansion and verification, not a character-count increase.

## 6. Manual and scheduled executions

Before choosing a node, inspect main SHA, actual chapter, menu, roadmap, sitemap, checkpoint, branches and active drafts. An existing quality-hold item is a **priority repair** to address before advancing the node sequence, provided the execution can genuinely meet the standard without sacrificing quality. Preserve concurrent work. If it cannot be repaired in the current run, report/preserve a resumable draft instead of pretending it is fixed.

After the repair, clear the hold only if the newly strengthened text is *substantively* better, all QA tests pass and the main-branch commit is independently verified. Do not falsely change the number of published nodes, and never add a duplicate URL to sitemap.

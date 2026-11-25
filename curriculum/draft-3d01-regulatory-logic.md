# Regulatory logic and quantitative foundations

## Positive and negative control

A regulator's sign is defined by the effect of its active form on a specified target. A transcriptional activator increases output relative to a suitable baseline; a repressor reduces it. An activator may facilitate productive transcription by helping recruit machinery or stabilising a productive complex. A repressor can obstruct access or another required interaction. Neither label determines whether expression is exactly zero or maximal.

An environmental signal can increase transcription by activating an activator or by inactivating a repressor. Both produce induction, yet their direct regulatory signs differ. A signal can decrease output by activating a repressor or inhibiting an activator. Consequently the direction of a wild-type response cannot by itself establish positive or negative control.

Consider two hypothetical systems that produce 5 RNA units without signal and 90 with signal. In system X, deletion of the sole regulator gives 90 units in both conditions; in system Y, it gives 5 in both. Assuming intact promoters and no compensating factors, X uses negative inducible control and Y uses positive inducible control. The mutant is the discriminating evidence.

## Effectors and four regulatory architectures

An inducer is a signal that promotes target expression in the specified context. A classical corepressor promotes the repressive activity of a regulator. Allosteric ligand binding can alter the regulator's active fraction without changing its total abundance. If 100 nM of a regulator changes from 80% active to 5% active, the active pool falls from 80 to 5 nM. The extracellular nutrient need not be the direct ligand: allolactose is the physiological inducer of the classical lactose system. The specific lac mechanism is treated in 3.D.02.

| Model | No signal | Signal present | Sole regulator absent |
|---|---|---|---|
| Negative inducible | Low | High | High in both |
| Positive inducible | Low | High | Low in both |
| Negative repressible | High | Low | High in both |
| Positive repressible | High | Low | Low in both |

The table assumes an intact basal promoter and one relevant regulator. In the negative inducible system the signal inactivates repression; in the positive inducible system it activates stimulation. In the negative repressible system the corepressor activates repression; in the positive repressible system the signal inhibits stimulation. Real systems can combine factors. If high expression requires an active activator and an inactive repressor, removing repression alone may be insufficient.

## Binding and output

For R + D ⇌ RD, Kd = [R][D]/[RD] in the dilute single-site model. The target balance is Dtotal = [D]+[RD]. Therefore fractional occupancy θ = [R]/(Kd+[R]), using free active regulator rather than total protein. At R = Kd, θ = 0.5. If R = 20 nM and Kd rises from 10 to 40 nM, occupancy falls from 2/3 to 1/3.

If the unoccupied transcription rate is 100 units/min and the repressor-bound rate is 5, the mean production rate is 100(1−θ)+5θ. At θ = 0.8, output is 24; at θ = 0.2, it is 81. An activator instead has a greater bound-state than unbound-state rate. Binding is not equivalent to activation.

A Hill-type model θ = Rⁿ/(Kⁿ+Rⁿ) can describe apparent steepness but its exponent is not necessarily a count of bound molecules. A steep output curve may also arise from coupled steps downstream of binding.

## RNA and protein balance

For a fixed production rate s (RNA molecules per cell per minute) and first-order removal constant d (min⁻¹), the RNA balance is dM/dt = s−dM. At steady state Mss = s/d. If production ceases, M(t)=M₀e^(−dt) and the half-life is ln(2)/d. After a step in production with unchanged d, M(t)=Mss,new+(M₀−Mss,new)e^(−dt).

A gene producing 4 RNA molecules/min with d=0.10 min⁻¹ has steady RNA abundance 40. If production increases to 16, the new steady abundance is 160. After one half-life (6.93 min), abundance is 100, and after two half-lives it is 130. Thus induction in measured abundance need not be instantaneous even if production changes abruptly.

For protein production per available RNA k and first-order protein loss γ, dP/dt=kM−γP. At steady state Pss=ks/(dγ). A doubling of s and halving of d raises RNA abundance fourfold; an additional 1.5-fold increase in k raises protein sixfold if γ is unchanged. Increased protein turnover can lower abundance even when synthesis remains unchanged. These models presume stable rate constants, a consistent abundance unit and first-order removal; effective dilution in growing cells may also contribute.

## Evidence and checkpoint interpretation

Transcriptional control changes RNA production, post-transcriptional control changes RNA processing, availability or lifetime, and translational control changes protein production from available RNA. A protein modification may alter activity without changing abundance. Measuring steady RNA alone cannot separate production from decay. Measuring steady protein alone cannot separate production from removal.

If new RNA synthesis is unchanged but RNA lifetime increases, stabilisation is a plausible primary mechanism. If RNA remains available but new protein synthesis per RNA falls, translational control is supported. If protein synthesis is unchanged but protein lifetime decreases, turnover is implicated. Such interpretations require appropriate normalisation and matched controls.

Bacterial operons can coordinate transcription of linked genes; a regulon consists of transcription units sharing control, whether or not they are adjacent. Phage and viral expression programmes can order events over time; eukaryotic control can additionally exploit chromatin and nuclear RNA processing. These general concepts prepare the subsequent specialised chapters.

Sources: Alberts et al., Molecular Biology of the Cell, chapter 7 (https://www.ncbi.nlm.nih.gov/books/NBK21057/); How Genetic Switches Work (https://www.ncbi.nlm.nih.gov/books/NBK26872/); Jacob and Monod 1961 (https://pubmed.ncbi.nlm.nih.gov/13718526/); OpenStax Biology 2e sections 16.1–16.6.

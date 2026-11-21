# Working manuscript — 1.A.2.06 Principal Quantum Number n: Shells, Scale and Energy

> **ARCHIVED RESEARCH DRAFT: Node 1.A.2.06 has been fully published on GitHub main.** Publication commit: 76f0ef6445551761a23602a09eb86aa8fd2d0146. This file documents preliminary research only. Do not develop, republish or relink Node 06 from this branch; verify current main before starting the next genuinely unpublished Node.
>
> Target canonical slug: `notes/unit-01/subunit-1a/topic-1a2/node-06-principal-quantum-number-shells-scale-energy.html`.

## Scope, dependencies and editorial boundary

Previous Node 05 established a stationary wavefunction and the Born interpretation. This Node explains the **principal quantum number** and the experimentally meaningful shell/energy pattern of one-electron Coulomb systems, then carefully qualifies which claims transfer to multi-electron atoms. Node 07 will develop azimuthal quantum number and subshells; Node 09 will derive full shell capacities. Do not teach an electron as a planet in a literal circular orbit. Avoid implying that all electrons with the same n have a single radius or that all many-electron orbitals with the same n are degenerate.

## Chronological scientific narrative

### 1. Why atomic spectra demanded discrete energy states

Hydrogen produces separated emission lines rather than a continuous rainbow. Balmer (1885) found a numerical regularity among visible hydrogen wavelengths; Rydberg later expressed broader line patterns with a compact reciprocal-wavelength formula. These empirical successes preceded quantum mechanics and required explanation. Spectral lines record **differences between energy levels**, not pictures of an electron's path.

### 2. Bohr's n was an early organizing step, not the final atomic model

In 1913 Bohr introduced discrete permitted energies for hydrogen. His model explained the gross hydrogen spectrum, but its fixed circular trajectories cannot be the final account of an electron's state. De Broglie's matter waves, Schrödinger's 1926 wave mechanics and Born's probability interpretation led to an orbital account. Modern n labels a family of allowed bound states and their radial scale and energy behavior in the hydrogenic case. It does not prescribe a measured path.

### 3. Definition and allowed values

The principal quantum number is a **positive integer** n = 1, 2, 3, ... for bound hydrogenic electronic states. There is no n = 0, negative n or fractional n among these states. The ground bound level is n = 1. Increasing n generally corresponds to less tightly bound hydrogenic energy levels and more extended probability distributions. For a hydrogenic bound state, n alone does **not** uniquely specify its wavefunction; additional quantum numbers are needed, developed in the next Nodes.

### 4. Historical shell letters

K, L, M and N denote n = 1, 2, 3 and 4 respectively; the sequence continues O for 5, P for 6, Q for 7. These labels are historical shell terminology, not new types of quantum numbers. A shell is a collection of states sharing n, not a rigid spherical wall or a circular rail.

| n | Shell label | A useful first statement |
|---|---|---|
| 1 | K | Lowest hydrogenic bound energy |
| 2 | L | Higher bound energy than n=1 |
| 3 | M | Higher bound energy than n=2 |
| 4 | N | Higher bound energy than n=3 |

### 5. The Coulomb potential and why Z matters

For a nonrelativistic electron interacting with a point nucleus of charge +Ze, the Coulomb potential energy is V(r) = -Ze²/(4πε₀r). The idealized **hydrogenic** family comprises H, He⁺, Li²⁺ and other systems with one electron, ignoring corrections such as finite nuclear mass, fine structure and QED. For a nucleus of mass M, use the electron–nucleus reduced mass μ = mₑM/(mₑ+M), not automatically mₑ when high precision is required.

### 6. Bound-state energies and the meaning of a negative sign

For the idealized one-electron Coulomb Hamiltonian,

E_n = - μZ²e⁴ / [2(4πε₀)²ħ²n²].

When μ ≈ mₑ this is approximately E_n ≈ -(13.6057 eV)Z²/n². The zero is the ionization threshold at infinite separation; negative E means the electron is bound relative to that reference. A **higher** energy state can therefore have a numerically less negative energy, e.g. -3.40 eV is higher than -13.61 eV. It is incorrect to claim the electron has 'negative kinetic energy': kinetic energy is nonnegative; the total energy is negative because potential energy is sufficiently negative.

### 7. Why n² appears, and the limits of the simple equation

In the nonrelativistic Coulomb solution, the bound energy depends only on n (and Z and μ). This special degeneracy does not hold as a general rule for multi-electron atoms, where electron-electron repulsion, shielding and penetration change orbital energies. Even hydrogenic levels are split by fine-structure, hyperfine and external-field effects beyond the idealized model. The equation is therefore a model with stated assumptions, not a universal exact atomic law.

### 8. Transition energies and photon wavelengths

For a transition from n_i to n_f with n_i > n_f, the atom loses energy ΔE_atom = E_nf - E_ni < 0; the emitted photon's energy is E_γ = E_ni - E_nf > 0. For an absorption transition n_f > n_i, the atom gains positive energy and absorbs a photon of the corresponding energy. Photon energy E_γ = hν = hc/λ in vacuum. Do not swap the initial and final indices or attach a negative energy to an emitted photon.

For hydrogen with negligible reduced-mass correction, n=3 → n=2: E_3≈-1.5117 eV, E_2≈-3.4014 eV; emitted E_γ≈1.8897 eV and λ≈656.2 nm using hc≈1239.84 eV·nm (the Balmer-alpha line). Exact observed wavelengths depend on convention, precision and corrections.

### 9. Ionization and the n → infinity limit

As n increases without bound, E_n approaches 0 from below. This limit is the continuum threshold, not a literal ordinary shell with n=∞. Removing an electron from hydrogen n=1 to the zero-energy threshold requires about 13.6 eV; from n=2 it requires about 3.40 eV in the same idealized model. The ionization energy is the positive energy required, not the negative bound-state energy.

### 10. Size: why 'the radius of shell n' is dangerous language

The characteristic hydrogenic length scale is a_μ/Z, where a_μ = 4πε₀ħ²/(μe²) is the reduced-mass Bohr radius; for ordinary hydrogen, a₀≈0.529 Å. The probability distribution is extended, not a thin shell. For a hydrogenic stationary state, the mean electron–nucleus distance is

⟨r⟩_(n,l) = [a_μ/(2Z)] [3n² - l(l+1)].

Thus n strongly influences size but **n alone does not determine one exact mean radius**: l also matters. In the special 1s case (n=1,l=0), ⟨r⟩=3a_μ/(2Z), whereas the most probable radial distance is a_μ/Z. Never confuse most probable radius with mean radius. The radius n²a_μ/Z from the Bohr model is not a universal exact orbital radius; it does equal the most probable radial distance of certain circular states with l=n-1, and the full wavefunction matters.

### 11. Scaling across hydrogen-like ions

At fixed n, the idealized energy magnitude scales approximately as Z² and the characteristic spatial scale as 1/Z. He⁺ has Z=2 and its n=1 bound energy is approximately -54.4 eV, four times hydrogen's magnitude. Its characteristic radius is approximately half the hydrogen value (small reduced-mass differences aside). These comparisons **do not** apply by substituting the atomic number of neutral multi-electron helium into the hydrogenic formula.

### 12. Probability, expectation and observation

An orbital probability density |ψ|² tells where a position measurement may find the electron. It does not identify a deterministic path. The probability that an electron lies between radii r and r+dr depends on the **radial probability density** P(r)=r²|R_nl(r)|² (for normalized spherical harmonics); the factor r² arises from the spherical volume element. A pointwise maximum of |ψ|² need not coincide with the maximum of P(r). For 1s, |ψ|² is largest at the nucleus, but P(r) is zero at r=0 and peaks at r=a_μ/Z.

### 13. Biological context: appropriate and inappropriate transfers

Discrete electronic energies underpin absorption and emission spectroscopy and the quantum basis of chemical bonding; however, electronic states in proteins, chromophores, metal centers and multi-electron atoms are **not** accurately described by assigning each electron the simple hydrogenic E_n formula. The quantum-number language is foundational vocabulary, not a complete molecular or biological model. A transition in a biological pigment may involve molecular orbitals, vibrational coupling and a local environment; distinguish these phenomena from isolated hydrogen spectral lines.

## Original worked examples — independently check all final numerics before publishing

1. **Allowed n.** Among -1, 0, 1, 1.5, 3, only 1 and 3 are permitted principal quantum numbers for bound hydrogenic states.
2. **Shell identification.** n=4 is the N shell; n=2 is L.
3. **Hydrogen level ratio.** E_2/E_1=1/4, where both energies are negative; the n=2 state is less tightly bound.
4. **Hydrogen E_4.** -13.6057/16≈-0.85036 eV.
5. **Hydrogen ionization from n=3.** Required threshold energy = 13.6057/9≈1.51174 eV.
6. **He⁺ E_2.** -13.6057(2²)/(2²)≈-13.6057 eV; numerical equality with hydrogen n=1 is specific to the idealized Z²/n² scaling.
7. **Li²⁺ E_3.** -13.6057(3²)/(3²)≈-13.6057 eV under the same assumptions.
8. **H absorption 1→2.** ΔE=13.6057(1-1/4)≈10.2043 eV; corresponding wavelength ≈121.5 nm, ultraviolet.
9. **H emission 4→2.** Eγ=13.6057(1/4-1/16)≈2.5511 eV; λ≈486.0 nm (Balmer-beta, approximated).
10. **H 1s mean distance.** ⟨r⟩=3a₀/2≈0.7935 Å, not 0.529 Å.
11. **H 2s mean distance.** ⟨r⟩=(a₀/2)(3·4)=6a₀≈3.174 Å.
12. **H 2p mean distance.** ⟨r⟩=(a₀/2)(12-2)=5a₀≈2.645 Å; same n but different l and mean radius.
13. **He⁺ 1s characteristic radius.** a₀/2≈0.2645 Å.
14. **Hydrogen transition 5→2.** Eγ=13.6057(1/4-1/25)≈2.8572 eV; λ≈433.9 nm.
15. **Energy ordering.** -0.85 eV is higher than -1.51 eV, even though its absolute value is smaller.

## Misconceptions to address explicitly

- 'n=0 is the innermost shell' — false; n starts at 1.
- 'An orbital is a thin Bohr ring' — false; it is a spatial probability amplitude.
- 'A negative E means a negative kinetic energy' — false; the zero of total energy is the ionization limit.
- 'All orbitals with the same n have the same radius' — false; expectation values also depend on l.
- 'All orbitals with the same n have the same energy in every atom' — false; hydrogenic degeneracy is special.
- 'A larger n is always physically farther from the nucleus at every instant' — false; distributions overlap.
- 'The 13.6 eV formula is exact for every element' — false; hydrogenic and approximation assumptions matter.
- 'n is the number of electrons in the shell' — false; n labels a quantum state family.
- 'The most probable radius is the mean radius' — false even for hydrogen 1s.
- 'The Balmer line is the energy of n=3' — false; lines encode differences of two levels.

## Planned original scientific SVGs (must implement and validate in final HTML)

1. Horizontal energy-level diagram n=1..5 plus E=0 continuum, with correctly spaced E∝-1/n² lines, labelled 3→2 Balmer emission and 1→2 absorption.
2. Radial-probability comparison for 1s versus 2s (both curves correctly normalized and qualitatively shaped; 2s has one radial node).
3. Hydrogen versus He⁺ level scaling using a common zero and consistent energy-axis labels.
4. Historical sequence: Balmer → Rydberg → Bohr → Schrödinger/Born, clearly distinguishing observations from successive models.

## Final chapter requirements before publication

Develop this foundation into a complete reader-ready HTML chapter matching the prior Node 05 UX, including extensive original solved examples, explained MCQs with answer key and plausible distractor analysis, rigorous misconception clinic, biological case studies with boundaries, integrated challenges, full references, metadata, TOC, diagrams and responsive interactions. The final HTML must be evaluated against Node 05 as a depth benchmark; **this draft is intentionally not sufficient to publish**.

## Authoritative references to verify and cite in final HTML

- OpenStax Chemistry 2e, §6.3 Development of Quantum Theory: https://openstax.org/books/chemistry-2e/pages/6-3-development-of-quantum-theory
- OpenStax Chemistry 2e, §6.4 Electronic Structure of Atoms: https://openstax.org/books/chemistry-2e/pages/6-4-electronic-structure-of-atoms-electron-configurations
- NIST Atomic Spectra Database: https://physics.nist.gov/asd
- NIST CODATA constants: https://physics.nist.gov/cuu/Constants/
- CSIR-HRDG Life Sciences syllabus: https://www.csirhrdg.res.in/SiteContent/ManagedContent/ContentFiles/20260129163159108LS_Sylbs_29Jan2026.pdf

**Next action:** Convert into a complete chapter HTML on this feature branch; check every equation, number, source and figure; only then recheck main/menu/sitemap/roadmap and publish if there is no manual overlap.

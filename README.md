# Dual-Frame Research Group: Σ-Order Research Program Hub
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18027076.svg)](https://doi.org/10.5281/zenodo.18027076)

---

## Naming note (Σ-Order transition)

This research program historically used the name **Dual-Frame Theory (DFT)**.
Because “DFT” is widely associated with *density functional theory*, the public-facing
name of the framework is now **Σ-Order theory (ΣO)**.

The term **Dual-Frame** remains valid when referring specifically to the dual-projection
structure (Temporal / Spatial frames), but the overall theoretical framework is indexed
under **Σ-Order** terminology.

**Conventions used across repositories and papers:**

- First introduction: **Σ-Order theory (ΣO)**
- Formal/technical contexts: **Σ** (e.g., **Σ₂**, **Σ₃**)
- Prose, titles, and narrative text: **Σ-Order** (abbrev: **ΣO**)

This is a *naming/terminology transition only*: it does not change any existing claims,
verification standards, DOIs, or repository lineage. Where older repositories or documents
use “DFT”, interpret it as referring to the same underlying framework, now indexed under
Σ-Order terminology.

---

> **Repository status:** Early-stage research program maintained by a non-dedicated researcher. 
> Documentation reflects conceptual architecture and ongoing work. Not all listed repositories 
> are public yet. Completeness claims (e.g., `dft-radiation` C1–C5) are falsifiable but 
> under active stress-testing.

## Program Structure

This repository indexes a **single developmental research program**, but not all
repositories operate at the same theoretical level.

- **Σ-Order Theory (ΣO):** the **post-projection**, limits-first framework.
  It preserves structural residue beyond standard QM, exposes admissibility
  boundaries clearly, and serves as the main reduced diagnostic layer of the program.
  However, relative to the deeper carrier level, it is **degenerate**: it does not
  retain the full local admissibility structure needed for complete mechanism.

- **Compact-fiber / carrier reconstruction:** the **deeper branch** of the program,
  aimed at recovering local admissibility structure closer to the Natural Reference
  System (NRS) level described in Larson’s Reciprocal System of Theory (RST). This branch
  addresses mechanisms that the degenerate post-projection layer cannot adequately
  generate on its own, especially in areas such as magnetism, matter and gravity.

- **Dual-Frame Theory (DFT):** the historical predecessor of the ΣO branch.
  Older repositories or documents using “DFT” should be understood in that lineage.

These branches are **continuous parts of one research program**, not unrelated
theories. The ΣO branch is especially useful for exposing admissibility boundaries,
hidden structural residues, and reduced explanatory organization. The compact-fiber
branch addresses the deeper carrier structure from which those projected residues arise.

---

### Research Integrity and Reproducibility Model

The Dual-Frame research program operates under audit-grade, falsifiable,
and independently reproducible standards. Empirical claims are accepted only
when they meet operational criteria, not author assertion.

Across repositories:

- Parameters are frozen prior to evaluation (no post-hoc tuning)
- Public datasets are cited and externally accessible
- Scripts regenerate all reported figures/tables from raw data
- Each project defines an explicit falsification surface
- Negative results are preserved and logged
- Claims are limited to what the measurements warrant

Repository status labels (e.g., **Validated / Production**) are mechanical and
defined by the criteria in **[VERIFICATION_PRINCIPLES.md](./VERIFICATION_PRINCIPLES.md)**.

Independent reproduction by third parties is encouraged and expected.

---

## 1. Purpose and Scope

**Purpose:** Provide a parameter-light, geometry-first framework that explains 
quantization, coherence limits, and correlation structure across quantum, atomic, 
and macroscopic systems using minimal structural assumptions, with explicit falsifiability.

This repository serves as the canonical, citable **program-level index** for the
broader **Σ-Order research program**, including both **Σ-Order theory (ΣO)** as the
post-projection, limits-first branch and the deeper **compact-fiber / carrier
reconstruction** branch.

This repository is a **conceptual and organizational index** for the full research
ecosystem descending from the Dual-Frame / Σ-Order lineage. All empirical claims
are constrained by explicit verification and falsification standards defined in
VERIFICATION_PRINCIPLES.md.

> **TL;DR**
> The research collected here belongs to a single developmental program.
> **Σ-Order theory** is the post-projection, limits-first branch: structurally informative,
> boundary-revealing, and richer than standard QM in preserved hidden structure, but
> degenerate relative to the deeper carrier level. The **compact-fiber branch** pursues
> that deeper local admissibility structure closer to the pre-projection / NRS level.

---

## 2. What ΣO Is — and Is Not

ΣO (Σ-order) is a **geometry-first explanatory framework**, not a
replacement formalism for quantum mechanics or general relativity.

In the present program, ΣO should be understood specifically as the
**post-projection branch** of the broader research effort. It preserves hidden
structural residue beyond standard QM, but it is not the deepest carrier level
of the program.

ΣO does **not** introduce new dynamical postulates, hidden variables, or stochastic
mechanisms at the foundational level. Instead, it proposes that many discrete and
correlation-driven physical phenomena arise from **topological constraints on
motion** when a universal scalar progression is projected into complementary
Temporal (T) and Spatial (S) frames.

ΣO is therefore:

- **Explanatory, not phenomenological** — it accounts for observed structure without tunable parameters or auxiliary mechanisms.
- **Derivational, not expansive** — it derives familiar behavior from minimal geometric necessity.
- **Falsifiable, not speculative** — claims are constrained by public benchmarks with explicit failure criteria.

ΣO is **not**:

- a commitment to a single predictive formalism,
- confined to a particular physical scale,
- or a claim that established models fail where their reductions remain sufficient.

### Where ΣO Reproduces vs. Competes

**ΣO reproduces standard QM/GR in validated regimes** (survival constraint):
- Standard coherence envelopes (Gaussian phase diffusion)
- Uncertainty relations (T/S projection complementarity)
- Local weak-field gravitational effects
- Standard spectral relationships (stationary Fourier)

**ΣO competes by predicting new admissibility boundaries:**
- Refusal where standard practice continues (winding hops, aperture violations)
- Attribution constraints without free parameters (rotation curves, atomic structure)
- Cross-domain invariants (same L, same winding rules across scales)

**Key claim:** ΣO is **interpretive** where QM/GR are maximally constrained, 
and **competing** at boundaries where standard frameworks use effective models 
or free parameters.

**Worked example (atomic ionization energies):**
- **Standard QM:** Ionization energies obtained by solving electronic structure 
  equations with screening approximations and effective potentials.
- **ΣO interpretation:** Same regularities attributed to winding-sector 
  admissibility and coherence aperture L—geometric constraints rather than 
  tuned interaction landscapes.
- **Overlap:** Both reproduce validated energies where standard methods are 
  sufficient.
- **Competing boundary:** ΣO commits to specific residual-structure patterns 
  (GOR-style diagnostics) under frozen parameters. Clean failure if patterns 
  do not match or require parameter adjustment.

A concise statement of falsifiability and verification standards is provided in  
VERIFICATION_PRINCIPLES.md.

All verification, admissibility, frozen-parameter, and falsification rules are
defined *canonically* in that document. The present README references and applies
those rules but does not redefine them.

---

## 3. Core Theory (Stable Background)

### 3.1 Foundational Primitives

- **Scalar progression** — a universal primitive of motion
- **Temporal / Spatial (T/S) frame duality** — complementary projections of scalar motion
- **Winding sectors** — topological admissibility conditions on T-frame evolution
- **Background Phase Geometry (BPG)** — global constraints on phase coherence
- **Closure Energy Principle (CEP)** — closure/holonomy mismatch yields finite penalties; logarithms arise from scale-distributed closure stress ([CLOSURE_ENERGY_PRINCIPLE.md](./CLOSURE_ENERGY_PRINCIPLE.md))
- **Second-order constraint geometry (Σ₂)** — trajectory-dependent organization  
   *(constraints on whether constraint satisfaction itself remains stable under continuation
   or intervention; governs when local constraints remain valid under re-projection)*  
   *(See **[sigma2-framework/](./sigma2-framework/)** for methodology backgrounder, motivating examples, scope boundaries, and the formal forcing schema.)*

Σ₂ is used throughout the Σ-Order ecosystem as a diagnostic and organizational concept.
Its formal definition and admissibility criteria are developed in the dedicated
Σ₂ framework documentation; the present README adopts that usage without
reintroducing formalism.

### 3.2 Relationship Between Core Theory and Domain Phenomenology

**Core theory provides primitives; domain modules show their manifestation.**

The ΣO core (Section 3.1) establishes foundational primitives: scalar progression,
T/S frame duality, winding sectors, BPG, and Σ₂. These are **scale-independent**
and **domain-neutral**.

**Domain phenomenology modules** translate these primitives into constraint-complete
classification frameworks for specific physical contexts (radiation, magnetism, etc.).

A domain module must:
- Identify **irreducible constraint classes** governing observable properties
- Map phenomena to **constraint signatures** (which classes they instantiate)  
- Provide **operational classification tests** (mechanical assignment rules)
- Maintain a **Binding Atlas** (phenomena → constraints mapping)
- Maintain a **Challenge Log** (classification stress-tests and boundary cases)
- Declare explicit **falsification conditions** (what would require new constraint classes)

**Key distinction:**
- **Core theory:** "What are the geometric primitives?" (universal, stable)
- **Domain modules:** "How do those primitives constrain observables in domain X?" (domain-specific, complete)

**Methodology:**
All domain modules use the **Binding Atlas + Challenge Log** approach to make
completeness claims auditable:
1. Pre-declare constraint classes before populating phenomena
2. Classify phenomena using operational tests (no judgment calls)
3. Log all challenging or boundary cases publicly
4. Treat any requirement for a new constraint class as a falsifiable theoretical event

**Example:** `dft-radiation` (Section 6.5) identifies five irreducible constraint
classes (C1–C5) governing phase evolution in radiation, then systematically maps
all radiation phenomena to these classes. See that module's repository for
full Binding Atlas and Challenge Log.

**Note:** Domain modules are independently citable, versioned repositories with
their own completeness claims. They extend explanatory coverage without modifying
core primitives.

### 3.3 Canonical Structure and Reading Order (Pedagogical)

The ΣO core theory is written as a **single, internally numbered development**.

- Section numbering inside documents is **authoritative**
- File boundaries are organizational only
- This document is an index; it does not duplicate core texts

**Recommended entry points (core theory):**

1. **Foundations:** [`01_foundations/scalar_motion.md`](./01_foundations/scalar_motion.md)  
   Axioms and dual-frame architecture

2. **Mechanics:** [`02_mechanics/winding_sectors.md`](./02_mechanics/winding_sectors.md)  
   Winding-sector admissibility (core mechanics)

3. **Coherence:** [`02_mechanics/coherence_hierarchy.md`](./02_mechanics/coherence_hierarchy.md)  
   Coherence hierarchy and aperture \(L\)

4. **Verification:** [`03_verifications/atomic_residuals.md`](./03_verifications/atomic_residuals.md)  
   Empirical sufficiency and falsification gates

5. **Geometry:** [`04_spatial_geometry/kernel_physicality.md`](./04_spatial_geometry/kernel_physicality.md)  
   Background Phase Geometry (BPG) and kernel physicality

6. **Synthesis:** [`05_synthesis/spectral_shifts.md`](./05_synthesis/spectral_shifts.md)  
   Cross-domain integration and spectral structure

**Representational reconstruction layer (papers):**  
For the motion-first Hilbert reconstruction and symmetry-induced complexification papers,
see **§6.9** (single canonical listing location).

**Note:** Section numbering inside documents is authoritative. File boundaries are for organization only.

---

## 4. Program Architecture

### 4.1 Domain Phenomenology Modules

Domain phenomenology modules apply core ΣO constraints to specific empirical domains 
by identifying **irreducible constraint classes** and providing **operational classification tests**.

**Established modules:**

| Module | Constraint Classes | Status | DOI |
|--------|-------------------|--------|-----|
| ✅ [`dft-radiation`](https://github.com/arwells-research/dft-radiation) | C1–C5 (phase evolution) | v1.0 RC | — |
| ✅ [`dft-magnetism`](https://github.com/arwells-research/dft-magnetism) | C1–C5 (circulation phenomenology) | v1.0 | — |

**Candidate modules (scoping stage):**

| Module | Domain | Status |
|--------|--------|--------|
| 🔒 `dft-gravity` | Gravitational phenomena | Constraint classes under identification |

**Status legend:**
- ✅ Public repository, constraint structure complete
- 🔒 Scoping stage, not yet public

**Note:** Candidate modules are **not commitments or roadmaps**. They indicate
domains where constraint-class coverage appears tractable, pending formal scoping
and verification against module admission criteria. Admission requires: irreducible 
constraint classes, operational tests, binding atlas, challenge log, and explicit 
falsification conditions.

### 4.2 Empirical Test Repositories

Empirical repositories implement frozen-parameter validation against public
datasets.

- Parameters are fixed *prior* to evaluation
- Benchmarks are externally curated where possible
- Each repository defines a domain-specific falsification surface

### 4.3 Foundational Extensions and Diagnostics

These repositories extend diagnostic reach without altering the core theory.

- Σ₂ formalism and diagnostics
- Information-theoretic constraints
- Projection asymmetry and arrow diagnostics

Repository | Scope | Domain | Status | DOI
--- | --- | --- | --- | ---
✅ [`dft-ringdown-diagnostics`](https://github.com/arwells-research/dft-ringdown-diagnostics) | Σ₂ diagnostics | Ringdown (GR) | Methods note | 10.5281/zenodo.18425951
✅ [`kernel-gravity-witness`](https://github.com/arwells-research/kernel-gravity-witness) | Σ₂ transport admissibility witness (curvature/nonmetricity channels + diagnostic SPD metric-fit) | Patch-overlap transport (pre-gravity admissibility instrument) | Validated instrument | —
✅ [`dft-lambda-consistency`](https://github.com/arwells-research/dft-lambda-consistency) | Global consistency analysis | Cosmology foundations | Conceptual paper | 10.5281/zenodo.18437571
✅ [`admissibility-beyond-minimal-surfaces`](https://github.com/arwells-research/admissibility-beyond-minimal-surfaces) | Scope limits | Network geometry | Conceptual paper | 10.5281/zenodo.18444241
   
---

## 5. Status of the Framework

> **Scope note:** This section summarizes theoretical maturity and verification status only.

### 5.1 Established and Verified

- Discrete winding constraints and quantization
- Coherence hierarchy and coherence aperture L
- Atomic residual structure (GOR) and nonlocal kinematic fits
- All validated against public datasets with frozen parameters

### 5.2 Constraint-Complete but Phenomenological

Some constructions are phenomenological but remain explicitly bounded:

- Effective variance laws and envelope forms
- Introduced only as minimal sufficient descriptions
- Explicitly constrained by falsification criteria

**Explicit example: `dft-radiation`**

**Structural completeness:**
- ✓ All five constraint classes (C1–C5) identified and bounded
- ✓ Operational classification tests established  
- ✓ Binding Atlas populated with canonical phenomena (expanding)
- ✓ Challenge Log documents boundary and stress-test cases
- ✓ No known phenomenon has required introduction of C6 to date

**Derivational incompleteness:**
- ⧗ Microscopic phase-evolution derivations from scalar progression in progress
- ⧗ Cumulant expansions and continuum-limit scaling under development
- ⧗ Formal connection to core winding-sector mechanics being formalized

**Status:** Constraint structure is **stable and complete** as of 2026-01-14.
Derivational work strengthens mechanistic understanding but does not affect
the constraint classification itself.

**Interpretation:** Domain is ready for use in classification and mapping work.
The constraint set (C1–C5) is not expected to change; any such change would
constitute a major theoretical revision (v2.0+), not a patch.

### 5.3 Active Stress-Testing and Extension

- Microscopic phase-evolution constructions from scalar progression
- Continuum-limit scaling analyses
- Formal mappings to standard QM and GR limits

---

## 6. Associated Research Repositories

Each repository below implements a falsifiable test, validation, or extension
of the core ΣO framework.

### 6.1 Atomic and Structural Physics

| Repository | Tests (ΣO Primitives) | Dataset | Status | DOI |
|-----------|------------------------|---------|--------|-----|
| ✅ [`gor-caf`](https://github.com/arwells-research/gor-caf) | Winding sectors, coherence aperture | NIST ionization energies | Validated | 10.5281/zenodo.18027076 |
| ✅ [`gor-kernel-model`](https://github.com/arwells-research/gor-kernel-model) | Coherence aperture L | Periodic table structure | Validated | — |
| ✅ [`gor-ck-witness`](https://github.com/arwells-research/gor-ck-witness) | CK witness, regime-conditioned collapse, manifold resolution (k-selection) | NIST ionization energies (p-block) | Validated | — |

### 6.2 Nuclear Decay and Lifetime Scaling

| Repository | Tests (ΣO Primitives) | Dataset | Status | DOI |
|-----------|------------------------|---------|--------|-----|
| ✅ [`satz-lifetime-diagnostics`](https://github.com/arwells-research/satz-lifetime-diagnostics) | Phase-space scaling, Σ₂ diagnostics | ENSDF β-decay lifetimes | Validated | — |

### 6.3 Macroscopic Vacuum and MEMS

| Repository | Tests (ΣO Primitives) | Dataset | Status | DOI |
|-----------|------------------------|---------|--------|-----|
| 🔄 [`casimir-mems-geometry`](https://github.com/arwells-research/casimir-mems-geometry) | Background Phase Geometry | Casimir force regimes (MEMS) | In development | — |

### 6.4 Astrophysical Kinematics and Large-Scale Structure

| Repository | Tests (ΣO Primitives) | Dataset | Status | DOI |
|-----------|------------------------|---------|--------|-----|
| ✅ [`dft-astro-nonlocal-kinematics`](https://github.com/arwells-research/dft-astro-nonlocal-kinematics) | Post-projection nonlocal kinematic geometry | SPARC rotation curves | Validated | — |
| ✅ [`compact-fiber-galactic-rotation`](https://github.com/arwells-research/compact-fiber-galactic-rotation) | Compact-fiber galactic rotation model | SPARC rotation curves | Paper repo | 10.5281/zenodo.19446509 |

### 6.5 Radiation and Coherence Phenomenology

**Domain module:**

| Repository | Type | Constraint Classes | Status | DOI |
|-----------|------|-------------------|--------|-----|
| ✅ [`dft-radiation`](https://github.com/arwells-research/dft-radiation) | Module | C1–C5 (phase evolution) | v1.0 RC | — |

**Note:** Module tables report constraint coverage rather than dependency structure.

**Empirical test repositories:**

| Repository | Tests (Constraint Signatures) | Dataset/Domain | Status | DOI |
|-----------|-------------------------------|----------------|--------|-----|
| ✅ [`mzi-phase-diffusion`](https://github.com/arwells-research/mzi-phase-diffusion) | Phase coherence (C1, C2) | First-order interference | Validated | — |
| ✅ [`g2-phase-statistics`](https://github.com/arwells-research/g2-phase-statistics) | Coherence hierarchy (C2) | Second-order correlations | Validated | — |
| ✅ [`hom-phase-diffusion`](https://github.com/arwells-research/hom-phase-diffusion) | Joint phase dynamics (C2, C5) | HOM interference | Validated | 10.5281/zenodo.17931012 |
| ⚠️ [`hom-topological-phase-history`](https://github.com/arwells-research/hom-topological-phase-history) | Winding sector survival (C2) | HOM benchmarks | Deprecated | — |
| ✅ [`single-emitter-antibunching`](https://github.com/arwells-research/single-emitter-antibunching) | Exclusivity topology (C2) | Antibunching | Validated | — |

**Note:** `dft-radiation` provides the constraint-classification framework (C1–C5).
Test repositories validate specific constraint signatures or combinations identified
in the module's Binding Atlas. Constraint class labels (C1, C2, etc.) in test descriptions
refer to `dft-radiation` classifications.

### 6.6 Magnetism and Circulation Phenomenology

**Domain module:**

| Repository | Type | Constraint Classes | Status | DOI |
|-----------|------|-------------------|--------|-----|
| ✅ [`dft-magnetism`](https://github.com/arwells-research/dft-magnetism) | Module | C1–C5 (circulation phenomenology) | v1.0 | — |

**Note:** `dft-magnetism` provides a constraint-complete, non-mechanistic
classification of magnetic and circulation phenomena within ΣO.
It establishes admissibility, reconstruction, and falsification boundaries
for magnetism without introducing material laws or microscopic models.

Constraint classes (C1–C5) here apply to **phase circulation and quasi-static
field structure**, not radiative dynamics.

### 6.7 Foundations and Bell-Type Correlations

| Repository | Tests (ΣO Primitives) | Dataset/Domain | Status | DOI |
|-----------|------------------------|----------------|--------|-----|
| ✅ [`chsh-joint-phase`](https://github.com/arwells-research/chsh-joint-phase) | Joint phase dynamics | Bell-CHSH | Validated | — |
| ✅ [`bell-correlations-joint-phase-dynamics`](https://github.com/arwells-research/bell-correlations-joint-phase-dynamics) | Long-range phase evolution | Bell correlations | Validated | — |

### 6.8 Second-Order Organization and Dynamics

| Repository | Tests (Σ₂ Class) | Dataset/Domain | Status | DOI |
|-----------|------------------|----------------|--------|-----|
| ✅ [`second-order-constraint-geometry`](https://github.com/arwells-research/second-order-constraint-geometry) | Σ₂ axioms | Two-qubit Hamiltonians | Validated | 10.5281/zenodo.18124930 |
| ✅ [`unfaithful-cut-foundations`](https://github.com/arwells-research/unfaithful-cut-foundations) | Σ₂ diagnostics (intervention) | Intervention faithfulness | Validated | 10.5281/zenodo.18168369 |
| ✅ [`unfaithful-cut-ai`](https://github.com/arwells-research/unfaithful-cut-ai) | Σ₂ epistemic limits | ML/RL evaluation | Validated | 10.5281/zenodo.18181966 |
| ✅ [`dft-second-order-framework`](https://github.com/arwells-research/dft-second-order-framework) | Σ₂ formalism | Organizational dynamics | Validated | 10.5281/zenodo.18124930 |

**Practitioner tools:**  
Σ₂ constraint logic is also implemented in domain-agnostic practitioner tools:

- [`intervention-faithfulness`](https://github.com/arwells-research/intervention-faithfulness) (Σ₂-I diagnostic for experimental/simulation data)
  - Install: `pip install intervention-faithfulness`
  - Use case: Certify model validity under protocol changes
  - Does not require ΣO knowledge; implements the same Σ₂ admissibility logic

These tools serve as **independent validation surfaces** for Σ₂ constraints and
provide **adoption pathways** for practitioners who encounter Σ₂ via applied work,
with the underlying methodology documented in the core theory.

### 6.9 Information Theory and Representation

| Repository | Tests (ΣO Primitives) | Dataset/Domain | Status | DOI |
|-----------|------------------------|----------------|--------|-----|
| ✅ [`dual-frame-information-theory`](https://github.com/arwells-research/dual-frame-information-theory) | Dual-frame entropy | Representation learning | Validated | 10.5281/zenodo.18048533 |
| ✅ [`motion-first-quantum-kinematics`](https://github.com/arwells-research/motion-first-quantum-kinematics) | Hilbert representability from distinguishability axioms | Quantum kinematics (representational) | Paper repo | 10.5281/zenodo.18646222 |
| ✅ [`symmetry-induced-complexification`](https://github.com/arwells-research/symmetry-induced-complexification) | Complex structure from one-parameter symmetry | Quantum kinematics (representational) | Paper repo | 10.5281/zenodo.18692888 |
| ✅ [`compact-fiber-admissibility`](https://github.com/arwells-research/compact-fiber-admissibility) | Necessity of the compact local admissibility carrier | Reciprocal-System / foundational local carrier | Paper repo | 10.5281/zenodo.19423877 |
| ✅ [`compact-fiber-atomic-structure`](https://github.com/arwells-research/compact-fiber-atomic-structure) | Atomic screening classification from the compact fiber | Atomic structure / spectroscopic regime | Paper repo | 10.5281/zenodo.19426035 |
| ✅ [`compact-fiber-quantum-gravity`](https://github.com/arwells-research/compact-fiber-quantum-gravity) | Effective quantum and gravitational structure from the compact fiber | Quantum / gravity (representational and weak-field effective structure) | Paper repo | 10.5281/zenodo.19434652 |

### 6.10 Arrow Diagnostics and Projection Asymmetry

| Repository | Tests (ΣO Primitives) | Dataset/Domain | Status | DOI |
|-----------|------------------------|----------------|--------|-----|
| ✅ [`projection-induced-arrows`](https://github.com/arwells-research/projection-induced-arrows) | Projection asymmetry | Arrow diagnostics | Validated | — |

### 6.11 Neuroscience and Dual-Order Dynamics

| Repository | Tests (ΣO Primitives) | Dataset/Domain | Status | DOI |
|-----------|------------------------|----------------|--------|-----|
| 🔄 [`dft-dual-order-dynamics`](https://github.com/arwells-research/dft-dual-order-dynamics) | Trajectory holonomy | EEG/OpenNeuro | Active | — |

### 6.12 Developmental Biology & Constraint Audits

| Repository | Tests (ΣO Primitives) | Dataset/Domain | Status | DOI |
|-----------|------------------------|----------------|--------|-----|
| ✅ [`lineage-constraint-audit`](https://github.com/arwells-research/lineage-constraint-audit) | Constraint-first audit logic (Σ₂-adjacent) | Lineage detectability in scRNA-seq (C. elegans) | Validated | — |

**Status legend:**
- ✅ Public repository, validation complete or validated
- 🔄 Public repository, active development
- 🔒 Scoping stage, not yet public
- ⚠️ Deprecated or superseded

---

## 7. Verification and Falsifiability

Verification, falsification, frozen-parameter validation, and challenge protocols
are defined centrally in VERIFICATION_PRINCIPLES.md.

This section summarizes how those principles are *applied* across repository
types (core theory, domain modules, empirical tests), rather than restating the
rules themselves.

**Completeness falsification (domain modules):**

For constraint-complete modules like `dft-radiation`, falsification is **structural**:
discovery of a phenomenon requiring a new constraint class (e.g., C6 for radiation)
constitutes falsification of the completeness claim. Such discoveries are treated
as **versioned theoretical events**, not quiet patches.

**Empirical falsification (test repositories):**

Each test repository defines domain-specific falsification surfaces (e.g., residual
structure in atomic ionization energies, systematic deviations in rotation curves).

**Full protocols:**  
See **[VERIFICATION_PRINCIPLES.md](./VERIFICATION_PRINCIPLES.md)** for:
- Detailed verification standards
- Domain-specific falsification criteria  
- Reproducibility requirements

---

## Citation

If you use or reference this work, please cite:

A. R. Wells (2025). *Dual-Frame Theory: Core Framework* (v1.0.0).  
Zenodo. https://doi.org/10.5281/zenodo.18027076

> **Versioning note:** This repository is a living index; citations should reference
> the DOI above and the tagged release version.

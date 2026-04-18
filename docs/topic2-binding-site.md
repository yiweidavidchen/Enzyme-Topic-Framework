# Topic 2 — Binding-Site Exploration

---

## Status

This topic is currently in the **mutagenesis/design stage**.  
The ideas presented here reflect **working hypotheses** and **candidate residue selections**, rather than validated kinetic conclusions.

---

## Motivation

Phase 1 (catalytic-site mutations) suggests that:

> catalytic residues primarily control turnover (`kcat`),  
> with limited impact on substrate discrimination.

This leads to a central question:

> **Where does substrate specificity arise in BglB?**

---

## Core Question

> Is substrate specificity primarily encoded by binding-site interactions rather than catalytic residues?

---

## Working Hypothesis

Substrate discrimination in BglB emerges from:

- **direct interactions** between enzyme and substrate  
  (hydrogen bonding, stacking, positioning)

rather than from:

- catalytic chemistry alone

In particular, interactions involving:

- C3  
- C4  
- C6  

positions of the sugar are expected to play a dominant role.

---

## Conceptual Model

We model the BglB active site as a **layered system**:

- **Catalytic core** → governs chemical transformation  
- **Recognition layer** → defines substrate identity  
- **Structural context** → modulates positioning and stability  

Topic 2 focuses on probing the **recognition layer**, while incorporating selected mutations in the **structural context** to disentangle direct vs indirect effects.

---

## Figure Concept (Schematic Description)

**Figure 1. Layered model of the BglB active site and mutational probing strategy**

The active site is represented as concentric functional layers:

- At the center, the **catalytic core** (E164, E353, T352) performs bond cleavage.
- Surrounding this is the **recognition layer**, composed of residues that directly interact with substrate hydroxyl groups and aromatic surfaces (e.g. E406, Q19, W407).
- The outer region forms the **structural context**, including second-shell and electrostatic residues (e.g. N293, R76), which indirectly influence active-site geometry.

Substrate orientation is stabilized through:

- hydrogen bonding at C3/C4/C6 positions  
- π-stacking interactions  

Mutations are conceptualized as **localized perturbations** applied to different layers:

- catalytic perturbations → alter reaction chemistry  
- recognition perturbations → alter substrate discrimination  
- context perturbations → alter positioning and energetic landscape  

Observed kinetic outputs (`kcat`, `Km`, `kcat/Km`) are interpreted as system-level responses to these perturbations.

---

## Representative Residues

This section highlights **representative residues**, chosen to probe distinct interaction types within the binding site.

---

### 🔹 E406 — C4/C6 Recognition

**Proposed role**  
- Hydrogen bonding with C4-OH and/or C6-OH  
- Potential discriminator across substrates

**Rationale**  
- C4 stereochemistry differs between glucose and galactose  
- C6 presence/absence varies across substrates  

**Interpretation goal**  
- Test whether C4/C6 interactions dominate specificity

---

### 🔹 Q19 — C3/C4 Hydrogen Bond Network

**Proposed role**  
- Bidentate hydrogen bonding with substrate hydroxyl groups  

**Rationale**  
- May stabilize specific substrate orientations  
- Could define preferred binding conformations  

**Interpretation goal**  
- Evaluate contribution of local H-bond networks to specificity

---

### 🔹 W407 — Aromatic Stacking Platform

**Proposed role**  
- π-stacking interaction with substrate  

**Rationale**  
- Aromatic stacking is common in carbohydrate-binding sites  
- May influence positioning rather than identity directly  

**Interpretation goal**  
- Separate positioning effects from chemical recognition

---

### 🔹 N293 — Structural Context (Second-Shell)

**Proposed role**  
- Indirect modulation of active-site geometry  

**Rationale**  
- Does not directly contact substrate  
- May influence catalytic or recognition residues through structural coupling  

**Interpretation goal**  
- Distinguish direct recognition from indirect structural effects

---

## Mutation Strategy

Mutations are designed as **targeted perturbations**:

- disrupt hydrogen bonding  
- alter polarity and charge  
- modulate aromatic stacking  
- perturb second-shell interactions  

Each mutation is interpreted as probing a **specific interaction type**, rather than as an optimization attempt.

---

## Expected Readouts

Experimental measurements:

- `kcat` → catalytic turnover  
- `Km` → effective binding affinity  
- `kcat/Km` → catalytic efficiency  
- substrate-dependent trends → specificity profile  

---

## Interpretation Framework

Results will be evaluated relative to the model:

- **Specificity shifts without major kcat change**  
  → supports binding-driven discrimination  

- **Large kcat changes across all substrates**  
  → indicates coupling with catalytic machinery  

- **Second-shell effects**  
  → reveal contribution from structural context  

---

## Relationship to Topic 1

Topic 1 (catalytic machinery):

- establishes baseline for catalytic contribution  

Topic 2 (binding site):

- probes determinants of substrate identity  

Together:

> enzyme function is decomposed into  
> **catalysis vs recognition vs context**

---

## Future Directions

This topic will evolve with experimental data:

- refine residue classification  
- expand or reduce candidate set  
- integrate structural/docking analysis  
- test model consistency across substrates  

---

## Notes

This document represents an evolving design space.  
Both residue selection and interpretation models are expected to change as new data becomes available.

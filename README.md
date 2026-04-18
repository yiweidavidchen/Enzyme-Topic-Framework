# Enzyme-Topic-Framework
A model-guided framework for interpreting enzyme mutations as probes into molecular systems.

# 🧬 BglB Exploration Framework  
*A model-guided lens for enzyme mutational analysis*

---

## What this is

This project proposes a simple idea:

> Mutations are not just variants.  
> They are **probes into a molecular system**.

Instead of treating enzyme engineering as a collection of isolated experiments, this framework organizes mutations into **Topics (models)** to enable structured interpretation.

---

## The gap

High-throughput workflows (e.g. D2D pipelines) are powerful:

- mutations are generated efficiently  
- data is collected systematically  

But often lack:

- a clear question behind each mutation  
- connections between mutants  
- a unified interpretation layer  

This framework adds that missing layer.

---

## Core idea

Two complementary modes of exploration:

### Non-parametric exploration
- random / semi-random mutations  
- broad sampling of sequence space  
- data-first discovery  

### Model-guided exploration (this framework)
- mutations grouped into **Topics**  
- each mutation = a **probe**  
- data interpreted against a **model**

---

## Topic X framework

Each **Topic** defines a local model of enzyme behavior.

**Minimal structure:**

- **Question** — what are we testing?  
- **Hypothesis** — what do we believe?  
- **Residues** — where do we probe?  
- **Mutations** — how do we test?  

---

### Example: Catalytic Machinery

**Question**  
Do catalytic residues control only turnover, or also substrate specificity?

**Hypothesis**  
Catalytic residues primarily affect `kcat`, with limited effect on discrimination.

**Residues**  
E164, E353, T352

**Mutations (probes)**  
E164A, E353D, T352A

---

### Example: Binding-Site Exploration

**Question**  
Is substrate specificity primarily encoded by binding interactions rather than catalytic residues?

**Working hypothesis**  
Hydrogen bonding and stacking interactions around the substrate-binding pocket play a larger role in discrimination than the catalytic core itself.

**Representative residues**  
- E406: C4/C6 recognition  
- Q19: C3/C4 hydrogen-bonding  
- W407: aromatic stacking platform  
- N293: second-shell structural context  

This topic is currently in the mutagenesis/design stage and will be refined as kinetic data become available.

---

## Mutation = probe

Each mutation is interpreted as a functional perturbation:

| Mutation | Interpretation |
|----------|----------------|
| E164A | removes acid/base function |
| T352A | alters nucleophile positioning |
| E353D | shifts catalytic geometry |

To improve interpretability, mutations can be named:

- E164A → *Acid Switch Off*  
- T352A → *Nucleophile Drift*  
- E353D → *Catalytic Core Shift*  

---

## Data = system response

Experimental outputs are not just numbers:

| Attribute | Meaning |
|----------|--------|
| `kcat` | catalytic turnover |
| `Km` | binding affinity |
| `kcat/Km` | efficiency |
| `Tm` | stability |

They are **responses of the enzyme to a defined perturbation**.

---

## Example case

**E164A — Acid Switch Off**

- **Topic**: Catalytic Machinery  
- **Perturbation**: removal of acid/base catalysis  

**Observed response**
- strong decrease in `kcat`  
- increased thermal stability  

**Interpretation**  
This mutation supports a model where catalytic residues dominate turnover while contributing minimally to substrate discrimination.

---

## Structural map (conceptual)

BglB can be understood as a layered system:

- **Catalytic core**  
  Directly involved in chemical transformation  

- **Recognition layer**  
  Direct interactions with substrate (hydrogen bonding, stacking)  

- **Structural context**  
  Indirect effects through positioning, electrostatics, and stability  

Examples:
- Core: E164, E353  
- Recognition: E406, Q19, W407  
- Context: N293, R76  

Mutations probe different layers of this system, revealing how enzyme function emerges from their interplay.

---

## Philosophy

Shift the question from:

> “Did this mutation work?”

to:

> “What does this mutation reveal?”

---

## Use case

This framework is designed as an **interpretation layer** on top of existing workflows:

- does not replace D2D pipelines  
- does not change experimental procedures  
- organizes how results are understood  

---

## Vision

- turn mutation datasets into structured knowledge  
- help new researchers think mechanistically  
- enable shared interpretation across labs  

While developed on BglB, this approach generalizes to:

- other enzymes  
- protein engineering workflows  
- mutational scanning systems  

---

## Status

Early-stage, evolving.

Future directions:
- expand Topic definitions  
- integrate structural/docking data  
- connect with shared datasets (e.g. D2D network)  

---

## Author note

This framework emerged from attempts to better understand how mutations shape enzyme behavior in BglB.

It is shared as a conceptual tool for anyone exploring enzyme systems.

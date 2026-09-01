# General Structure Unfolding Intelligence

## From Core Structure and Delta Modification to a General Paradigm of Intelligence

**GSUI — General Structure Unfolding Intelligence**

> **Intelligence can be studied not only as computation over data, but also as the controlled unfolding of structure.**

---

## Core Idea

```text
<Core Structure> +/- <Delta Modification>
```

A more general runtime form is:

$$
S_{t+1} =
U(S_t,\Delta_t,C_t,T_t,P_t,I_t)
$$

where:

* \(S_t\) — current structure;
* \(\Delta_t\) — candidate structural modification;
* \(C_t\) — context;
* \(T_t\) — trigger;
* \(P_t\) — policy;
* \(I_t\) — relevant invariants;
* \(U\) — unfolding operator.

The central research question is:

> **Can reasoning, generation, planning, coding, control, perception, learning, and structural growth be studied as different forms of constrained structural unfolding?**

GSUI does **not** claim that these processes are algorithmically identical.

It asks whether they share a sufficiently general **structural form** to support common theories of:

```text
Core
Delta
Unfolding Space
Triggering
Control
Policy
Evaluation
Invariant
Certification
Feedback
Growth
Structural Self
```

---

# 1. The Intelligence Cycle

Modern AI research has devoted enormous attention to forming structure:

```text
Observation
    ↓
Data
    ↓
Training / Compression / Folding
    ↓
Structure
```

But once structure exists, another question becomes equally important:

> **How does structure become runtime intelligence?**

GSUI focuses on the other half:

```text
Structure
    ↓
Context / Trigger
    ↓
Unfolding
    ↓
Reasoning / Generation / Planning / Action
```

The larger cycle is:

```text
WORLD
  │
  ▼
Observation
  │
  ▼
FOLDING
  │
  ▼
CORE STRUCTURE
  │
  ▼
UNFOLDING
  │
  ▼
Action / Generation
  │
  ▼
WORLD
  │
  ▼
Feedback
  │
  ▼
STRUCTURAL GROWTH
  │
  └──────────────► Updated Core Structure
```

Thus:

> **Folding and Unfolding are two complementary halves of an intelligence cycle.**

---

# 2. Why Unfolding?

A trained model, graph, tree, policy system, or biological structure is not intelligent merely because structure exists.

The structure must become operational.

Examples:

```text
LLM
→ runtime continuation

CallingGraph
→ coding plan and structural modification

Tree
→ branch activation

CCC
→ condition-context-controlled transition

ANN
→ distributed activation trajectory

World Model
→ possible future consequences

Autonomous Vehicle
→ reachable trajectory

Continual Learner
→ structural growth
```

These mechanisms differ substantially.

GSUI does not erase those differences.

Instead it asks:

> **What can unfold from an existing structure, under what conditions, and with what control?**

---

# 3. Core Structure + Delta Modification

The minimal GSUI form is:

$$
S' = S \pm \Delta
$$

Here:

* \(S\) represents a Core Structure;
* \(\Delta\) represents a candidate modification;
* \(S'\) represents the resulting structure or state.

Delta is broader than simple addition.

Possible operations include:

```text
Preserve
Add
Delete
Replace
Branch
Merge
Reconnect
Reweight
Activate
Suppress
Instantiate
Sample
Move
Compress
Expand
```

Therefore:

> **Unfolding is broader than generation.**

A generated artifact is one possible result of unfolding.

A branch selection, trajectory modification, structural suppression, topology change, or invariant-preserving update may also be an unfolding operation.

Conceptually:

$$
Generation \subset Unfolding
$$

---

# 4. Generality Without False Equivalence

GSUI makes a deliberately bounded claim:

> **A broad class of intelligent processes can be represented, analyzed, or reconstructed as constrained structural unfolding.**

It does **not** claim:

```text
ANN = CCC

CCC = CallingGraph

CallingGraph = Tree

Planning = Generation

Reasoning = Navigation

All intelligence = one algorithm
```

Instead:

> **Generality refers to recurring structural form, not algorithmic identity.**

Different systems may implement unfolding through very different mechanisms.

| System             | Core Structure                      | Example Unfolding         |
| ------------------ | ----------------------------------- | ------------------------- |
| LLM                | learned parameter structure         | runtime continuation      |
| CallingGraph       | software call topology              | ΔCG                       |
| Tree               | branch topology                     | routing / growth          |
| CCC                | condition-context-control structure | constrained transition    |
| ANN                | learned distributed structure       | activation trajectory     |
| Generative AI      | model + runtime state               | generated artifact        |
| Autonomous Vehicle | vehicle + controller state          | trajectory modification   |
| World Model        | structured world representation     | consequence simulation    |
| Continual Learning | persistent learned structure        | retained structural Delta |

The common object is not one algorithm.

It is the relationship:

```text
Persistent Structure
        +
Runtime Conditions
        ↓
Structured Possibility
        ↓
Selected Transition
```

---

# 5. Unfolding Space

A structure does more than encode what already exists.

It also determines what can happen next.

GSUI calls this the **Unfolding Space**:

$$
\mathcal{U}(S,C)
$$

where:

* \(S\) is the current structure;
* \(C\) is current context.

The space may contain:

```text
Possible next states
Possible branches
Possible actions
Possible trajectories
Possible generations
Possible structural modifications
Possible retained structures
```

A crucial hierarchy is:

$$
\mathcal{U}_{selected}
\subseteq
\mathcal{U}_{preferred}
\subseteq
\mathcal{U}_{allowed}
\subseteq
\mathcal{U}_{reachable}
\subseteq
\mathcal{U}_{possible}
$$

In plain language:

```text
Possible
   ↓
Reachable
   ↓
Allowed
   ↓
Preferred
   ↓
Selected
   ↓
Certified
   ↓
Executed
```

This distinction is fundamental.

> **Possible does not mean allowed.**

> **Allowed does not mean preferred.**

> **Preferred does not mean selected.**

> **Selected does not automatically mean certified.**

---

# 6. Search Is Not Unfolding

Search and unfolding are related, but they are not identical.

Search commonly assumes:

```text
Existing Candidate Space
        ↓
Search
        ↓
Selected Candidate
```

Structural unfolding may instead produce:

```text
Current Structure
        ↓
Structural Delta
        ↓
New Structure
        ↓
New Future Possibility Space
```

Therefore:

$$
S_t \rightarrow S_{t+1}
$$

may imply:

$$
\mathcal{U}(S_t)
\neq
\mathcal{U}(S_{t+1})
$$

This is a major GSUI distinction:

> **Search selects within possibility. Structural unfolding can change possibility itself.**

An intelligent system may therefore do more than search for answers.

It may change what answers, actions, structures, or capabilities can become reachable next.

---

# 7. Control Plane

A large Unfolding Space is not automatically useful intelligence.

The system must organize it.

GSUI therefore treats the **Control Plane** as a first-class intelligence structure.

```text
             UNFOLDING SPACE
                    │
                    ▼
             Candidate Deltas
                    │
                    ▼
          ┌────────────────────┐
          │    CONTROL PLANE   │
          ├────────────────────┤
          │ Triggering         │
          │ Constraints        │
          │ Policy             │
          │ Evaluation         │
          │ Invariants         │
          │ Certification      │
          │ Authorization      │
          └─────────┬──────────┘
                    ▼
              Selected Delta
```

The Control Plane answers:

```text
What becomes active?

What is reachable?

What is permitted?

What is preferred?

What must remain invariant?

What can cross into consequential action?
```

Thus:

> **Control is not merely an external restriction on intelligence. It is one mechanism by which unfolding becomes intelligent.**

---

# 8. Intelligence Is Not Maximum Unfolding Freedom

A system with more possible behaviors is not necessarily more intelligent.

A huge uncontrolled space may increase:

```text
Search cost
Instability
Risk
Inconsistency
Governance difficulty
```

A mature structure may instead reduce unnecessary exploration.

For example:

```text
Novice
→ large search
→ many weak candidates

Expert
→ structural recognition
→ small relevant region
→ direct route
```

Therefore:

> **Intelligence is not maximum unfolding freedom.**

A stronger statement is:

> **Intelligence is effective organization of unfolding possibility.**

---

# 9. Structural Growth

Feedback alone is not growth.

Growth occurs when successful unfolding becomes part of future persistent structure.

```text
Unfolding
    ↓
Consequence
    ↓
Feedback
    ↓
Evaluation
    ↓
Retention
    ↓
Updated Core Structure
```

A working definition is:

> **Structural Growth is the incorporation of selected unfolding outcomes into persistent structure such that future unfolding possibilities are changed.**

The important transition is therefore not only:

$$
S_t \rightarrow S_{t+1}
$$

but:

$$
\mathcal{U}(S_t)
\rightarrow
\mathcal{U}(S_{t+1})
$$

Structural Growth can:

```text
Expand useful possibility

Contract unsafe possibility

Create direct routes

Change triggering

Change evaluation

Reorganize topology

Add new capabilities

Strengthen invariants
```

Thus:

> **Learning becomes structural growth when retained unfolding changes future unfolding capacity.**

---

# 10. Structural Self

The expression:

$$
S' = S \pm \Delta
$$

contains a deeper question:

> **Relative to what is Delta defined?**

Likewise:

```text
Capability of what?

Damage to what?

Growth of what?

Invariant of what?

Possible future for what?

World Model for whom?
```

GSUI introduces **Structural Self** as a reference-frame concept.

> **Structural Self is the persistent structural reference frame relative to which unfolding, modification, capability, preservation, and continuity are defined.**

The shortest form is:

> **Self is the reference frame of unfolding.**

This does not require consciousness.

It does not imply human-like subjective experience.

It begins from structural continuity.

---

# 11. Self Need Not Begin with Consciousness

A preliminary hierarchy is:

```text
Structural Self
      ↓
Operational Self
      ↓
Cognitive Self
      ↓
Narrative / Human Self
```

GSUI primarily begins with the first two.

### Structural Self

The persistent reference structure across unfolding.

### Operational Self

The current capabilities, interfaces, permissions, constraints, and actionable state of that structure.

The lower levels do not establish the higher ones.

Therefore:

> **Self need not begin with consciousness. It may begin with structural continuity.**

---

# 12. World Model for Whom?

Structural Self clarifies a basic problem in world-model research.

A world model is often written conceptually as:

$$
WM = Model(World)
$$

But action-oriented intelligence needs more.

A useful operational formulation is:

$$
WM =
WM(
World
\mid
Self,
Context,
Capability,
Goal
)
$$

Why?

Because the same physical world can have different operational meanings for different systems.

Example:

```text
Corridor width = 0.8 m

Small robot:
passable

Large robot:
blocked

Human:
walkable

Drone:
possibly bypassable
```

The world did not change.

The Structural Self changed.

Therefore:

> **For action-oriented intelligence, a world model becomes operationally meaningful when interpreted relative to a Structural Self, its capabilities, constraints, context, and goals.**

---

# 13. Self ↔ World Model ↔ Unfolding Space

Three GSUI objects therefore form a tight relationship:

```text
             STRUCTURAL SELF
                /       \
               /         \
              ▼           ▼
       WORLD MODEL ←──→ UNFOLDING SPACE
```

Structural Self asks:

> **For whom?**

World Model asks:

> **What is the relevant world structure?**

Unfolding Space asks:

> **What can this system do or become next?**

A useful expression is:

$$
\mathcal{U} =
\mathcal{U}(Self,World,Context)
$$

If the Self changes:

$$
Self_t \rightarrow Self_{t+1}
$$

then even with the same world:

$$
\mathcal{U}(Self_t,World)
\neq
\mathcal{U}(Self_{t+1},World)
$$

may hold.

---

# 14. Machine-Native Perception

GSUI also questions the assumption that AI perception must imitate human perception.

Human perception evolved under specific constraints:

```text
Human body
Human sensors
Human energy limits
Human environment
Human survival pressures
```

These are not universal requirements for machine intelligence.

Machines may directly perceive:

```text
CallingGraph topology

Network latency fields

RF spectrum

Database contention

Memory pressure

Dependency graphs

Runtime traces

Industrial sensor manifolds

High-dimensional telemetry
```

These can be first-class machine perceptions.

A general formulation is:

$$
Perception:
WorldSignals
\rightarrow
SelfRelativeOperationalStructure
$$

Thus:

> **Perception is not fundamentally human-like sensing; it can be the construction of self-relative structures that constrain and enable unfolding.**

---

# 15. Machine-Native Cognition

The same principle extends beyond perception.

Machine intelligence may use:

```text
ANN activation

Latent spaces

CallingGraphs

Metric structures

CCC structures

Policy trees

Runtime invariants

Machine-specific memory
```

without translating every internal operation into human cognitive categories.

This motivates:

> **Non-Anthropomorphic Intelligence**

But this freedom has an important boundary.

---

# 16. Machine-Native Cognition Does Not Mean Uncontrolled AI

The following inference is invalid:

```text
AI cognition differs from human cognition
        ↓
Humans cannot interpret every internal state
        ↓
AI external actions should be unrestricted
```

GSUI explicitly rejects this conclusion.

Instead:

$$
Internal\ Unfolding\ Freedom
\neq
External\ Action\ Freedom
$$

A machine may possess rich, non-human internal cognition while consequential actions remain:

```text
Observable
Constrained
Policy-governed
Invariant-checked
Certified
Auditable
```

The governing principle is:

> **Machine-native cognition; human-governable consequences.**

---

# 17. Structural Observability and Certification

GSUI distinguishes:

### Internal Interpretability

Can humans understand the internal computation?

### Structural Observability

Can consequential structural changes be identified?

### Action Certifiability

Can those changes be checked against policy, invariants, tests, and safety requirements?

These are not the same problem.

Future systems may have:

```text
Limited internal interpretability

but

Strong structural observability

and

Strong action certification
```

This creates an important bridge between powerful machine-native cognition and human governance.

---

# 18. CallingGraph AI Coding as a Canonical Example

AI coding makes the idea concrete.

A coding AI may internally reason through structures that humans cannot fully inspect.

But a consequential software modification can still be represented as:

$$
CG_{t+1} =
CG_t
\pm
\Delta CG
$$

The governance questions become:

```text
What is ΔCG?

Was ΔCG authorized?

Does ΔCG preserve required invariants?

Does generated code faithfully implement ΔCG?

Does the actual CallingGraph match the planned CallingGraph?

Should the change be accepted?
```

A canonical flow is:

```text
Machine-Native Internal Reasoning
             ↓
        Candidate ΔCG
             ↓
         Coding Plan
             ↓
       Generated Code
             ↓
        Actual CG
             ↓
 Planned / Actual Comparison
             ↓
   Invariant Certification
             ↓
       Accept / Reject
```

Thus:

> **Non-anthropomorphic cognition is not a reason to remove the structural reins.**

---

# 19. Invariant and Continuity

If structure changes continuously, why should:

$$
S_{t+1}
$$

still count as a continuation of:

$$
S_t
$$

?

GSUI connects this problem to invariants.

```text
Structural Self
      ↓
Candidate Delta
      ↓
Modified Structure
      ↓
Invariant Check
      ↓
Continuation / Rejection
```

An invariant specifies what must remain sufficiently true across change.

Thus:

> **Invariant defines continuity across unfolding.**

Structural Self is therefore not necessarily a structure that never changes.

Rather:

> **Structural Self is the reference structure whose continuity is managed while change occurs.**

---

# 20. The Full GSUI Runtime Cycle

```text
                           WORLD
                             │
                             ▼
                        Observation
                             │
                             ▼
                    STRUCTURAL PERCEPTION
                             │
                             ▼
                     ┌───────────────┐
                     │    FOLDING    │
                     └───────┬───────┘
                             ▼
                  ┌────────────────────┐
                  │   CORE STRUCTURE   │
                  │    + INVARIANTS    │
                  └─────────┬──────────┘
                            │
                Context / Trigger / Goal
                            │
                            ▼
                  ┌────────────────────┐
                  │  UNFOLDING SPACE   │
                  └─────────┬──────────┘
                            │
                 ┌──────────┼──────────┐
                 ▼          ▼          ▼
                Δ1         Δ2         Δ3
                 │          │          │
                 └──────────┼──────────┘
                            ▼
                  ┌────────────────────┐
                  │    CONTROL PLANE   │
                  ├────────────────────┤
                  │ Constraint         │
                  │ Policy             │
                  │ Evaluation         │
                  │ Invariant          │
                  │ Certification      │
                  └─────────┬──────────┘
                            ▼
                       Selected Δ
                            │
                            ▼
                        S' = S ± Δ
                            │
                            ▼
                  Action / Generation
                            │
                            ▼
                           WORLD
                            │
                         Feedback
                            │
                            ▼
                    STRUCTURAL GROWTH
                            │
                            ▼
                    UPDATED STRUCTURE
                            │
                            ▼
                 NEW UNFOLDING SPACE
```

Across the cycle:

```text
STRUCTURAL SELF
      │
      ├── provides the reference for Delta
      ├── defines continuity
      ├── conditions capability
      ├── conditions perception
      ├── shapes world-model meaning
      └── shapes Unfolding Space
```

---

# 21. Three Central GSUI Hypotheses

## 21.1 Unfolding Universality

> **A broad class of intelligent behaviors may share a useful structural description as constrained unfolding from persistent structure.**

## 21.2 Unfolding Primitive Compression

> **Many human-defined intelligence categories may eventually be expressible through compositions of a relatively small family of structural unfolding primitives.**

Candidate primitive families include:

```text
Metric
CCC
Activation
Inhibition
Branch
Merge
Memory
Delta
Feedback
Trigger
Selection
Invariant
```

## 21.3 Structural Self

> **A persistent structural reference frame may provide an operational basis for Delta, continuity, perception, world-model interpretation, capability, and action.**

These hypotheses are related but independently testable.

---

# 22. Scaling Revisited

GSUI does not reject scaling.

Large learned structures may support:

```text
More latent relations

More reusable representations

More candidate trajectories

More context-sensitive reconstruction

More possible unfolding
```

Thus:

> **Scaling enlarges unfolding potential.**

But potential alone is not sufficient.

Advanced intelligence also requires:

```text
Triggering
Localization
Routing
Policy
Evaluation
Invariant
Certification
Feedback
Growth
```

Therefore:

> **Scaling enlarges unfolding potential; structural intelligence governs unfolding.**

---

# 23. Research Program

GSUI opens a broader research landscape.

### Unfolding Space

How should possible structural futures be represented?

### Unfolding Primitive Algebra

Can complex intelligent processes be composed from a small family of structural operators?

### Triggering

What activates the relevant region of a large latent Unfolding Space?

### Control Plane

How should constraints, policies, evaluation, and certification interact?

### Invariant-Preserving Unfolding

How can systems change while maintaining structural continuity?

### Structural Growth

How does successful runtime unfolding become future capability?

### Unfolding-Space Geometry

Can reachability, risk, structural distance, and topology be formalized?

### Structural Self

What provides the persistent reference frame across intelligent change?

### Self-Relative World Models

How should world-model semantics adapt when the acting Self changes?

### Non-Anthropomorphic Perception

What forms of perception emerge when machines are not required to imitate human sensory systems?

### Machine-Native Cognition

What structures support intelligence beyond human cognitive categories?

### Structural Certification

What must become observable at the boundary between opaque internal cognition and consequential action?

### Autonomous Structural Unfolding

How can systems modify their own future Unfolding Space without losing continuity and governability?

---

# 24. Foundational Papers

The first GSUI release is organized around five foundational papers.

### GSUI-001 — From Folding to Unfolding

Introduces the missing second half of the intelligence cycle:

```text
Observation
→ Folding
→ Structure
→ Unfolding
→ Action
→ Feedback
→ Growth
```

### GSUI-002 — Core Structure and Delta Modification

Develops the minimal structural language:

$$
S' = S \pm \Delta
$$

and defines Core, Delta, Context, Trigger, Policy, Invariant, and Unfolding Operator.

### GSUI-003 — General Structure Unfolding Intelligence

Establishes the cross-domain paradigm and compares LLMs, CallingGraphs, trees, CCC, ANN, generative AI, autonomous systems, world models, and learning.

### GSUI-004 — Unfolding Space, Control, and Growth

Introduces:

$$
\mathcal{U}_{possible}
\supseteq
\mathcal{U}_{reachable}
\supseteq
\mathcal{U}_{allowed}
\supseteq
\mathcal{U}_{preferred}
\supseteq
\mathcal{U}_{selected}
$$

and develops Control Plane, Search vs Unfolding, Certification, Feedback, and Structural Growth.

### GSUI-005 — Structural Self: The Reference Frame of Unfolding

Introduces Structural Self and connects:

```text
Self
↔
Perception
↔
World Model
↔
Unfolding Space
↔
Invariant
↔
Growth
↔
Governance
```

---

# 25. Figures

The initial figure set provides a visual route through the GSUI framework.

### Fig-000 — GSUI Grand Map

The complete lifecycle from Folding to Structure, Unfolding, Control, Feedback, Growth, and updated structure.

### Fig-001 — Folding–Structure–Unfolding Cycle

The two complementary halves of the intelligence cycle.

### Fig-002 — Core Structure + Delta Modification

The canonical:

```text
<Core Structure> +/- <Delta Modification>
```

form.

### Fig-003 — Unfolding Intelligence Across Domains

Cross-domain comparison of LLM, CallingGraph, Tree, CCC, ANN, Generative AI, and autonomous systems.

### Fig-004 — Unfolding Space and Control Plane

```text
Possible
→ Reachable
→ Allowed
→ Preferred
→ Selected
→ Certified
```

### Fig-005 — Structural Self as the Reference Frame of Unfolding

Structural Self, world-model meaning, continuity, capability, Delta, and future Unfolding Space.

See:

`docs/FIGURE-INDEX.md`

for detailed placement guidance.

---

# 26. Research Lineage

GSUI emerges from several related structural-intelligence directions.

```text
LLM Structural Evolution
        │
        └── Folding / Unfolding
                    │
                    │
CallingGraph Unfolding
        │
        └── CG → Planning → Coding
             → Certification → Growth
                    │
                    ▼
          GENERAL STRUCTURE
              UNFOLDING
                    │
                    ▼
        STRUCTURE UNFOLDING
             INTELLIGENCE
```

Several neighboring research directions provide complementary concepts:

```text
Runtime Invariant / RIA
→ continuity and invariant preservation

Runtime Computational Primitives
→ candidate primitive layer

CCC / Metric / ANN
→ candidate unfolding mechanisms

Structural Continual Learning
→ persistent structural growth

CallingGraph AI Coding
→ consequential structural certification
```

GSUI is intended to connect these ideas without collapsing their distinct functions.

---

# 27. Six Foundational Statements

The initial GSUI repository is organized around six foundational statements.

### 1.

> **Intelligence does not begin only with computation over data; it can also be studied as the unfolding of structure.**

### 2.

> **A broad class of intelligent processes can be represented as `<Core Structure> +/- <Delta Modification>`.**

### 3.

> **Generation is one form of unfolding; unfolding is broader than generation.**

### 4.

> **Intelligent unfolding requires not only possibility, but triggering, constraint, policy, evaluation, feedback, and invariant preservation.**

### 5.

> **Human-defined intelligence categories may eventually compress into a much smaller set of general unfolding primitives.**

### 6.

> **Structural Self may be understood as the persistent reference structure relative to which unfolding and continuity are defined.**

---

# 28. Methodological Boundary

GSUI is intentionally broad.

Therefore methodological discipline is essential.

The framework should not become:

```text
Everything is structure.

Everything is unfolding.

Therefore everything is GSUI.
```

That would make the theory unfalsifiable and analytically weak.

A useful GSUI analysis should identify concrete answers to questions such as:

```text
What persists?

What unfolds?

What is Delta?

What triggers Delta?

What defines the candidate space?

What constrains the candidate space?

What selects among candidates?

What must remain invariant?

What crosses into consequential action?

What feedback returns?

What becomes persistent structure?
```

If these questions reveal no useful structural organization, GSUI should not be forced onto the system.

---

# 29. Claim Discipline

The repository distinguishes among:

```text
Core Claims

Working Hypotheses

Open Questions
```

This separation is important because GSUI combines:

* relatively direct structural observations;
* cross-domain theoretical extensions;
* and more speculative research directions.

See:

`docs/GSUI-CLAIMS.md`

for the explicit claim hierarchy.

---

# 30. Repository Structure

```text
General-Structure-Unfolding-Intelligence-GSUI/
│
├── README.md
├── START-HERE.md
├── CONTENTS.md
│
├── docs/
│   ├── GSUI-001-From-Folding-to-Unfolding.md
│   ├── GSUI-002-Core-Structure-and-Delta-Modification.md
│   ├── GSUI-003-General-Structure-Unfolding-Intelligence.md
│   ├── GSUI-004-Unfolding-Space-Control-and-Growth.md
│   ├── GSUI-005-Structural-Self-The-Reference-Frame-of-Unfolding.md
│   │
│   ├── GSUI-CLAIMS.md
│   ├── FUTURE-DIRECTIONS.md
│   ├── GLOSSARY.md
│   └── FIGURE-INDEX.md
│
├── figures/
│   ├── Fig-000-GSUI-Grand-Map.png
│   ├── Fig-001-Folding-Structure-Unfolding-Cycle.png
│   ├── Fig-002-Core-Structure-Delta-Modification.png
│   ├── Fig-003-Unfolding-Intelligence-Across-Domains.png
│   ├── Fig-004-Unfolding-Space-and-Control-Plane.png
│   └── Fig-005-Structural-Self-as-Unfolding-Reference-Frame.png
│
├── CITATION.cff
├── .zenodo.json
└── LICENSE
```

---

# 31. Recommended Reading Path

For a first reading:

```text
README
   ↓
GSUI-001
   ↓
GSUI-002
   ↓
GSUI-003
   ↓
GSUI-004
   ↓
GSUI-005
```

For the shortest conceptual route:

```text
Folding
   ↓
Core + Delta
   ↓
Unfolding Space
   ↓
Control
   ↓
Growth
   ↓
Structural Self
```

For governance:

```text
GSUI-003
   ↓
GSUI-004
   ↓
GSUI-005
```

For future research:

```text
GSUI-CLAIMS
   ↓
FUTURE-DIRECTIONS
```

---

# 32. What This Repository Is

This repository is intended as a:

> **foundational launch repository for General Structure Unfolding Intelligence.**

It is not intended to be a complete theory of intelligence.

Version 1.0 establishes:

```text
Problem
Vocabulary
Canonical structural form
Cross-domain hypothesis
Unfolding Space
Control Plane
Structural Growth
Structural Self
Research boundaries
Future directions
```

The objective is to make the research problem explicit enough that it can be:

```text
criticized,
formalized,
implemented,
tested,
extended,
or rejected.
```

That is more useful than prematurely claiming completion.

---

# 33. What Comes Next?

Several next-stage directions are especially important:

```text
Unfolding Primitive Algebra

Unfolding Space Geometry

Invariant-Preserving Unfolding

Generic Unfolding Runtime

Structural Certification

Machine-Native Perception

Self-Relative World Models

Structural Self Runtime

Autonomous Structural Growth

Control-Plane Evolution
```

A future runtime implementation should be added only when generic abstractions become sufficiently clear.

Candidate abstractions may eventually include:

```text
CoreStructure

Delta

UnfoldingOperator

Trigger

Policy

Invariant

Evaluator

Certifier

Feedback

GrowthOperator
```

The theory should lead the runtime rather than forcing the theory into a premature toy implementation.

---

# 34. Final Perspective

The history of AI can be viewed partly as a history of building increasingly powerful structures.

```text
Rules

Trees

Graphs

Neural Networks

Large Language Models

World Models

Agent Systems
```

GSUI asks what happens after those structures exist.

How are they activated?

How do they expose possible futures?

How are Deltas selected?

How are consequences controlled?

How does successful unfolding become future structure?

And relative to what persistent structure are all these changes defined?

This produces the larger GSUI picture:

```text
WORLD
  ↓
FOLDING
  ↓
STRUCTURE
  ↓
UNFOLDING SPACE
  ↓
DELTA
  ↓
CONTROL
  ↓
CONSEQUENCE
  ↓
FEEDBACK
  ↓
GROWTH
  ↓
NEW STRUCTURE
```

with:

```text
STRUCTURAL SELF
```

providing a persistent reference frame across the cycle.

The central research proposition is therefore:

> **A broad class of intelligent processes may be understood not merely as computation over representations, but as controlled structural unfolding from persistent structure.**

And the deeper developmental proposition is:

> **Intelligence can change not only its answers, but the structure of what it can unfold next.**

Finally, as machine intelligence becomes less anthropomorphic:

> **Machine-native cognition should expand the space of intelligence without dissolving the structural interfaces through which consequential action remains observable, certifiable, and governable.**

---

## GSUI in One Screen

```text
Observation
    ↓
FOLDING
    ↓
CORE STRUCTURE
    │
    ├──── Structural Self
    │
    ▼
UNFOLDING SPACE
    ↓
Candidate Δ
    ↓
CONTROL PLANE
    ↓
Selected / Certified Δ
    ↓
S' = S ± Δ
    ↓
Action / Generation
    ↓
Feedback
    ↓
STRUCTURAL GROWTH
    ↓
NEW CORE STRUCTURE
    ↓
NEW UNFOLDING SPACE
```

> **Structure defines possibility.**

> **Control organizes possibility.**

> **Unfolding realizes possibility.**

> **Feedback evaluates consequence.**

> **Growth changes future possibility.**

> **Structural Self provides continuity across the entire process.**

---

## License

See `LICENSE`.

---

## Citation

Citation metadata is provided in:

* `CITATION.cff`
* `.zenodo.json`

---

**GSUI — General Structure Unfolding Intelligence**

**From Core Structure and Delta Modification to a General Paradigm of Intelligence**



---

## Author

Sizhe Tan\
Independent Researcher

GPT-Obot\
AI Research Assistant

2026

DOI: TBD
    
---

## 📚 DBM-SI Series Navigation

See:\
[./docs/DBM-SI-Series-of-gitHub-Repositories/DBM-SI-Series-of-gitHub-Repositories.md](./docs/DBM-SI-Series-of-gitHub-Repositories/DBM-SI-Series-of-gitHub-Repositories.md)

[./docs/DBM-SI-Series-of-gitHub-Repositories/DBM-SI-Structural-Intelligence-Dictionary-(v2).md](./docs/DBM-SI-Series-of-gitHub-Repositories/DBM-SI-Structural-Intelligence-Dictionary-(v2).md)


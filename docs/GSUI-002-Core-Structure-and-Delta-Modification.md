# GSUI-002 — Core Structure and Delta Modification

## A Minimal Structural Form for General Structure Unfolding Intelligence

**General Structure Unfolding Intelligence (GSUI)**
**Foundational Paper 002**

---

## Abstract

General Structure Unfolding Intelligence begins from a simple observation:

> An intelligent system rarely creates every runtime result from nothing.

Instead, it operates from an already existing structure.

That structure may be:

* a neural model,
* a CallingGraph,
* a decision tree,
* a policy structure,
* a CCC,
* a world model,
* a memory system,
* a trajectory structure,
* a software architecture,
* or a biological control structure.

Runtime intelligence then produces a change relative to this existing structure.

This motivates a minimal expression:

$$
S_{t+1}=S_t \pm \Delta_t
$$

or, in structural language:

```text
<Core Structure> +/- <Delta Modification>
```

This paper develops that expression into a more general framework.

It distinguishes:

* Core Structure,
* Delta Modification,
* Unfolding Operator,
* Context,
* Trigger,
* Constraint,
* Policy,
* Candidate Structure,
* Invariant,
* Evaluation,
* Certification,
* Feedback,
* and Structural Growth.

The central claim is not that all intelligent systems execute the same algorithm.

Rather:

> **A broad class of intelligent processes can be studied through the relation between a persistent structural core and controlled modifications relative to that core.**

This viewpoint is useful because it shifts attention from unconstrained output generation toward **structural continuity, admissible change, runtime control, and future growth**.

---

# 1. The Minimal GSUI Form

The simplest structural expression is:

$$
S_{t+1}=S_t \pm \Delta_t
$$

where:

* \(S_t\) is the current structure;
* \(\Delta_t\) is a structural modification;
* \(S_{t+1}\) is the resulting structure or runtime state.

In compact form:

```text
<Core Structure> +/- <Delta Modification>
```

This expression is intentionally broad.

It may represent:

```text
CallingGraph + new branch
Tree - obsolete branch
Policy + new condition
ANN state + activation change
Trajectory + steering correction
LLM runtime + generated continuation
Repository + software modification
Memory + retained experience
```

The notation does not imply that every structure supports literal arithmetic addition or subtraction.

The symbols `+/-` represent generalized structural modification.

---

However, the expression

$$
\[
S' = S \pm \Delta
\]
$$

contains an important hidden requirement.

A Delta cannot be defined in isolation.

Change always requires a reference:

changed relative to what?

added to what?

removed from what?

preserved relative to what?

![Fig-002 — Reference Frame of Unfolding](../figures/Fig-002-Reference-Frame-of-Unfolding.png)

**Fig-002 — Reference Frame of Unfolding.**  
Structural change is meaningful only relative to a reference structure. In GSUI, a local Delta may be measured relative to Core Structure, while longer-term continuity may be defined relative to Structural Self.

This gives the Core Structure a second role.

It is not merely stored structure.

It is also the local reference relative to which structural difference becomes meaningful.

Thus:

$$
\[
\Delta_t = Difference(S_t,S_{t+1})
\]
$$

is meaningful only because \(S_t\) provides the reference.

---

# 2. Why Core Structure Matters

A Delta is meaningful only relative to something that already exists.

Without a Core Structure:

```text
Δ relative to what?
```

cannot be answered.

This makes the Core Structure concept fundamental.

A **Core Structure** is the persistent structure that provides continuity across one or more unfolding operations.

It may include:

```text
Topology
Parameters
Relations
Rules
Memory
Runtime State
Capabilities
Interfaces
Constraints
Invariants
```

The core need not be completely immutable.

A structure can grow while still preserving enough continuity to be treated as the same evolving system.

Thus:

> **Core does not mean frozen. Core means structurally persistent enough to serve as the reference frame for modification.**

---

# 3. Core Structure Is Not Necessarily the Whole System

The Core Structure should not automatically be identified with everything inside a system.

For example, an AI coding system may contain:

```text
LLM
Repository
CallingGraph
Task Context
Tests
Policy
Runtime Memory
```

Yet the relevant Core Structure for one unfolding operation might be only:

```text
Repository CallingGraph
```

For another operation, it may be:

```text
Task Planning Tree
```

For another:

```text
Agent Runtime State
```

Therefore Core Structure is partly **operation-relative**.

A useful formulation is:

$$
S^{core}_{t}(U)
$$

meaning:

> the portion of the current system treated as structurally persistent with respect to unfolding operator \(U\).

This avoids a common mistake:

> assuming that intelligence must have one universal structural center at every level of analysis.

Different unfolding problems may expose different cores.

---

# 4. Delta as the Unit of Structural Change

If Core Structure represents persistence, Delta represents change.

A Delta can be defined as:

> **A candidate modification relative to an existing structural reference.**

In the simplest form:

$$
\Delta_t = S_{t+1}-S_t
$$

Again, the subtraction is conceptual rather than necessarily numeric.

The Delta may describe:

```text
Added nodes
Removed nodes
Changed edges
Parameter change
Branch selection
Policy modification
Trajectory correction
State transition
Activation pattern
Memory update
Interface change
Constraint change
```

This makes Delta a potentially useful common abstraction across many AI systems.

---

# 5. Delta Is Broader Than Addition

One of the most important points in GSUI is:

> **Unfolding is not equivalent to expansion.**

A structure may unfold through many operators.

A preliminary Delta family includes:

```text
ADD
REMOVE
REPLACE
BRANCH
MERGE
SPLIT
CONNECT
DISCONNECT
REWEIGHT
MOVE
ACTIVATE
INHIBIT
SELECT
SAMPLE
INSTANTIATE
COMPRESS
EXPAND
PRESERVE
```

Therefore:

```text
Core + Delta
```

should not be read narrowly as:

```text
Core + More Structure
```

A better interpretation is:

> **Core subjected to a controlled structural transformation.**

This distinction allows GSUI to describe:

* generation,
* routing,
* suppression,
* repair,
* adaptation,
* selection,
* pruning,
* reconfiguration,
* and control.

---

# 6. Preservation Is Also a Delta Decision

An interesting boundary case is:

```text
Δ = 0
```

or its structural equivalent:

> preserve the current state.

This matters because intelligent systems frequently decide **not to change**.

Examples include:

```text
Do not modify this function.
Do not take this branch.
Maintain current lane.
Preserve this invariant.
Reject candidate code.
Keep the existing policy.
```

Therefore preservation should not be treated as absence of intelligence.

It can itself be the result of evaluation.

In this sense:

> **Intelligent unfolding includes intelligent non-modification.**

The action:

```text
PRESERVE
```

belongs inside the unfolding operator family.

---

# 7. From Delta to Unfolding Operator

A Delta describes what changes.

An **Unfolding Operator** describes how a change is produced or applied.

We may write:

$$
S_{t+1}=U(S_t,\Delta_t)
$$

where \(U\) is the unfolding operator.

Different systems may implement radically different operators.

Examples include:

```text
Neural activation
Graph expansion
Tree traversal
Branch creation
Policy routing
Metric-based selection
Trajectory update
Token generation
Rule application
Structural mutation
Memory incorporation
```

This leads to an important distinction:

```text
Delta
= What changes

Operator
= How change is produced
```

Two systems may produce structurally similar Deltas through completely different operators.

Likewise, one operator may produce many different Delta forms.

---

# 8. Context-Conditioned Unfolding

Most intelligent unfolding is not context-free.

The same Core Structure may unfold differently under different conditions.

Therefore:

$$
S_{t+1}=U(S_t,\Delta_t,C_t)
$$

where \(C_t\) represents context.

Context may include:

```text
Environment
Prompt
Task
Observed State
History
User Request
Sensor Input
Repository State
Runtime Condition
External Event
```

For example:

```text
Same LLM
+ different prompt
→ different continuation

Same CallingGraph
+ different coding task
→ different ΔCG

Same vehicle
+ different road state
→ different trajectory

Same CCC
+ different condition/context
→ different behavior
```

Thus unfolding should generally be treated as **context-conditioned structural transformation**.

---

# 9. Triggering: Why Unfold Now?

Context alone does not explain why a structure becomes active at a particular time.

GSUI therefore distinguishes **Context** from **Trigger**.

Context answers:

> What conditions currently exist?

Trigger answers:

> Why does unfolding begin now?

A trigger may be:

```text
Prompt arrival
Sensor threshold
Function call
Policy condition
External request
Detected anomaly
Goal activation
Timer event
Failure event
Structural gap
```

The resulting form becomes:

$$
S_{t+1}=U(S_t,\Delta_t,C_t,T_t)
$$

where \(T_t\) is a triggering condition or event.

This distinction matters for runtime intelligence.

A structure may contain significant latent capability without continuously unfolding all of it.

Triggering selects which part becomes operational.

---

# 10. Constraints Define the Boundary of Change

Not every possible Delta should be allowed.

Let:

$$
\mathcal{D}_{possible}(S_t)
$$

represent possible Deltas.

Constraints define a smaller set:

$$
\mathcal{D}_{allowed}(S_t,C_t)
\subseteq
\mathcal{D}_{possible}(S_t)
$$

Examples of constraints include:

```text
Physical limits
API contracts
Security boundaries
Safety rules
Type constraints
Resource limits
CallingGraph boundaries
Policy restrictions
Biological limits
Runtime invariants
```

Therefore intelligence is not simply:

> produce many possible modifications.

It is also:

> **exclude structurally unacceptable modifications.**

Constraint is therefore not an optional governance layer added after intelligence.

It can be part of intelligence itself.

---

# 11. Policy Chooses Among Allowed Deltas

Constraints define what is permitted.

Policy helps determine what is preferred.

We may define:

$$
P_t:
\mathcal{D}_{allowed}
\rightarrow
Preference
$$

A policy may encode:

```text
Safety preference
Performance objective
Energy preference
Risk tolerance
User intent
Coding style
Business rule
Trajectory strategy
Priority rule
Governance rule
```

Thus:

```text
Possible Delta
      ↓
Constraint
      ↓
Allowed Delta
      ↓
Policy
      ↓
Preferred Delta
```

This introduces an important GSUI distinction:

> **Possible does not mean allowed. Allowed does not mean preferred. Preferred does not mean selected.**

---

# 12. Candidate Delta and Selected Delta

An intelligent system may generate many candidates:

$$
\Delta_1,\Delta_2,\ldots,\Delta_n
$$

These form a candidate set:

$$
\mathcal{D}_{candidate}
$$

Evaluation may then assign scores or structural judgments:

$$
E(\Delta_i\mid S_t,C_t,P_t)
$$

Selection produces:

$$
\Delta^*
$$

where:

$$
\Delta^* =
Select(\mathcal{D}_{candidate})
$$

The structural process becomes:

```text
Core Structure
      ↓
Candidate Generation
      ↓
Δ1   Δ2   Δ3   ...   Δn
      ↓
Constraint
      ↓
Policy
      ↓
Evaluation
      ↓
Selected Δ*
```

This pattern appears in many seemingly different algorithms.

---

# 13. Evaluation Is Not Necessarily Scalar

Traditional optimization often imagines evaluation as:

$$
E(\Delta)\rightarrow score
$$

But GSUI should not assume that every structural evaluation reduces to one number.

Evaluation may be:

```text
Boolean
Ordinal
Multi-objective
Policy-based
Constraint-based
Structural
Metric
Probabilistic
Human-reviewed
Certification-based
```

For example:

```text
Does the CG preserve required dependency structure?

Does this trajectory remain inside the safe corridor?

Does the code pass tests?

Does the candidate violate an invariant?

Is the structural modification authorized?
```

Thus evaluation is broader than reward maximization.

---

# 14. Invariants: What Must Survive Change?

If a system changes continuously, another question arises:

> What must remain preserved?

This introduces the concept of an **Invariant**.

Let:

$$
I(S_t)
$$

represent a required structural property.

A candidate structure may be accepted only if:

$$
I(S_{t+1}) = true
$$

or more generally:

$$
I_k(S_{t+1}) \in AcceptableRange_k
$$

for a set of invariants \(I_1,\ldots,I_m\).

Examples include:

```text
API compatibility
Safety boundary
Identity continuity
CallingGraph requirement
Type correctness
Security property
Control stability
Mission constraint
Core behavioral requirement
```

The unfolding process therefore becomes:

$$
S_t
\rightarrow
\Delta
\rightarrow
S_{t+1}
\rightarrow
Invariant\ Check
$$

This is crucial because:

> **A useful Delta is not merely a change. It is a change that preserves what must remain preserved.**

---

# 15. Core and Invariant Are Related but Different

Core Structure and Invariant should not be collapsed into one concept.

The Core Structure is:

> the current structural reference.

An Invariant is:

> a property that must remain sufficiently preserved across modification.

For example:

```text
Core Structure:
Current CallingGraph

Invariant:
Public API must remain callable
```

or:

```text
Core Structure:
Current vehicle state

Invariant:
Vehicle remains dynamically stable
```

The structure itself may change significantly while the invariant continues to hold.

Therefore:

```text
Core
≠
Invariant
```

Instead:

```text
Core
provides the reference for change

Invariant
defines continuity or admissibility across change
```

---

# 16. Structural Continuity

This distinction leads to an important GSUI problem:

> At what point does modified structure cease to count as a continuation of the original structure?

Suppose:

$$
S_0
\rightarrow
S_1
\rightarrow
S_2
\rightarrow
...
\rightarrow
S_n
$$

Each transition may be locally acceptable.

Yet after many Deltas, the system may be radically different.

Therefore structural continuity cannot always be inferred from one-step similarity.

Possible continuity criteria may include:

```text
Invariant continuity
Functional continuity
Identity continuity
Topology continuity
Policy continuity
Memory continuity
Goal continuity
Runtime continuity
```

This question becomes especially important for:

* continual learning,
* autonomous agents,
* self-modifying software,
* evolving AI systems,
* Structural Self.

---

# 17. Structural Self Emerges Naturally from Core + Delta

The concept of Structural Self does not need to begin from consciousness.

It appears directly from the Core + Delta framework.

To define:

$$
\Delta_t
$$

we need a reference structure:

$$
S_t
$$

To determine continuity across:

$$
S_t \rightarrow S_{t+1}
$$

we need some persistent structural relation.

This motivates:

> **Structural Self as the persistent reference structure relative to which Delta, continuity, capability, and unfolding are defined.**

In compact form:

```text
Structural Self
      ↓
Reference Structure
      ↓
Possible Δ
      ↓
Allowed Δ
      ↓
Selected Δ
      ↓
Updated Self
```

Thus Structural Self is not introduced merely for philosophical interest.

It emerges as an operational requirement of structural change.

---

# 18. Delta Is Self-Relative

Suppose two systems encounter the same external event.

Their structural Deltas may differ because their structures differ.

Let:

$$
Self_A \neq Self_B
$$

Then:

$$
\Delta_A(World)
\neq
\Delta_B(World)
$$

may hold even under the same external conditions.

For example:

```text
Same narrow passage

Small robot
→ PASS

Large vehicle
→ BLOCKED
```

The world did not change.

The Structural Self changed.

Therefore operational Delta is often:

$$
\Delta =
\Delta(World,Self,Context)
$$

rather than simply:

$$
\Delta =
\Delta(World)
$$

This provides a structural basis for self-relative world models and self-relative perception.

---

# 19. Perception as Delta-Relevant Structuring

Perception can now be connected directly to Delta formation.

A system need not perceive everything.

It needs to construct representations relevant to possible unfolding.

We may write:

$$
Perception
\rightarrow
Operational\ Structure
\rightarrow
Candidate\ Delta
$$

For a machine, this may involve features that have no human perceptual counterpart.

Examples include:

```text
Dependency changes
Memory pressure
Graph centrality
Latency shifts
Packet topology
RF structure
Machine state transitions
CallingGraph gaps
```

Thus:

> **Perception can be understood partly as the construction of structures required for meaningful Delta selection.**

This supports machine-native perception without requiring machine action to become ungoverned.

---

# 20. Delta and World Model

A world model becomes operationally useful when it helps estimate consequences of candidate Deltas.

A simple form is:

$$
WM(S_t,\Delta_t)
\rightarrow
\widehat{S}_{t+1}
$$

or for embodied systems:

$$
WM(Self_t,World_t,\Delta_t)
\rightarrow
\widehat{World}_{t+1}
$$

This reframes world-model reasoning.

The model is not only trying to answer:

> What happens next?

It may instead answer:

> **What happens if this Structural Self unfolds through this Delta?**

That form is much closer to planning and control.

---

# 21. Delta and Planning

Planning can be represented as prospective Delta composition.

Suppose:

$$
\Delta_1,\Delta_2,\ldots,\Delta_n
$$

form a candidate trajectory.

Then:

$$
S_n =
U_n(
...
U_2(
U_1(S_0,\Delta_1),
\Delta_2
)
...
,\Delta_n
)
$$

Planning explores possible sequences of unfolding before committing to external action.

Thus:

> **Planning can be viewed as simulated structural unfolding.**

This applies naturally to:

* software modification;
* robot motion;
* task decomposition;
* tree search;
* multi-step reasoning;
* policy execution.

---

# 22. Delta and Generative AI

Generative AI is naturally expressible in this framework.

For text generation:

```text
Core Model
    +
Context
    ↓
Candidate Token Delta
    ↓
Selection
    ↓
Updated Runtime Sequence
```

Repeatedly:

$$
S_{t+1}=U(S_t,\Delta_t)
$$

For code generation:

```text
Repository Structure
        +
Task
        ↓
Candidate Structural Delta
        ↓
Code Realization
```

For image generation:

```text
Latent / Model Structure
        +
Condition
        ↓
Iterative State Delta
        ↓
Generated Image
```

Therefore generation is a natural GSUI application.

But again:

> **Delta Modification is broader than generation.**

---

# 23. CallingGraph Delta as a Canonical Example

CallingGraph-based AI coding provides a particularly readable structural example.

Suppose:

$$
CG_t
$$

is the current CallingGraph.

A coding task produces candidate structural modifications:

$$
\Delta CG_1,\Delta CG_2,\ldots,\Delta CG_n
$$

The system evaluates:

```text
Does the branch fit?
Does it preserve required calls?
Does it violate architecture?
Does it introduce forbidden dependencies?
Does implementation match the planned graph?
```

A selected modification produces:

$$
CG_{t+1} =
CG_t
\pm
\Delta CG^*
$$

Generated code then realizes this structural Delta.

Certification checks whether:

$$
ExtractedCG(Code_{new})
\approx
CG_{planned}
$$

under required invariants.

This illustrates an important principle:

> **Structural Delta can serve as an intermediate control object between machine-native reasoning and executable external consequences.**

---

# 24. Internal Unfolding vs Consequential Delta

Not every internal Delta requires external governance.

An AI may internally generate:

```text
Candidate thoughts
Latent transitions
Temporary branches
Hypotheses
Alternative plans
Simulation trajectories
```

Many are harmless until they cross an action boundary.

Therefore GSUI should distinguish:

### Internal Delta

A modification inside the system's reasoning or simulation process.

### Consequential Delta

A modification that changes an external, persistent, privileged, or safety-relevant structure.

Examples:

```text
Deploy code
Move vehicle
Execute transaction
Modify database
Change access control
Rewrite policy
Alter persistent memory
Call external actuator
```

The governance requirement increases sharply at this boundary.

---

# 25. The Structural Control Boundary

A useful general architecture is:

```text
Internal Unfolding
        ↓
Candidate Delta
        ↓
════════════════════════════
   STRUCTURAL CONTROL BOUNDARY
════════════════════════════
        ↓
Constraint Check
        ↓
Policy Check
        ↓
Invariant Check
        ↓
Certification
        ↓
Authorized Delta
        ↓
External / Persistent Change
```

This supports a central principle:

> **Machine-native internal cognition does not imply uncontrolled external modification.**

Or more compactly:

> **Internal unfolding may be rich; consequential Delta must remain governable.**

This is especially important for advanced AI and autonomous systems.

---

# 26. Delta Certification

A candidate Delta may require certification before acceptance.

Certification asks whether the proposed structural change satisfies required conditions.

Let:

$$
Cert(S_t,\Delta_t,I,P)
\rightarrow
\{Accept,Reject\}
$$

or a richer result:

$$
Cert(...)
\rightarrow
Assessment
$$

Certification may include:

```text
Invariant validation
Policy compliance
Test execution
Structural comparison
Security analysis
Human approval
Metric threshold
Runtime simulation
Consistency checking
```

This makes certification distinct from candidate generation.

A system can be excellent at proposing Deltas while still requiring independent mechanisms to determine whether those Deltas should become reality.

---

# 27. Feedback Converts Delta into Learning

After a Delta is executed, the world returns consequences.

Let:

$$
F_t
$$

represent feedback.

Then:

$$
F_t =
Observe(
Result(S_t,\Delta_t)
)
$$

The system may use this feedback to:

```text
Reject the change
Rollback
Adjust the Delta
Update evaluation
Update policy
Update memory
Promote a temporary structure
Change future unfolding space
```

Thus a complete Delta lifecycle is:

```text
Generate
   ↓
Evaluate
   ↓
Select
   ↓
Certify
   ↓
Execute
   ↓
Observe
   ↓
Retain / Reject / Modify
```

This transforms a one-shot unfolding mechanism into a learning system.

---

# 28. Structural Growth

A successful Delta may remain temporary.

Or it may become part of the future Core Structure.

Let:

$$
Promote(\Delta_t)
$$

represent incorporation into persistent structure.

Then:

$$
S^{core}_{t+1} =
S^{core}_t
\pm
Promote(\Delta_t)
$$

This is **Structural Growth**.

Examples include:

```text
New CallingGraph branch
New policy rule
New memory structure
New routing branch
New learned skill
New reusable plan
New representation
New runtime invariant
```

Structural Growth changes future unfolding because it changes the Core Structure itself.

Therefore:

$$
\mathcal{U}(S_t)
\neq
\mathcal{U}(S_{t+1})
$$

may follow after growth.

This is a major distinction between:

```text
temporary inference
```

and:

```text
persistent structural learning
```

---

# 29. Delta Growth Can Expand or Contract Future Intelligence

Growth is not always expansion.

A new structure may:

```text
Open new possibilities
Close unsafe possibilities
Create new branches
Remove obsolete branches
Strengthen constraints
Compress repeated behavior
Add reusable memory
Reduce search
```

Therefore structural development may increase intelligence partly by **reducing** future unfolding space.

For example:

```text
Before learning:
100 candidate paths

After structural learning:
3 high-value paths
```

This suggests:

> **Growth may improve intelligence through both expansion and disciplined contraction of unfolding space.**

This point is important because larger possibility spaces do not automatically imply better intelligence.

---

# 30. Metric, CCC, ANN, Trees, and Other Operator Families

GSUI should avoid claiming that all structures are equivalent.

Instead, different structures may support different unfolding operator families.

For example:

### Metric

```text
Measure distance
Compare alternatives
Select nearest / farthest / thresholded Delta
```

### CCC

```text
Condition
Context
Control
→ constrained transition
```

### Tree

```text
Branch
Route
Expand
Prune
```

### CallingGraph

```text
Connect
Disconnect
Insert call path
Modify dependency topology
```

### ANN

```text
Activate
Suppress
Reweight
Propagate
Sample
```

These systems may share a general unfolding language without sharing one implementation.

This is a central methodological boundary of GSUI.

---

# 31. Toward an Unfolding Primitive Algebra

The Core + Delta framework raises a deeper question:

> Can complex intelligent behavior be reconstructed from a small set of structural operators?

A provisional primitive set might contain:

```text
OBSERVE
COMPARE
TRIGGER
ACTIVATE
INHIBIT
SELECT
BRANCH
MERGE
CONNECT
DISCONNECT
ADD
REMOVE
MOVE
MEMORIZE
RECALL
EVALUATE
CERTIFY
PROMOTE
PRESERVE
```

These are not yet proposed as a final algebra.

The research question is whether many human-defined categories such as:

```text
Reasoning
Planning
Navigation
Generation
Decision
Control
Learning
```

can be compressed into compositions of a smaller number of reusable structural operators.

If this succeeds, GSUI may provide not only a descriptive framework but also a computational primitive framework.

---

# 32. A General Operational Form

Combining the elements introduced so far, a more complete unfolding expression is:

$$
S_{t+1} =
U(
S_t,
\Delta_t,
C_t,
T_t,
P_t,
I_t
)
$$

subject to:

$$
\Delta_t
\in
\mathcal{D}_{allowed}(S_t,C_t,P_t,I_t)
$$

with candidate evaluation:

$$
E(
\Delta_t
\mid
S_t,C_t,P_t
)
$$

and certification:

$$
Cert(
S_t,\Delta_t,I_t,P_t
)
$$

followed by feedback:

$$
F_t =
Observe(S_{t+1},World_{t+1})
$$

and possible structural promotion:

$$
S^{core}_{t+1} =
Grow(
S^{core}_t,\Delta_t,F_t
)
$$

This should not be interpreted as a finalized mathematical theory.

It is a structural scaffold.

Its purpose is to make the components of intelligent unfolding explicit.

---

# 33. The Minimal GSUI Runtime Pattern

A general runtime pattern can now be written:

```text
CORE STRUCTURE
      │
      ▼
Context / Observation
      │
      ▼
Trigger
      │
      ▼
Candidate Delta Formation
      │
      ▼
Possible Δ
      │
      ▼
Constraint
      │
      ▼
Allowed Δ
      │
      ▼
Policy
      │
      ▼
Preferred Δ
      │
      ▼
Evaluation / Selection
      │
      ▼
Selected Δ
      │
      ▼
Invariant / Certification
      │
      ▼
Applied Unfolding
      │
      ▼
NEW STRUCTURE / ACTION
      │
      ▼
Feedback
      │
      ▼
Retain / Reject / Modify
      │
      ▼
Structural Growth
```

This is one candidate canonical pipeline for GSUI.

---

# 34. What Core + Delta Does Not Mean

Because the expression is extremely compact, several misunderstandings should be explicitly avoided.

## 34.1 It Does Not Mean All AI Is Symbolic

The structure may be neural, distributed, latent, physical, graphical, symbolic, or hybrid.

## 34.2 It Does Not Mean Delta Is Human-Readable

Internal Deltas may exist in representations humans cannot directly inspect.

## 34.3 It Does Not Mean Every Delta Should Be Externally Applied

Candidate generation and authorized execution are different stages.

## 34.4 It Does Not Mean Core Never Changes

Core structure may itself evolve through structural growth.

## 34.5 It Does Not Mean Similar Structure Implies Similar Intelligence

Operators, policies, context, feedback, and embodiment also matter.

## 34.6 It Does Not Mean Unfolding Is Always Generative

Selection, inhibition, preservation, routing, and deletion are also valid forms.

## 34.7 It Does Not Mean One Scalar Objective Is Sufficient

Evaluation can be multi-dimensional, policy-based, structural, or certified.

---

# 35. Core + Delta as a Research Lens

The main value of the Core + Delta framework is not that it provides a final equation for intelligence.

Its value is that it forces a useful set of questions.

For any intelligent system, ask:

```text
What is the Core Structure?

What counts as a Delta?

Who or what generates candidate Deltas?

What triggers change?

What context conditions the change?

What is physically or logically possible?

What is allowed?

What is preferred?

What must remain invariant?

How is a Delta evaluated?

How is it certified?

What crosses the external action boundary?

What feedback returns?

Which Deltas become persistent structure?

How does the resulting structure change future unfolding?
```

These questions are applicable across very different domains.

That makes Core + Delta useful as a **comparative structural lens**.

---

# 36. Initial GSUI Principles from Core + Delta

This paper establishes several provisional principles.

### Principle 1 — No Delta Without Reference Structure

Structural change is defined relative to an existing structure.

### Principle 2 — Delta Is More General Than Addition

Modification includes addition, deletion, replacement, selection, activation, inhibition, branching, merging, preservation, and other transformations.

### Principle 3 — Intelligent Delta Is Context-Conditioned

The same structure may unfold differently under different contexts and triggers.

### Principle 4 — Possible, Allowed, Preferred, and Selected Are Different

Unfolding requires boundaries and choice.

### Principle 5 — Invariants Define What Must Survive

Change and continuity must be studied together.

### Principle 6 — Evaluation Is Broader Than Optimization

Structural validity, policy, certification, and human governance may matter independently of scalar reward.

### Principle 7 — Internal and Consequential Delta Must Be Distinguished

Machine-native internal cognition may remain flexible while consequential external change remains controlled.

### Principle 8 — Feedback Determines Whether Delta Becomes Growth

A temporary unfolding becomes structural learning only when selected results are incorporated into future structure.

### Principle 9 — Structural Growth Changes Future Unfolding Space

Learning alters not only current state but future possibility.

### Principle 10 — Structural Self Is a Natural Reference Frame

Persistent structure provides the operational reference relative to which Delta and continuity are defined.

---

# 37. Canonical Structural Diagram

```text
                    ┌─────────────────────┐
                    │   CORE STRUCTURE    │
                    │        S_t          │
                    └──────────┬──────────┘
                               │
                    Context / Trigger
                               │
                               ▼
                    ┌─────────────────────┐
                    │   DELTA FORMATION   │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
                Δ1            Δ2            Δ3
                 │             │             │
                 └─────────────┼─────────────┘
                               ▼
                    Possible Delta Space
                               │
                         Constraints
                               ▼
                     Allowed Delta Space
                               │
                           Policy
                               ▼
                    Preferred Delta Space
                               │
                    Evaluation / Selection
                               ▼
                         Selected Δ*
                               │
                               ▼
                    ┌─────────────────────┐
                    │ INVARIANT / POLICY  │
                    │    CERTIFICATION    │
                    └──────────┬──────────┘
                               │
                         Accept / Reject
                               │
                               ▼
                     S_(t+1) = S_t ± Δ*
                               │
                               ▼
                    Action / New Structure
                               │
                               ▼
                           Feedback
                               │
                               ▼
                     Structural Growth
                               │
                               └────────────►
                              Updated Core
```

---

# 38. Canonical Form

The minimal GSUI structural form remains:

```text
<Core Structure> +/- <Delta Modification>
```

The operational form is:

$$
S_{t+1} =
U(
S_t,
\Delta_t,
C_t,
T_t,
P_t,
I_t
)
$$

with:

```text
S  = Core / Current Structure
Δ  = Delta Modification
U  = Unfolding Operator
C  = Context
T  = Trigger
P  = Policy
I  = Invariants
E  = Evaluation
F  = Feedback
G  = Structural Growth
```

A fuller lifecycle is:

```text
Core
  ↓
Trigger
  ↓
Context
  ↓
Candidate Delta
  ↓
Constraint
  ↓
Policy
  ↓
Evaluation
  ↓
Selection
  ↓
Certification
  ↓
Unfolding
  ↓
Feedback
  ↓
Growth
  ↓
Updated Core
```

---

# 39. Conclusion

General Structure Unfolding Intelligence requires a language for talking about both persistence and change.

The minimal pair is:

```text
CORE
+
DELTA
```

Core Structure answers:

> **What persists?**

Delta Modification answers:

> **What changes?**

Unfolding Operator answers:

> **How does change occur?**

Context and Trigger answer:

> **Under what conditions and why now?**

Constraint and Policy answer:

> **What may change and what should be preferred?**

Invariant answers:

> **What must remain preserved?**

Evaluation and Certification answer:

> **Which change should become consequential?**

Feedback answers:

> **What happened after unfolding?**

Structural Growth answers:

> **What should become part of future structure?**

Together they transform the simple expression:

$$
S_{t+1}=S_t\pm\Delta_t
$$

into a general research framework for controlled structural change.

The central GSUI proposition emerging from this paper is therefore:

> **Intelligence can be studied as the controlled production, selection, certification, execution, and retention of Delta relative to persistent structure.**

This does not replace neural networks, graphs, trees, CCCs, policies, metrics, world models, or other computational mechanisms.

It provides a common structural language in which their unfolding behavior can be compared.

The next step is to move from this minimal structural form toward the broader paradigm:

> **General Structure Unfolding Intelligence.**

---

## Canonical Summary

```text
CORE STRUCTURE
      +
CONTEXT
      +
TRIGGER
      ↓
CANDIDATE DELTA
      ↓
CONSTRAINT
      ↓
POLICY
      ↓
EVALUATION
      ↓
SELECTED DELTA
      ↓
INVARIANT / CERTIFICATION
      ↓
UNFOLDING
      ↓
NEW STRUCTURE / ACTION
      ↓
FEEDBACK
      ↓
STRUCTURAL GROWTH
      ↓
UPDATED CORE STRUCTURE
```

### Minimal Expression

```text
<Core Structure> +/- <Delta Modification>
```

### Core GSUI Question

> **What may change, what must remain, and how should the transition between the two be governed?**

---

**GSUI-002**
**General Structure Unfolding Intelligence**
**Foundational Series**

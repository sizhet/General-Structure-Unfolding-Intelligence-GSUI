# GSUI-003 — General Structure Unfolding Intelligence

## A General Paradigm for Structure-Conditioned Intelligence

**General Structure Unfolding Intelligence (GSUI)**
**Foundational Paper 003**

---

## Abstract

Artificial intelligence is usually divided into task categories:

```text
Perception
Recognition
Prediction
Reasoning
Planning
Generation
Decision
Control
Navigation
Learning
Coding
```

These categories are useful.

But they may not correspond to the deepest reusable structure of intelligence.

General Structure Unfolding Intelligence (GSUI) proposes a different research question:

> **Can many apparently different intelligent processes be studied as context-conditioned unfolding of persistent structure?**

The minimal structural form is:

```text
<Core Structure> +/- <Delta Modification>
```

or:

$$
S_{t+1}=U(S_t,\Delta_t,C_t,T_t,P_t,I_t)
$$

where:

* \(S_t\) is current structure;
* \(\Delta_t\) is a candidate structural modification;
* \(C_t\) is context;
* \(T_t\) is triggering;
* \(P_t\) is policy;
* \(I_t\) represents relevant invariants;
* \(U\) is an unfolding operator.

This paper develops GSUI as a general intelligence paradigm.

It compares:

* large language models,
* CallingGraph-based AI coding,
* trees,
* CCC structures,
* artificial neural networks,
* generative AI,
* autonomous driving,
* world-model systems,
* planning,
* perception,
* and structural growth.

The claim is not that these systems execute one common algorithm.

The stronger and more defensible proposition is:

> **Many intelligent systems share a structural form in which an existing structure constrains, enables, and governs possible next states, behaviors, actions, or structural modifications.**

GSUI therefore studies intelligence through:

```text
Structure
→ Unfolding Space
→ Candidate Delta
→ Control
→ Selection
→ Consequence
→ Feedback
→ Growth
```

This perspective also supports machine-native perception while preserving human-governable external consequences.

The result is a research program concerned not only with how intelligence is formed, but with **how structure becomes intelligence at runtime**.

---

# 1. Why a General Unfolding Paradigm?

Modern AI has produced many powerful specialized concepts.

Examples include:

```text
Inference
Generation
Planning
Search
Control
Routing
Activation
Prediction
World modeling
Continual learning
Code generation
```

These concepts describe real differences.

They should not be discarded.

But another question remains:

> **Are some of these differences differences of application rather than differences of fundamental runtime structure?**

For example:

A language model produces a continuation.

A decision tree selects a branch.

A robot selects a trajectory.

A CallingGraph-guided coding system modifies software topology.

A neural network propagates activation.

A policy system selects a permitted action.

A continual learner incorporates a successful modification into future structure.

These operations are not identical.

But each can be examined through a common question:

> **Given an existing structure, what changes can unfold from it under current conditions?**

This question motivates GSUI.

---

# 2. From Task Categories to Structural Form

Traditional AI classification frequently begins from what a system does.

For example:

```text
Predict
Reason
Generate
Navigate
Control
Learn
```

GSUI begins one level lower.

It asks:

```text
What structure already exists?

What can unfold from that structure?

What Delta is possible?

What Delta is allowed?

What determines selection?

What must remain invariant?

What becomes persistent afterward?
```

This shifts the analytical unit from:

```text
Task Name
```

toward:

```text
Structural Transition
```

The central transition is:

$$
S_t \rightarrow S_{t+1}
$$

with:

$$
S_{t+1}=S_t\pm\Delta_t
$$

under runtime conditions.

---

# 3. A Provisional Definition of GSUI

A working definition is:

> **General Structure Unfolding Intelligence is the study and construction of intelligent systems in which persistent structure is contextually unfolded through candidate structural modifications that are triggered, constrained, selected, evaluated, certified, and potentially retained as future structure.**

A shorter form is:

> **Intelligence as controlled structural unfolding.**

This should not be interpreted as a claim that every intelligent operation is literally graph expansion or symbolic transformation.

Structure may be:

```text
Neural
Graphical
Symbolic
Latent
Metric
Topological
Temporal
Physical
Hybrid
```

Unfolding may likewise be:

```text
Activation
Routing
Generation
Selection
Movement
Reconfiguration
Mutation
Suppression
Planning
Execution
Growth
```

GSUI is therefore a **structural abstraction**, not a commitment to one representation technology.

---

# 4. The Canonical GSUI Pattern

A general GSUI process may be represented as:

```text
CORE STRUCTURE
      │
      ▼
Context / Trigger
      │
      ▼
UNFOLDING SPACE
      │
      ▼
Candidate Deltas
      │
      ▼
Constraints
      │
      ▼
Policies
      │
      ▼
Evaluation
      │
      ▼
Selected Delta
      │
      ▼
Invariant / Certification
      │
      ▼
Applied Unfolding
      │
      ▼
Behavior / Generation / Action
      │
      ▼
Feedback
      │
      ▼
Structural Growth
      │
      ▼
UPDATED CORE STRUCTURE
```

Not every system contains every stage explicitly.

Some stages may be fused.

Some may be learned.

Some may be implicit in architecture.

Some may not yet exist.

The pattern is intended as an analytical map.

---

# 5. The General Structural Form

The compact form is:

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

subject to admissibility conditions such as:

$$
\Delta_t
\in
\mathcal{D}_{allowed}(S_t,C_t,P_t,I_t)
$$

A candidate set may be:

$$
\mathcal{D}_t =
\{
\Delta_1,\Delta_2,\ldots,\Delta_n
\}
$$

with selection:

$$
\Delta^* =
Select(
\mathcal{D}_t
\mid
S_t,C_t,P_t,I_t
)
$$

and subsequent transformation:

$$
S_{t+1} =
U(S_t,\Delta^*)
$$

The formulation is deliberately permissive.

The objective is to support comparison across domains without pretending that implementation details are identical.

---

# 6. What Is General About GSUI?

The word **General** requires care.

GSUI does not claim:

```text
ANN = Tree = CCC = CallingGraph
```

Nor:

```text
Reasoning = Planning = Navigation
```

Nor:

```text
All intelligence = one unfolding algorithm
```

The generality lies elsewhere.

GSUI proposes that many systems may share a common **structural relationship**:

```text
Persistent Structure
       +
Runtime Conditions
       ↓
Restricted Possibility Space
       ↓
Selected Structural Transition
       ↓
Result
```

Thus:

> **Generality refers to recurring structural form, not algorithmic identity.**

This distinction is fundamental.

---

# 7. LLMs Through the GSUI Lens

A large language model contains a highly compressed learned structure.

Training performs a large-scale Folding process:

```text
Data
  ↓
Training
  ↓
Parameterized Structure
```

At runtime:

```text
Model Structure
      +
Prompt / Context
      ↓
Activation / Sampling
      ↓
Runtime Trajectory
      ↓
Generated Continuation
```

A simplified GSUI mapping is:

| GSUI Element   | LLM Interpretation                                           |
| -------------- | ------------------------------------------------------------ |
| Core Structure | learned model structure                                      |
| Context        | prompt / conversation / retrieved context                    |
| Trigger        | inference request                                            |
| Delta          | next token / latent/runtime continuation                     |
| Operator       | learned neural computation + decoding                        |
| Policy         | decoding / runtime control / higher-level policy             |
| Evaluation     | implicit probability / external evaluator / verifier         |
| Result         | generated trajectory                                         |
| Feedback       | user/environment/evaluator response                          |
| Growth         | memory, fine-tuning, structural update, or external learning |

LLMs therefore provide a major example of runtime unfolding from heavily folded structure.

---

# 8. CallingGraph AI Coding Through the GSUI Lens

CallingGraph-based AI coding provides a more explicit structural instance.

Suppose:

$$
CG_t
$$

is the existing software CallingGraph.

A new task introduces candidate changes:

$$
\Delta CG
$$

The process becomes:

```text
Existing CG
     │
     ▼
Coding Task
     │
     ▼
CG Unfolding
     │
     ▼
Candidate ΔCG
     │
     ▼
Planning
     │
     ▼
Code Generation
     │
     ▼
Structural Certification
     │
     ▼
Updated CG
```

A GSUI mapping is:

| GSUI Element   | CallingGraph AI Coding                    |
| -------------- | ----------------------------------------- |
| Core Structure | current CallingGraph                      |
| Context        | repository + coding task                  |
| Trigger        | requested change / detected gap           |
| Delta          | ΔCG                                       |
| Operator       | graph modification / planning             |
| Constraint     | architecture / interface / security rules |
| Policy         | coding / structural policy                |
| Evaluation     | tests / structural comparison             |
| Invariant      | required call and architecture properties |
| Certification  | code-to-CG verification                   |
| Growth         | accepted CG update                        |

This example is important because the Delta can be made explicit and externally auditable.

---

# 9. Trees Through the GSUI Lens

Trees provide another useful family.

A tree may unfold through:

```text
Branch
Traverse
Expand
Prune
Merge
Replace
```

A basic form is:

```text
Current Tree
     +
Condition
     ↓
Branch Selection / Modification
     ↓
New Runtime Path or New Tree
```

GSUI interpretation:

| Element    | Tree System                  |
| ---------- | ---------------------------- |
| Core       | current tree                 |
| Delta      | branch/path/topology change  |
| Trigger    | condition/query/state        |
| Operator   | branch/traverse/expand/prune |
| Policy     | routing rule                 |
| Evaluation | branch utility / consistency |
| Growth     | retained new branch          |

This reveals an important distinction:

> Tree intelligence may unfold either **within an existing structure** or **by changing that structure**.

The first is routing.

The second is structural growth.

---

# 10. CCC Through the GSUI Lens

CCC-type systems emphasize the relationship among condition, context, and control.

A simplified form is:

```text
Condition
   +
Context
   ↓
Structural Selection
   ↓
Controlled Behavior
```

From the GSUI perspective, CCC can function as an unfolding mechanism that restricts which transitions are appropriate under a given state.

A rough mapping is:

| GSUI Element | CCC Interpretation                          |
| ------------ | ------------------------------------------- |
| Core         | existing CCC structure                      |
| Context      | runtime context                             |
| Trigger      | condition satisfaction                      |
| Delta        | selected transition / structural activation |
| Operator     | condition-context mapping                   |
| Policy       | control rule                                |
| Result       | bounded behavior                            |

CCC is therefore not necessarily identical to GSUI.

Rather:

> **CCC may be one important family of constrained unfolding primitives.**

---

# 11. Artificial Neural Networks Through the GSUI Lens

ANNs provide perhaps the most important non-symbolic example.

A neural network contains learned distributed structure.

Runtime computation unfolds that structure through activation dynamics.

A simplified view is:

```text
Learned Parameters
       +
Input
       ↓
Distributed Activation
       ↓
State / Output
```

Possible GSUI correspondence:

| GSUI Element   | ANN Interpretation                              |
| -------------- | ----------------------------------------------- |
| Core Structure | learned parameters / topology                   |
| Context        | input + runtime state                           |
| Trigger        | input event                                     |
| Delta          | activation/state change                         |
| Operator       | neural propagation                              |
| Constraint     | architecture / learned boundaries               |
| Policy         | implicit learned mapping or explicit controller |
| Result         | output / action / state transition              |

ANNs are especially important because their unfolding can be:

* distributed;
* high-dimensional;
* machine-native;
* difficult to interpret directly.

This reinforces a core GSUI principle:

> **Structural unfolding need not be symbolic or human-readable.**

---

# 12. Generative AI Through the GSUI Lens

Generative AI is an obvious but incomplete instance of unfolding.

For generation:

```text
Core Model
    +
Condition
    ↓
Candidate Continuation
    ↓
Generated Artifact
```

The artifact may be:

```text
Text
Code
Image
Audio
Video
Design
Plan
Simulation
```

GSUI treats this as one subtype:

> **Representational unfolding.**

The broader paradigm includes changes that may produce no conventional “content” at all.

For example:

```text
Suppress a branch
Change trajectory
Select control
Rewire topology
Preserve current state
Reject unsafe Delta
```

Therefore:

$$
Generation \subset Unfolding
$$

as a conceptual relationship.

---

# 13. Autonomous Driving Through the GSUI Lens

Autonomous driving makes the embodied case especially clear.

A vehicle has:

```text
Body
Sensors
Actuators
Runtime State
Capabilities
Control Limits
Goal
```

Its operational process can be represented as:

```text
Vehicle + Runtime State
          │
          ▼
Perception
          │
          ▼
Self-Relative World Structure
          │
          ▼
Candidate Trajectories
          │
          ▼
Constraint / Policy
          │
          ▼
Selected ΔTrajectory
          │
          ▼
Vehicle Action
```

A GSUI mapping is:

| GSUI Element    | Autonomous Vehicle                           |
| --------------- | -------------------------------------------- |
| Core Structure  | vehicle + controller + runtime state         |
| Context         | road / traffic / environment                 |
| Trigger         | observed event / control cycle               |
| Delta           | steering / braking / trajectory modification |
| Unfolding Space | reachable trajectories                       |
| Constraint      | physics / safety / traffic rules             |
| Policy          | driving strategy                             |
| Evaluation      | safety / progress / comfort                  |
| Invariant       | stability / collision constraints            |
| Result          | physical motion                              |

The physical world makes one GSUI property explicit:

> **Unfolding possibilities depend on the Structural Self.**

---

# 14. Structural Self Changes the Unfolding Space

Consider two agents in the same world.

Let:

$$
Self_A \neq Self_B
$$

Then generally:

$$
\mathcal{U}(Self_A,World)
\neq
\mathcal{U}(Self_B,World)
$$

For example:

```text
Narrow corridor

Human:
walkable

Small robot:
reachable

Large vehicle:
unreachable

Drone:
possibly irrelevant
```

The objective world is unchanged.

But the operational unfolding space changes.

Therefore:

> **For embodied or action-oriented intelligence, unfolding is structurally self-relative.**

This gives Structural Self an engineering role.

It defines:

```text
Capability
Reachability
Constraint
Risk
Affordance
Possible Delta
```

---

# 15. World Models Through the GSUI Lens

A world model is often described as:

$$
Model(World)
$$

GSUI suggests that operational intelligence often requires:

$$
WM(World\mid Self,Context,Capability,Goal)
$$

The world model helps determine:

```text
What exists?

What may happen?

What matters to this system?

What can this system do?

What would happen under candidate Delta?
```

A world model therefore participates in constructing an unfolding space.

One useful abstraction is:

$$
WM(Self_t,World_t,\Delta_t)
\rightarrow
PredictedConsequences
$$

Thus:

> **A world model becomes operationally important when it helps a Structural Self evaluate candidate unfolding.**

This does not imply that all world representations must be self-specific.

Objective or reusable submodels may exist.

But action-oriented semantics frequently depend on the acting structure.

---

# 16. Perception Through the GSUI Lens

Perception also changes meaning under GSUI.

It need not mean:

> reconstruct a human-like sensory world.

Instead:

$$
World\ Signals
\rightarrow
Operational\ Structure
$$

where operational structure supports unfolding.

Machine perception may therefore include:

```text
Graph change
Latency field
RF spectrum
CallingGraph anomaly
Memory pressure
Industrial telemetry
Dependency topology
Market trajectory
Database contention
```

These may have no direct human sensory analogue.

Thus:

> **Machine-native perception is legitimate when it constructs reliable self-relevant structure for intelligent unfolding.**

This supports non-anthropomorphic intelligence without abandoning engineering validation.

---

# 17. Machine-Native Cognition

Machine-native cognition extends the same principle.

A machine may use internal representations that:

* are not linguistic;
* are not visual;
* are not intuitive to humans;
* are not directly explainable at every step.

GSUI does not require human-like internal cognition.

It does require us to ask:

```text
What consequential Delta is being proposed?

What structure will change?

What constraints apply?

What invariants must hold?

Can the transition be certified?
```

This leads to a crucial distinction:

$$
Internal\ Cognitive\ Freedom
\neq
External\ Action\ Freedom
$$

---

# 18. Human-Governable Consequences

Machine-native intelligence must not become a justification for uncontrolled consequential action.

The GSUI governance pattern is:

```text
Machine-Native Internal Unfolding
              │
              ▼
       Candidate Delta
              │
════════════════════════════════
      STRUCTURAL BOUNDARY
════════════════════════════════
              │
        Observability
              │
          Policy
              │
        Invariants
              │
       Certification
              │
              ▼
    Authorized Consequence
```

This supports a concise principle:

> **Machine-native cognition; human-governable consequences.**

For AI coding:

```text
Internal Reasoning
      ↓
Candidate ΔCG
      ↓
Coding Plan
      ↓
Generated Code
      ↓
CG / Invariant Certification
      ↓
Deployment Decision
```

This is not a rejection of AI autonomy.

It is an architecture for governing consequential unfolding.

---

# 19. Structural Observability vs Internal Interpretability

Future AI systems may make complete internal interpretability increasingly difficult.

GSUI therefore distinguishes three concepts.

### Internal Interpretability

Can humans understand the internal computational process?

### Structural Observability

Can humans or machines observe the consequential structural change being proposed?

### Action Certifiability

Can the proposed transition be checked against policies, invariants, tests, or other governance criteria?

These should not be conflated.

A system may have limited internal interpretability while maintaining high structural observability and strong action certification.

This suggests a practical governance strategy:

> **Do not require every internal computation to become human-like; require consequential structural transitions to become governable.**

---

# 20. Planning as Prospective Unfolding

Planning can be interpreted as unfolding before execution.

Suppose a system considers:

$$
\Delta_1,\Delta_2,\ldots,\Delta_n
$$

Then it may simulate:

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

without immediately applying those changes to the external world.

Planning therefore becomes:

> **Prospective structural unfolding.**

The system explores:

```text
If Δ1, then what?

If Δ2 follows, then what?

Which future structure becomes reachable?

Which invariant fails?

Which trajectory is preferred?
```

This creates a direct relationship among:

```text
Planning
World Modeling
Unfolding Space
Evaluation
Policy
```

---

# 21. Reasoning as Runtime Unfolding

Reasoning may also be viewed through this lens.

A reasoning system begins with:

```text
Existing Structure
+
Current Problem
```

and constructs intermediate states:

```text
State 0
  ↓
State 1
  ↓
State 2
  ↓
Candidate Conclusion
```

GSUI does not claim that every reasoning system must expose these states symbolically.

But reasoning can often be analyzed as:

> **temporarily unfolding structure into a problem-conditioned trajectory.**

This interpretation is particularly useful when reasoning changes future available reasoning structures, as in learning or continual structural growth.

---

# 22. Decision as Selection Within Unfolding Space

Decision can be described as:

$$
Select(
\mathcal{U}_{allowed}
)
$$

or more specifically:

$$
\Delta^*
=
Select(
\Delta_1,\ldots,\Delta_n
)
$$

under constraints and policy.

Decision therefore need not be treated as a completely separate primitive from unfolding.

It may instead be a particular phase:

```text
Unfolding Space
      ↓
Candidate Alternatives
      ↓
Evaluation
      ↓
Selection
```

However, GSUI should not prematurely conclude that all decision mechanisms reduce to one selection operator.

The purpose is structural unification, not forced reduction.

---

# 23. Control as Bounded Unfolding

Control naturally fits the GSUI framework.

A controller attempts to keep unfolding inside an acceptable region.

Let:

$$
\mathcal{U}_{safe}
\subseteq
\mathcal{U}_{possible}
$$

Then control attempts to select transitions within:

$$
\mathcal{U}_{safe}
$$

while satisfying goals.

Thus:

> **Control can be viewed as bounded unfolding under feedback.**

The feedback loop is:

```text
Current State
     ↓
Candidate Delta
     ↓
Action
     ↓
World Response
     ↓
Observation
     ↓
Corrective Delta
```

This makes control one of the clearest runtime examples of iterative structural unfolding.

---

# 24. Learning as Retained Unfolding

Many unfolding events are temporary.

Learning begins when selected changes alter future structure.

A useful GSUI distinction is:

```text
Temporary Unfolding
        ↓
Runtime Result
```

versus:

```text
Successful Unfolding
        ↓
Evaluation
        ↓
Retention
        ↓
Updated Core Structure
```

Thus:

> **Learning can be viewed as retained unfolding.**

This is not intended as a replacement for mathematical learning theory.

It is a structural description of what distinguishes temporary runtime behavior from persistent capability change.

---

# 25. Structural Growth

Structural Growth occurs when retained unfolding changes future possibility.

If:

$$
S_t
\rightarrow
S_{t+1}
$$

and:

$$
\mathcal{U}(S_t)
\neq
\mathcal{U}(S_{t+1})
$$

then learning has changed the system's future unfolding capacity.

Examples include:

```text
New CallingGraph branch
New policy rule
New memory path
New learned skill
New routing structure
New reusable representation
New invariant
New control pathway
```

Structural Growth therefore concerns more than storage.

It concerns:

> **change in future reachable intelligence.**

---

# 26. Evolution as Long-Horizon Structural Unfolding

The GSUI perspective may also be extended cautiously toward biological evolution.

Evolution changes persistent structures across generations.

Those changes alter future possible behavior.

In a broad structural sense:

```text
Existing Organism Structure
          ↓
Variation
          ↓
Selection
          ↓
Retention
          ↓
Changed Future Structure
```

This resembles:

```text
Core
→ Delta
→ Evaluation
→ Retention
→ New Core
```

However, biological evolution should not be reduced to an engineered GSUI controller.

There may be no centralized policy or explicit evaluation mechanism.

The value of the comparison lies in structural recurrence:

> persistent structures generate variation, environments filter consequences, and retained changes alter future possibility.

---

# 27. Unfolding Universality

The first major GSUI hypothesis can now be stated.

### Unfolding Universality Hypothesis

> **A broad class of intelligent behaviors can be represented, analyzed, or reconstructed as constrained unfolding from persistent structure.**

This hypothesis does not claim universality in the strongest possible metaphysical sense.

It is a research hypothesis.

Its value depends on whether it helps:

```text
Explain
Compare
Design
Control
Certify
Compress
Generalize
```

across multiple AI domains.

---

# 28. A Cross-Domain Comparison

The GSUI framework can be summarized across several domains:

| Domain                 | Core Structure               | Delta                      | Unfolding Mechanism     | Control / Evaluation        |
| ---------------------- | ---------------------------- | -------------------------- | ----------------------- | --------------------------- |
| LLM                    | learned model                | token/runtime continuation | neural inference        | decoding, evaluator, policy |
| CallingGraph AI Coding | current CG                   | ΔCG                        | graph planning + coding | CG certification            |
| Tree                   | topology                     | branch/path delta          | routing / expansion     | branch policy               |
| CCC                    | condition-context structure  | controlled transition      | CCC mapping             | control rules               |
| ANN                    | parameters + state           | activation/state delta     | neural propagation      | learned dynamics/controller |
| Generative AI          | model + latent/runtime state | artifact/state delta       | generation              | sampler/evaluator           |
| Autonomous Driving     | vehicle + runtime state      | trajectory/control delta   | closed-loop control     | safety/policy               |
| Planning               | current modeled state        | simulated action delta     | prospective rollout     | evaluation                  |
| World Model            | world/self representation    | predicted transition       | simulation              | consequence comparison      |
| Continual Learning     | learned structure            | retained capability delta  | update/growth           | feedback/evaluation         |

The table shows common structural coordinates.

It does not imply computational equivalence.

---

# 29. Structural Form vs Algorithmic Equivalence

This distinction must remain explicit.

Two systems can share:

```text
Core
→ Delta
→ Selection
→ Result
```

while differing completely in:

```text
Representation
Mathematics
Learning mechanism
Runtime complexity
Physical substrate
Optimization method
Interpretability
Causality
Temporal scale
```

Therefore GSUI claims:

> **Structural comparability**

not:

> **algorithmic identity**.

This methodological discipline is essential if GSUI is to remain useful rather than becoming an overly broad metaphor.

---

# 30. When Is Something Not Useful to Call Unfolding?

A general paradigm requires boundaries.

If every state transition is called unfolding, the term becomes meaningless.

GSUI therefore requires more than arbitrary change.

A useful unfolding analysis generally includes several of the following:

```text
Persistent reference structure
Structured possibility space
Context conditioning
Candidate variation
Constraint
Selection
Continuity
Feedback
Future structural consequence
```

A random bit flip alone is not automatically intelligent unfolding.

A passive physical transformation need not be called GSUI.

A system becomes a stronger GSUI candidate when structure actively constrains and organizes possible transitions in relation to runtime conditions.

Thus:

> **Not every change is intelligent unfolding.**

---

# 31. Unfolding Space as a Central Research Object

One of GSUI's most important concepts is the Unfolding Space:

$$
\mathcal{U}(S,C)
$$

It represents the set or structured family of transitions available from a current structure under context.

We may distinguish:

$$
\mathcal{U}_{possible}
$$

$$
\mathcal{U}_{reachable}
$$

$$
\mathcal{U}_{allowed}
$$

$$
\mathcal{U}_{preferred}
$$

$$
\mathcal{U}_{selected}
$$

This creates a natural place for:

```text
Metric
Policy
Safety
Search
Sampling
Constraints
Evaluation
Triggering
Certification
```

GSUI therefore shifts attention from only modeling the current structure toward modeling:

> **the space of structurally reachable futures.**

---

# 32. Intelligence Is Not Maximum Unfolding Freedom

A common but misleading intuition is:

> greater intelligence = more possible behavior.

GSUI suggests a more nuanced view.

A useful intelligent system often becomes stronger by reducing irrelevant or unsafe possibilities.

For example:

```text
Novice system:
many poorly structured candidates

Experienced system:
few high-value candidates
```

Learning may:

```text
Expand useful space
Contract unsafe space
Collapse repeated search
Create direct routes
Strengthen invariants
```

Therefore:

> **Intelligence is not maximum unfolding freedom. It is effective organization of unfolding possibility.**

This gives Policy and Control Plane central rather than secondary roles.

---

# 33. Scaling Revisited

The success of ANN and LLM scaling can be interpreted through GSUI.

Larger folded structures may support:

```text
More representations
More latent relations
More candidate trajectories
More context-sensitive reconstruction
More reusable computational patterns
```

This can enlarge potential unfolding capacity.

A useful summary is:

> **Scaling enlarges unfolding potential.**

But capacity alone does not determine reliable intelligence.

Advanced systems also require:

```text
Triggering
Routing
Control
Evaluation
Certification
Feedback
Growth
```

Therefore:

> **Scaling enlarges unfolding potential; structural intelligence governs unfolding.**

GSUI treats these as complementary research directions.

---

# 34. Primitive Compression

The second major GSUI hypothesis concerns reduction rather than expansion.

Humans divide intelligence into many conceptual categories.

Evolution and machine computation may not require those same categories internally.

It may be possible to reconstruct many intelligent functions from a smaller set of operators.

Candidate families include:

```text
OBSERVE
COMPARE
METRIC
TRIGGER
ACTIVATE
INHIBIT
BRANCH
MERGE
SELECT
MOVE
CONNECT
MEMORIZE
RECALL
EVALUATE
CERTIFY
PRESERVE
PROMOTE
```

This motivates:

### Unfolding Primitive Compression Hypothesis

> **Many human-defined intelligence categories may eventually be expressible through compositions of a relatively small family of structural unfolding primitives.**

This remains an open research program.

---

# 35. GSUI and the Structural Self

The third major GSUI hypothesis concerns the reference frame of unfolding.

A Delta requires:

```text
Change relative to something.
```

A world model for action requires:

```text
World relative to an acting structure.
```

A capability requires:

```text
Capability of some structure.
```

An invariant requires:

```text
Continuity of some structure.
```

This motivates Structural Self.

A working definition is:

> **Structural Self is the persistent structural reference frame relative to which unfolding, capability, modification, continuity, and operational world meaning are defined.**

This does not imply consciousness.

It provides a runtime structural reference.

---

# 36. Three Levels of Self

A preliminary distinction is:

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

Persistent structure against which Delta is defined.

### Operational Self

The acting structure including relevant capabilities, boundaries, state, and control conditions.

### Cognitive Self

Internal representation of oneself as an object of cognition.

### Narrative Self

Human-level identity, biography, subjective interpretation, and social meaning.

The lower levels need not imply the higher ones.

This protects the Structural Self concept from unnecessary anthropomorphism.

---

# 37. Perception, World, and Self

GSUI naturally links three components:

$$
Self
\leftrightarrow
Perception
\leftrightarrow
WorldModel
$$

The Structural Self determines what is operationally relevant.

Perception constructs usable structure.

The World Model predicts or organizes possible consequences.

Together they help determine:

$$
\mathcal{U}(Self,World,Context)
$$

This produces the chain:

```text
WORLD
  ↓
Signals
  ↓
Structural Perception
  ↓
Self-Relative World Structure
  ↓
Unfolding Space
  ↓
Candidate Delta
  ↓
Action
```

This is a possible machine-native alternative to anthropomorphic perception-first models.

---

# 38. The GSUI Control Plane

GSUI requires more than candidate production.

A general Control Plane may contain:

```text
Trigger Management
Constraint Management
Policy
Candidate Evaluation
Invariant Checking
Certification
Authorization
Feedback Handling
Growth Promotion
```

Conceptually:

```text
               UNFOLDING SPACE
                      │
           ┌──────────┼──────────┐
           ▼          ▼          ▼
          Δ1         Δ2         Δ3
           │          │          │
           └──────────┼──────────┘
                      ▼
              ┌──────────────┐
              │ CONTROL PLANE│
              ├──────────────┤
              │ Constraints  │
              │ Policy       │
              │ Evaluation   │
              │ Invariants   │
              │ Certification│
              └──────┬───────┘
                     ▼
                 Selected Δ
```

The Control Plane is therefore one of the principal GSUI engineering directions.

---

# 39. Structural Certification

As AI becomes more autonomous, certification may become more important than full internal interpretability.

The critical question is not always:

> Why did every internal neuron activate?

It may instead be:

```text
What structural change is proposed?

Is that change authorized?

Does it preserve required invariants?

Does its implementation match the intended Delta?

Can it be rolled back?

What future unfolding does it enable?
```

For AI coding, CallingGraph certification is one concrete instance.

For other domains, equivalent certification structures may differ.

This suggests a wider GSUI research problem:

> **What structural representation should be exposed at the boundary between machine-native cognition and consequential action?**

---

# 40. Feedback Closes the GSUI Loop

Unfolding without feedback is incomplete for adaptive intelligence.

A general loop is:

```text
Structure
   ↓
Unfolding
   ↓
Action
   ↓
World
   ↓
Observation
   ↓
Evaluation
   ↓
Feedback
   ↓
Structural Update
```

Feedback may cause:

```text
Rollback
Reweighting
New memory
New policy
New branch
New invariant
New route
New skill
```

Thus GSUI connects runtime intelligence with continual structural development.

---

# 41. Folding and Unfolding Form a Larger Cycle

The broader cycle is:

```text
WORLD
  ↓
Observation
  ↓
FOLDING
  ↓
CORE STRUCTURE
  ↓
UNFOLDING
  ↓
ACTION / GENERATION
  ↓
WORLD
  ↓
FEEDBACK
  ↓
STRUCTURAL GROWTH
  ↓
REFOLDING
  ↓
UPDATED CORE STRUCTURE
```

This can be summarized as:

$$
World
\rightarrow
Structure
\rightarrow
World
$$

through alternating processes of Folding and Unfolding.

GSUI focuses primarily on the second half while maintaining the full cycle.

---

# 42. Three Central GSUI Hypotheses

The foundational GSUI program can now be summarized through three hypotheses.

## 42.1 Unfolding Universality

> A broad class of intelligent behaviors may share a useful structural description as constrained unfolding from persistent structure.

## 42.2 Primitive Compression

> Many human-defined intelligence categories may eventually compress into a smaller family of general unfolding primitives.

## 42.3 Structural Self

> A persistent structural reference frame may provide an operational basis for Delta, continuity, perception, world-model interpretation, capability, and action.

These hypotheses are related but separable.

Each can succeed or fail independently.

---

# 43. Initial GSUI Claims

The current framework makes several stronger claims.

### Claim 1

Structure formation is only one half of the intelligence problem.

### Claim 2

Runtime intelligence can often be studied as unfolding from persistent structure.

### Claim 3

`<Core Structure> +/- <Delta Modification>` provides a useful minimal comparative form.

### Claim 4

Generation is one form of unfolding, not the definition of unfolding.

### Claim 5

Search, planning, decision, and control can often be interpreted as phases or forms of structured unfolding, while remaining algorithmically distinct.

### Claim 6

Unfolding spaces are constrained by structure, context, capability, policy, and invariants.

### Claim 7

Machine-native perception and cognition need not imitate human perception and cognition.

### Claim 8

Machine-native cognition does not remove the need for human governance of consequential action.

### Claim 9

Structural certification may provide an important bridge between opaque internal intelligence and governable external consequences.

### Claim 10

Structural Growth changes future unfolding capacity.

---

# 44. What GSUI Does Not Claim

GSUI should maintain explicit theoretical boundaries.

It does not claim:

```text
All intelligence is identical.

All intelligence is symbolic.

All structures are graphs.

All Deltas are human-readable.

All world models must encode an explicit self.

Structural Self means consciousness.

Every AI action must be manually approved.

Internal interpretability is unnecessary.

Every state transition is intelligent unfolding.

GSUI is already a complete theory of intelligence.
```

The framework should be judged by whether it produces useful research questions, algorithms, explanations, control mechanisms, and cross-domain comparisons.

---

# 45. A GSUI Research Test

When examining a new system, one practical test is to ask:

```text
1. What persists?

2. What can change?

3. What triggers the change?

4. What determines the candidate space?

5. What constrains that space?

6. What selects among candidates?

7. What must remain invariant?

8. What consequence crosses into the world?

9. What feedback returns?

10. What becomes part of future structure?
```

If these questions reveal a coherent structural process, GSUI may provide a useful analytical lens.

If they do not, forcing the system into GSUI may add little value.

---

# 46. Toward a General Research Program

GSUI opens several major research areas:

```text
Unfolding Space

Unfolding Operators

Structural Delta Representation

Triggering

Control Plane

Policy

Evaluation

Invariant Preservation

Structural Certification

Structural Self

Self-Relative World Models

Machine-Native Perception

Machine-Native Cognition

Feedback

Structural Growth

Primitive Compression

Unfolding Algebra
```

These should not all be solved inside one theory paper.

GSUI is better understood as a foundational research program.

---

# 47. Canonical GSUI Grand Map

```text
                           WORLD
                             │
                             ▼
                        Observation
                             │
                             ▼
                     ┌──────────────┐
                     │   FOLDING    │
                     └──────┬───────┘
                            ▼
                  ┌───────────────────┐
                  │  CORE STRUCTURE   │
                  │   + INVARIANTS    │
                  └─────────┬─────────┘
                            │
                 Context / Trigger / Goal
                            │
                            ▼
                  ┌───────────────────┐
                  │ UNFOLDING SPACE   │
                  └─────────┬─────────┘
                            │
                 ┌──────────┼──────────┐
                 ▼          ▼          ▼
                Δ1         Δ2         Δ3
                 │          │          │
                 └──────────┼──────────┘
                            ▼
                  ┌───────────────────┐
                  │   CONTROL PLANE   │
                  ├───────────────────┤
                  │ Constraint        │
                  │ Policy            │
                  │ Evaluation        │
                  │ Invariant         │
                  │ Certification     │
                  └─────────┬─────────┘
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
                    Structural Growth
                            │
                            ▼
                      Refolding
                            │
                            └──────────────►
                         UPDATED CORE
```

Across the cycle:

```text
        STRUCTURAL SELF
              │
              ├── defines continuity
              ├── conditions capability
              ├── shapes perception
              ├── shapes world-model meaning
              └── constrains unfolding space
```

---

# 48. Canonical GSUI Form

### Minimal Form

```text
<Core Structure> +/- <Delta Modification>
```

### Runtime Form

$$
S_{t+1}
=
U(
S_t,
\Delta_t,
C_t,
T_t,
P_t,
I_t
)
$$

### Controlled Form

```text
Core Structure
      ↓
Unfolding Space
      ↓
Candidate Delta
      ↓
Constraint
      ↓
Policy
      ↓
Evaluation
      ↓
Certification
      ↓
Selected Unfolding
      ↓
Consequence
```

### Learning Form

```text
Unfolding
   ↓
Consequence
   ↓
Feedback
   ↓
Retention
   ↓
Structural Growth
   ↓
Changed Future Unfolding Space
```

---

# 49. Conclusion

General Structure Unfolding Intelligence begins with a simple shift in perspective.

Instead of asking only:

> What task does this AI perform?

we also ask:

> **What persistent structure is being unfolded?**

Instead of asking only:

> What output was generated?

we ask:

> **What Delta occurred relative to what Core?**

Instead of asking only:

> How large is the model?

we ask:

> **What unfolding space does its structure support?**

Instead of asking only:

> Can the AI think like a human?

we ask:

> **What machine-native structures can support reliable intelligent unfolding?**

And instead of assuming that machine-native cognition implies unrestricted autonomy, we ask:

> **How can consequential structural unfolding remain observable, constrained, and certifiable?**

GSUI therefore proposes a general research direction:

```text
Folding
   ↓
Structure
   ↓
Unfolding
   ↓
Delta
   ↓
Control
   ↓
Consequence
   ↓
Feedback
   ↓
Growth
```

Its central proposition is:

> **A broad class of intelligent systems may be understood through the controlled unfolding of persistent structure.**

Its methodological discipline is equally important:

> **Shared structural form does not imply shared algorithm.**

Its engineering objective is:

> **Make unfolding spaces, consequential Deltas, control boundaries, invariants, and structural growth explicit enough to study and govern.**

And its deeper research question is:

> **How much of what humans call perception, reasoning, planning, generation, decision, control, learning, and intelligence can ultimately be reconstructed from a smaller structural language of unfolding?**

That question defines the larger GSUI research program.

---

## Canonical Summary

```text
STRUCTURE
   │
   ▼
UNFOLDING SPACE
   │
   ▼
CANDIDATE DELTA
   │
   ▼
CONTROL
   │
   ▼
SELECTED DELTA
   │
   ▼
CERTIFIED CONSEQUENCE
   │
   ▼
FEEDBACK
   │
   ▼
STRUCTURAL GROWTH
   │
   ▼
NEW STRUCTURE
```

### Core Principle

> **Intelligence is not merely the possession of structure.
> Intelligence appears when structure can unfold meaningfully under conditions, constraints, evaluation, and feedback.**

### Governance Principle

> **Machine-native cognition; human-governable consequences.**

### Research Principle

> **Generalize structural form without falsely collapsing algorithmic differences.**

---

**GSUI-003**
**General Structure Unfolding Intelligence**
**Foundational Series**

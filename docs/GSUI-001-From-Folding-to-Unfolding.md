# GSUI-001 — From Folding to Unfolding

## Structure as the Bridge Between Learning and Intelligence

**General Structure Unfolding Intelligence (GSUI)**
**Foundational Paper 001**

---

## Abstract

Modern artificial intelligence has devoted enormous attention to **learning, compression, representation, and model formation**.

Observations are collected as data.
Data are compressed into parameters, graphs, trees, rules, latent representations, memories, and other persistent structures.

This direction may be summarized as:

```text
World
  ↓
Observation
  ↓
Data
  ↓
Folding / Compression
  ↓
Structure
```

Yet the formation of structure is only half of the intelligence cycle.

Once a structure exists, another question immediately follows:

> **How does a structure unfold into reasoning, prediction, planning, generation, decision, control, and action?**

This paper proposes that this second direction deserves to be studied as a general problem in its own right.

We call it **Structure Unfolding**.

The central transition is:

```text
Structure
  ↓
Context / Trigger
  ↓
Unfolding
  ↓
Behavior / Generation / Action
```

LLM inference provides one important example.
CallingGraph-based AI coding provides another.

But the concept is potentially much broader.

Trees, CCC structures, neural networks, planning systems, autonomous vehicles, generative systems, software structures, and biological control systems may all exhibit different forms of **constrained structural unfolding**.

The purpose of this paper is not to claim that all intelligence is reducible to one algorithm.

Instead, it introduces a more modest but potentially powerful hypothesis:

> **A broad class of intelligent processes can be represented, analyzed, or reconstructed as the unfolding of existing structure under context, constraints, and structural modification.**

This perspective leads naturally toward **General Structure Unfolding Intelligence (GSUI)**.

It also raises deeper questions concerning machine-native perception, unfolding spaces, invariants, structural growth, control boundaries, and the **Structural Self** relative to which change and continuity are defined.

---

# 1. The Missing Half of the Intelligence Cycle

A large part of modern AI can be understood as a process of converting observations into persistent computational structure.

Examples include:

* neural-network training;
* representation learning;
* language-model pretraining;
* graph extraction;
* tree construction;
* rule induction;
* memory formation;
* structural abstraction;
* knowledge organization.

In a highly generalized form:

```text
Observation
    ↓
Data
    ↓
Compression
    ↓
Folding
    ↓
Structure
```

The resulting structure may take many forms:

```text
ANN Parameters
LLM Parameters
Latent Representations
Calling Graphs
Decision Trees
CCC Structures
Policy Trees
Knowledge Graphs
Memory Structures
Runtime Invariants
```

These structures differ substantially in implementation.

Nevertheless, they share an important property:

> **Past observations, computations, relationships, or experiences have been folded into a reusable structure.**

The success of modern AI demonstrates the enormous value of this process.

But a structure that merely exists is not yet behavior.

A trained LLM must generate.

A CallingGraph must support planning or certification.

A policy structure must select actions.

A neural network must activate.

A vehicle model must participate in control.

A biological structure must produce behavior.

Therefore, after Folding comes another fundamental process:

> **Unfolding.**

---

# 2. Folding and Unfolding

The two directions can be placed together:

```text
WORLD
  │
  ▼
Observation
  │
  ▼
Data
  │
  ▼
Folding / Compression
  │
  ▼
STRUCTURE
  │
  ▼
Unfolding
  │
  ▼
Prediction / Reasoning / Planning
Generation / Decision / Action
  │
  ▼
WORLD
```

This suggests a broader intelligence cycle:

```text
World
  ↓
Observation
  ↓
Folding
  ↓
Structure
  ↓
Unfolding
  ↓
Action / Generation
  ↓
World
  ↓
Feedback
  ↓
Structural Update
```

Folding and Unfolding should not be treated as exact mathematical inverses.

A learned model cannot necessarily reconstruct its training data.

A CallingGraph does not uniquely determine source code.

A compressed biological control structure does not uniquely determine one future behavior.

Instead, they represent two complementary structural directions:

### Folding

```text
many observations / events / relations
                    ↓
            persistent structure
```

### Unfolding

```text
persistent structure
        +
current conditions
        ↓
candidate behavior / structure / action
```

Folding answers:

> **What structure can be retained?**

Unfolding answers:

> **What can this structure become or do now?**

---

# 3. From Stored Structure to Runtime Intelligence

This distinction exposes an important difference between **structural capacity** and **runtime intelligence**.

A model may contain enormous stored capability.

But runtime intelligence requires some portion of that capability to become operational.

In general:

```text
Stored Structure
      │
      ├── Context
      ├── Condition
      ├── Trigger
      ├── Goal
      ├── Policy
      └── Constraints
             │
             ▼
          Unfolding
             │
             ▼
     Runtime Intelligence
```

This suggests that intelligence should not be studied only through:

* model size;
* parameter count;
* training data;
* representation quality;
* compression efficiency.

It should also be studied through:

* what can unfold;
* what triggers unfolding;
* what modifications are permitted;
* how candidates are evaluated;
* what invariants must remain;
* what consequences are allowed;
* what feedback becomes structural growth.

This is the starting point of **Structure Unfolding Intelligence**.

---

# 4. LLMs as a First Unfolding Example

Large language models provide a particularly important example.

Training folds enormous quantities of linguistic and structural regularities into model parameters.

In simplified form:

```text
Text / Code / Knowledge
          ↓
       Training
          ↓
        Folding
          ↓
     LLM Structure
```

Inference reverses the direction of attention:

```text
LLM Structure
      +
Prompt / Context
      +
Runtime Conditions
      ↓
Triggering
      ↓
Unfolding
      ↓
Token / Latent Trajectory
      ↓
Generated Result
```

The model does not simply retrieve a stored answer.

Its existing structure participates in constructing a runtime trajectory conditioned by the current context.

Reasoning can therefore be examined as a special unfolding process:

```text
Compressed Model Structure
           ↓
Context-Conditioned Activation
           ↓
Runtime Reconstruction
           ↓
Reasoning Trajectory
```

This does not imply that all LLM reasoning is explicitly represented as a human-readable structure.

The important point is more general:

> **A previously folded structure is activated and transformed into a context-specific runtime process.**

This provides one path from Folding to Unfolding.

---

# 5. CallingGraph Unfolding as a Second Example

CallingGraph-based AI coding provides a structurally clearer example.

Existing software contains an existing CallingGraph:

```text
Existing Code
     ↓
Structural Extraction
     ↓
CallingGraph
```

When AI modifies the software, the process can be viewed from the structural side:

```text
Existing CallingGraph
          │
          ▼
     Task / Trigger
          │
          ▼
      CG Unfolding
          │
          ▼
     Candidate ΔCG
          │
          ▼
     Coding Planning
          │
          ▼
       AI Coding
          │
          ▼
 CG / Structural Certification
          │
      ┌───┴───┐
    Reject   Accept
              │
              ▼
       Updated CallingGraph
```

The central object is no longer merely generated code.

It becomes:

```text
Existing Structure
       +
Structural Modification
       ↓
Candidate New Structure
```

In compact form:

```text
<Core Structure> +/- <Delta Modification>
```

or:

$$
S_{t+1} = S_t \pm \Delta_t
$$

The generated code becomes an implementation of the proposed structural change.

This perspective provides an important conceptual transition:

> **AI coding can be treated as controlled software-structure unfolding rather than unconstrained code generation.**

---

# 6. From Specific Unfolding to General Unfolding

LLM inference and CallingGraph-based AI coding appear very different.

One operates largely through learned distributed representations.

The other can operate through explicit software topology.

Yet both suggest the same abstract pattern:

```text
Existing Structure
        +
Current Context
        +
Possible Modification
        ↓
Unfolding
        ↓
Candidate Result
```

This motivates a broader research question:

> **How many apparently different intelligent processes can be represented as constrained unfolding of existing structure?**

Potential examples include:

```text
LLM inference
Generative AI
AI coding
Tree traversal and growth
CCC-conditioned behavior
ANN activation
Planning
Navigation
Autonomous driving
Structural mutation
Structural sampling
Decision systems
World-model rollout
Continual learning
Biological behavior
```

These systems should not be assumed to implement the same algorithm.

Their structures, operators, state spaces, and physical substrates may differ radically.

The proposed commonality is instead a **structural form**:

> **Existing structure constrains and enables possible next structures, states, behaviors, or actions.**

This is the conceptual starting point of **General Structure Unfolding**.

---

# 7. Generation Is a Special Case of Unfolding

The term *generation* usually emphasizes the production of observable output.

For example:

```text
Prompt
  ↓
Model
  ↓
Text
```

or:

```text
Description
  ↓
Model
  ↓
Image
```

Structure Unfolding emphasizes something more general:

```text
Core Structure
      +
Context
      +
Allowed Modification
      ↓
Unfolding
      ↓
Candidate Structure / State / Behavior
```

An unfolding operation may involve:

```text
Add
Remove
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
Preserve
```

Therefore:

> **Generation is one form of unfolding, but unfolding is broader than generation.**

A system may unfold by selecting.

It may unfold by moving.

It may unfold by activating an existing branch.

It may unfold by suppressing an unsafe trajectory.

It may unfold by changing topology.

It may unfold by preserving most of a structure while modifying a small Delta.

This broader view becomes especially important for embodied intelligence, AI coding, control systems, and structural growth.

---

# 8. The Core Structure + Delta View

A minimal GSUI expression begins with:

$$
S_{t+1} = S_t \pm \Delta_t
$$

where:

* \(S_t\) is the current structure;
* \(\Delta_t\) is a candidate modification;
* \(S_{t+1}\) is the resulting structure or state.

A more useful operational form is:

$$
S_{t+1} = U(S_t,\Delta_t,C_t,P_t)
$$

where:

* \(U\) is an unfolding operator;
* \(C_t\) represents context and conditions;
* \(P_t\) represents policies and constraints.

This expression is deliberately general.

It does not assume that \(S\) must be:

* symbolic;
* neural;
* graphical;
* textual;
* physical;
* human-readable.

Nor does it assume that \(\Delta\) must be additive.

The purpose is to identify a common research object:

> **controlled modification of persistent structure under runtime conditions.**

---

# 9. Unfolding Requires an Unfolding Space

If a structure can change, then there is some set of possible changes available from its current state.

Let:

$$
\mathcal{U}(S_t,C_t)
$$

denote an **Unfolding Space** associated with structure \(S_t\) under context \(C_t\).

Not every possible unfolding should be treated equally.

We may distinguish:

$$
\mathcal{U}_{possible}
$$

from:

$$
\mathcal{U}_{allowed}
$$

from:

$$
\mathcal{U}_{preferred}
$$

and finally:

$$
\mathcal{U}_{selected}
$$

This immediately introduces several major AI research problems:

```text
Triggering
Search
Sampling
Policy
Constraint
Evaluation
Selection
Control
Certification
Feedback
Learning
Growth
```

The question is therefore not merely:

> What can the structure produce?

It is also:

> What should be allowed to unfold?

> What should be selected?

> What must remain invariant?

> What should become permanent structure?

---

# 10. Unfolding Is Broader Than Search

Search and unfolding are closely related, but they should not be identified.

Traditional search often assumes a sufficiently stable search space:

```text
Candidate Space
      ↓
Search
      ↓
Selected Candidate
```

Structural unfolding may change the space from which future candidates can arise.

If:

$$
S_t \rightarrow S_{t+1}
$$

then it may also be true that:

$$
\mathcal{U}(S_t) \neq \mathcal{U}(S_{t+1})
$$

The structure produced by one unfolding step may create:

* new branches;
* new operators;
* new reachable states;
* new representations;
* new action possibilities;
* new future structural modifications.

Therefore:

> **Unfolding may transform not only the current state, but the future possibility space itself.**

This is one of the bridges from inference to **Structural Growth**.

---

# 11. Feedback and Structural Growth

A temporary unfolding does not necessarily become permanent structure.

A system may generate thousands of candidates and retain none of them.

Learning begins when selected consequences affect future structure.

A more complete cycle is therefore:

```text
Core Structure
      ↓
Unfolding
      ↓
Candidate Δ
      ↓
Action / Generation
      ↓
Evaluation
      ↓
Feedback
      ↓
Accept / Reject / Modify
      ↓
Structural Growth
      ↓
Updated Core Structure
```

This suggests a useful distinction:

```text
Inference
    = temporary unfolding

Generation
    = representational unfolding

Planning
    = prospective unfolding

Action
    = world-coupled unfolding

Learning
    = retained unfolding

Structural Growth
    = unfolding that changes future unfolding capacity
```

This vocabulary is provisional.

Its purpose is not to replace established terminology prematurely.

Its purpose is to expose structural relationships among processes that are often studied separately.

---

# 12. Folding → Unfolding → Refolding

The intelligence cycle can now be expanded:

```text
WORLD
  │
  ▼
Observation
  │
  ▼
Folding
  │
  ▼
Core Structure
  │
  ▼
Unfolding
  │
  ▼
Candidate Change
  │
  ▼
Action / Generation
  │
  ▼
Feedback
  │
  ▼
Evaluation
  │
  ▼
Structural Growth
  │
  ▼
Refolding / Consolidation
  │
  └──────────────────────► Core Structure
```

This cycle is more general than a simple:

```text
Input → Model → Output
```

It treats intelligence as a continuing relationship between:

* structure formation;
* structure activation;
* structural modification;
* interaction with the world;
* evaluation;
* structural retention.

This may provide a useful bridge between learning theory, inference, control, generative AI, continual learning, and structural intelligence.

---

# 13. Machine-Native Perception

The unfolding perspective also changes how perception can be understood.

AI perception need not use human perception as its universal template.

Human perception reflects a particular biological history:

```text
Human Body
    ↓
Human Sensors
    ↓
Human Neural Structure
    ↓
Human Operational World
```

A machine may possess completely different sensing channels and structural needs.

For example, a machine may directly perceive:

```text
CallingGraph topology
Network latency fields
Database lock structures
RF spectra
Radar point clouds
API dependency graphs
Memory pressure
Industrial sensor manifolds
Distributed system failures
Market time-series structures
```

Many such structures have no direct human sensory equivalent.

Therefore machine perception need not first reconstruct a human-like visual, auditory, or phenomenal world.

A more general operational formulation is:

$$
Perception:
World\ Signals
\rightarrow
Self\text{-}Relative\ Operational\ Structure
$$

This suggests:

> **Perception is not fundamentally human-like sensing; it can be understood as the construction of structures that constrain and enable unfolding for a particular operational subject.**

This opens the possibility of **machine-native perception** and **machine-native cognition** without requiring an anthropomorphic model of intelligence.

---

# 14. The Structural Self

The previous section immediately raises another question:

> **Operational relative to whom or what?**

Any Delta implicitly requires a reference structure.

If:

$$
\Delta_t = S_{t+1} - S_t
$$

then \(S_t\) defines the structural reference relative to which change is measured.

This motivates the provisional concept of a **Structural Self**:

> **A Structural Self is the persistent structural reference frame relative to which unfolding, modification, preservation, and continuity are defined.**

This is not a claim about consciousness.

It is not a claim about subjective experience.

It is not intended as a replacement for philosophical theories of personal identity.

It is an operational concept.

Examples might include:

```text
Autonomous Vehicle
→ vehicle structure + runtime state + capabilities

Robot
→ embodiment + sensors + actuators + runtime state

AI Coding Agent
→ repository structure + active task + policy state

AI Agent
→ model + context + memory + runtime control state

Biological Organism
→ organism-maintaining structure
```

This produces an important relation:

```text
Structural Self
       ↕
Self-Relative World Model
       ↕
Unfolding Space
```

---

# 15. World Models Are Operationally Self-Relative

A world model is often described simply as a model of the world.

For action-oriented intelligence, this description may be incomplete.

Consider the same physical passage encountered by:

* a pedestrian;
* a narrow mobile robot;
* a large autonomous vehicle;
* a drone.

The objective environment may remain unchanged.

Yet:

```text
Reachability
Passability
Risk
Affordance
Useful Distance
Possible Action
```

all depend on the acting structure.

A more operational formulation is therefore:

$$
WM = WM(World \mid Self, Context, Capability, Goal)
$$

rather than merely:

$$
WM = Model(World)
$$

Changing the Structural Self may invalidate significant parts of the operational meaning of a previously learned world model.

This does not imply that all objective knowledge disappears.

It means that **self-conditioned semantics must be reconsidered**.

The same principle applies to the Unfolding Space:

$$
\mathcal{U}(Self_1,World)
\neq
\mathcal{U}(Self_2,World)
$$

even when the external world is unchanged.

Thus:

> **Unfolding Space is inherently self-relative whenever unfolding concerns an acting subject.**

---

# 16. Machine-Native Cognition Does Not Remove Governance

The recognition of machine-native perception and cognition must not become an argument for uncontrolled AI autonomy.

Two propositions must remain separate:

> **AI cognition need not imitate human cognition.**

and:

> **AI actions affecting human systems must remain governable.**

Machine-native internal representations may become increasingly difficult for humans to interpret directly.

That does not eliminate the need for structural observability, policy control, and certification at consequential action boundaries.

A useful distinction is:

```text
Internal Interpretability
        │
        │ may be limited
        ▼
Machine-Native Unfolding
        │
        ▼
Candidate Structural Change
        │
════════════════════════════════
       CONTROL BOUNDARY
════════════════════════════════
        │
        ▼
Structural Observability
        │
Policy / Invariant Checking
        │
Certification
        │
        ▼
External Consequence
```

This leads to an important governance principle:

> **Freedom of internal unfolding does not imply freedom of external action.**

For AI coding, this principle can be made concrete:

```text
Machine-Native Reasoning
        ↓
Candidate ΔStructure
        ↓
CallingGraph Unfolding
        ↓
Coding Plan
        ↓
Generated Code
        ↓
CallingGraph / Invariant Certification
        ↓
Accept / Reject
```

The objective need not be to understand every internal computation of a future advanced AI.

The more practical objective is:

> **Observe, constrain, and certify consequential structural unfolding before it crosses critical action boundaries.**

This is one reason structural representations such as CallingGraphs, runtime invariants, policies, and certification mechanisms remain important even as AI develops increasingly machine-native internal cognition.

---

# 17. Internal Freedom and External Certification

This relationship suggests a broader GSUI principle:

> **The greater the freedom of internal unfolding, the stronger the need for structural certification at consequential external boundaries.**

This principle avoids two opposite mistakes.

The first is **anthropomorphic limitation**:

```text
If humans cannot perceive or reason this way,
the machine should not either.
```

The second is **autonomy romanticism**:

```text
If the machine has its own cognition,
human structural control is obsolete.
```

Neither conclusion follows.

A more productive architecture is:

```text
Machine-Native Cognition
          │
          ▼
Rich Internal Unfolding
          │
          ▼
Candidate Consequence
          │
          ▼
Human-Governable Structural Interface
          │
          ▼
Policy / Invariant / Certification
          │
          ▼
Authorized External Action
```

In compact form:

> **Machine-native cognition; human-governable consequences.**

This relationship may become increasingly important as internal AI representations become more powerful and less directly interpretable.

---

# 18. Scaling Through the Folding–Unfolding Lens

The Folding–Unfolding framework also offers a possible interpretation of the success of neural scaling.

Large neural models demonstrate an empirical fact:

> **Richly folded structure can support extraordinarily rich runtime unfolding.**

Increasing model scale may increase:

* latent structural capacity;
* representational diversity;
* conditional reconstruction capacity;
* reachable generation trajectories;
* reusable internal patterns;
* potential unfolding space.

From this perspective, the historical success of ANN and LLM scaling is not surprising.

The intuition behind scaling may therefore contain an important truth:

> **More capable folded structures can enable richer unfolding.**

But this does not imply that Folding and scale are the entire intelligence problem.

Another major research direction concerns:

```text
Triggering
Unfolding Space
Delta Formation
Control
Policy
Evaluation
Certification
Feedback
Invariant Preservation
Structural Growth
```

A useful provisional summary is:

> **Scaling enlarges unfolding potential; structural intelligence governs unfolding.**

These are complementary rather than mutually exclusive research directions.

---

# 19. Toward Unfolding Primitives

Human knowledge divides intelligence into many categories:

```text
Perception
Recognition
Prediction
Reasoning
Planning
Decision
Navigation
Generation
Control
Learning
```

These categories are useful for human communication and engineering organization.

They need not correspond to the minimal computational primitives of intelligence.

Biological evolution did not need to define academic categories before constructing intelligent organisms.

Likewise, machine intelligence may eventually be describable through a much smaller set of reusable structural operations.

Possible candidates include:

```text
Metric
Condition
Context
Activation
Inhibition
Branch
Merge
Selection
Memory
Delta
Feedback
Invariant
```

Structures such as CCC, ANN, trees, graphs, and metric systems may implement or combine different subsets of such operations.

This motivates a second research direction complementary to expanding the taxonomy of unfolding:

> **Can apparently diverse intelligence categories be compressed into a small family of general unfolding primitives?**

This is a question for future research rather than a conclusion of the present paper.

---

# 20. A Provisional GSUI Grand Cycle

The ideas introduced above can be summarized as:

```text
                         WORLD
                           │
                           ▼
                      Observation
                           │
                           ▼
                    ┌─────────────┐
                    │   FOLDING   │
                    └──────┬──────┘
                           ▼
                 ┌─────────────────┐
                 │ CORE STRUCTURE  │
                 │  + INVARIANTS   │
                 └────────┬────────┘
                          │
               Context / Trigger / Goal
                          │
                          ▼
                 ┌─────────────────┐
                 │ UNFOLDING SPACE │
                 └────────┬────────┘
                          │
                ┌─────────┼─────────┐
                ▼         ▼         ▼
               Δ1        Δ2        Δ3
                │         │         │
                └─────────┼─────────┘
                          ▼
                 ┌─────────────────┐
                 │  CONTROL PLANE  │
                 │ Policy / Eval   │
                 └────────┬────────┘
                          ▼
                     Selected Δ
                          │
                          ▼
                     S' = S ± Δ
                          │
                          ▼
              Invariant / Certification
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
                 Refolding / Update
                          │
                          └──────────────►
                             CORE STRUCTURE
```

The persistent reference structure across this process may constitute an operational **Structural Self**.

---

# 21. From Structure Unfolding to Structure Unfolding Intelligence

Unfolding alone is not sufficient for intelligence.

A random mutation is an unfolding.

A random branch may be an unfolding.

An uncontrolled structural modification may be an unfolding.

Structure Unfolding becomes **Structure Unfolding Intelligence** when unfolding is coupled with mechanisms such as:

```text
Context
Triggering
Goal
Constraint
Policy
Evaluation
Selection
Invariant Preservation
Feedback
Certification
Learning
Growth
```

A provisional definition is therefore:

> **Structure Unfolding Intelligence is the capacity of a structured system to produce, select, evaluate, and incorporate context-conditioned structural variations while preserving relevant core invariants.**

The word **General** in General Structure Unfolding Intelligence refers not to one universal implementation, but to the search for structural principles that may recur across many different forms of intelligence.

---

# 22. What This Paper Does Not Claim

Because the scope of GSUI is potentially broad, several boundaries should be explicit.

This paper does **not** claim that:

1. all intelligence is one algorithm;
2. all intelligent systems contain explicit symbolic structures;
3. ANN, CCC, trees, CallingGraphs, and metric systems are computationally equivalent;
4. unfolding is identical to generation;
5. unfolding is identical to search;
6. Structural Self implies consciousness;
7. machine-native cognition removes the need for human governance;
8. every world model must explicitly encode a symbolic self;
9. Folding and Unfolding are exact inverses;
10. GSUI is already a complete theory of intelligence.

Instead, this paper proposes a research hypothesis:

> **A broad class of intelligent processes may share a useful structural description based on persistent structure, context-conditioned unfolding, Delta modification, control, invariants, feedback, and growth.**

The value of GSUI will depend on whether this description produces useful explanations, algorithms, abstractions, experiments, and control mechanisms.

---

# 23. Research Questions Opened by GSUI

The Folding–Unfolding perspective immediately opens a substantial research program.

### 23.1 Unfolding Representation

What forms of structure are most useful for representing unfolding?

### 23.2 Unfolding Operators

Can a small family of general operators cover large classes of intelligent behavior?

### 23.3 Unfolding Space

How should possible, allowed, preferred, and selected unfolding spaces be represented?

### 23.4 Triggering

What causes a dormant structure to become operational?

### 23.5 Control Plane

How should policies govern candidate structural modifications?

### 23.6 Evaluation

How should alternative unfolding trajectories be compared?

### 23.7 Invariants

What must remain unchanged while a structure unfolds?

### 23.8 Certification

How can consequential unfolding be certified before external action?

### 23.9 Feedback

How should world feedback alter future unfolding?

### 23.10 Structural Growth

When should successful unfolding become persistent structure?

### 23.11 Structural Self

What persistent structure defines the reference frame of change and continuity?

### 23.12 Self-Relative World Models

How should world representations change when the acting Structural Self changes?

### 23.13 Machine-Native Perception

What forms of perception become possible when machines are not constrained to human sensory paradigms?

### 23.14 Primitive Compression

Can reasoning, planning, prediction, navigation, generation, and control be reconstructed from a smaller set of unfolding primitives?

### 23.15 Human Governance

How can increasingly machine-native internal cognition remain connected to human-governable external consequences?

---

# 24. Initial Research Position

The initial GSUI research position can be summarized in six propositions.

### Proposition 1 — Structure Matters at Runtime

Intelligence should be studied not only through how structures are learned, but through how existing structures become runtime behavior.

### Proposition 2 — Core + Delta Is a Useful General Form

A broad class of intelligent processes may be represented as:

```text
<Core Structure> +/- <Delta Modification>
```

under context, constraints, and control.

### Proposition 3 — Generation Is One Form of Unfolding

Structural unfolding includes generation but is not limited to generation.

### Proposition 4 — Intelligent Unfolding Requires Governance

Triggering, policy, evaluation, feedback, invariants, and certification distinguish controlled intelligent unfolding from arbitrary structural change.

### Proposition 5 — Intelligence Categories May Be Compressible

Many human-defined intelligence categories may eventually be reconstructed from a smaller family of general unfolding primitives.

### Proposition 6 — Unfolding Requires a Reference Frame

For acting systems, structural change and operational world meaning are defined relative to a persistent reference structure — a candidate foundation for the concept of **Structural Self**.

---

# 25. Conclusion

Modern AI has demonstrated the power of Folding.

Massive observations can be compressed into structures capable of remarkable behavior.

But the existence of a powerful structure raises the next question:

> **How does structure become intelligence at runtime?**

General Structure Unfolding Intelligence begins from this question.

Its initial conceptual cycle is:

```text
Observation
    ↓
Folding
    ↓
Structure
    ↓
Unfolding
    ↓
Delta
    ↓
Action / Generation
    ↓
Feedback
    ↓
Growth
    ↓
Refolding
```

Within this cycle, several ideas become connected:

```text
LLM inference
CallingGraph unfolding
Generative AI
Planning
Control
Machine-native perception
World models
Structural invariants
Certification
Continual learning
Structural growth
Structural self
```

The purpose of GSUI is not to erase the differences among these systems.

It is to ask whether a deeper structural language can reveal relationships that task-specific classifications obscure.

The first hypothesis is simple:

> **Intelligence may be studied not only as computation over information, but as controlled unfolding of structure.**

The second is more ambitious:

> **Many apparently different forms of intelligence may eventually be understood through a relatively small family of structural unfolding primitives.**

And the third reaches beyond algorithm classification:

> **The structure that persists while unfolding occurs may provide an operational reference frame for perception, world models, action, continuity, and self.**

These hypotheses define a starting point.

They do not complete the theory.

They establish a research direction.

---

## Canonical Summary

```text
WORLD
  ↓
Observation
  ↓
FOLDING
  ↓
CORE STRUCTURE
  ↓
Context / Trigger
  ↓
UNFOLDING SPACE
  ↓
Candidate Δ
  ↓
Policy / Evaluation / Control
  ↓
Selected Unfolding
  ↓
Invariant / Certification
  ↓
Action / Generation
  ↓
WORLD
  ↓
Feedback
  ↓
Structural Growth
  ↓
Refolding
  ↓
UPDATED CORE STRUCTURE
```

### Core Expression

```text
<Core Structure> +/- <Delta Modification>
```

### Core Question

> **How does persistent structure unfold into intelligent behavior while remaining controllable, evaluable, and capable of growth?**

### GSUI Direction

> **From Folding to Structure.
> From Structure to Unfolding.
> From Unfolding to Feedback.
> From Feedback to Growth.**

---

**GSUI-001**
**General Structure Unfolding Intelligence**
**Foundational Series**

# GLOSSARY

## Canonical Terms for General Structure Unfolding Intelligence

**GSUI — General Structure Unfolding Intelligence**

---

## Purpose

This glossary defines the canonical terminology used in the foundational GSUI repository.

The goal is not to claim that every term is final.

It is to provide a stable vocabulary for:

```text
discussion,
formalization,
implementation,
comparison,
and future extension.
```

Several terms intentionally overlap with established AI, control, graph, learning, and systems terminology.

Where GSUI uses a term in a more specific way, that meaning is stated explicitly.

---

# A

## Action Certifiability

The degree to which a proposed consequential action or structural change can be checked against explicit requirements before execution.

Possible checks include:

```text
Policy
Invariant
Safety
Security
Tests
Authorization
Structural consistency
```

Action Certifiability is distinct from Internal Interpretability.

A system may be difficult to interpret internally while still supporting strong certification at consequential boundaries.

---

## Activate

An unfolding operator that causes an existing structure, branch, state, capability, or pathway to become operational.

Examples:

```text
Activate a tree branch.

Activate a policy route.

Activate an ANN pathway.

Activate a previously learned skill.
```

Activation changes runtime participation without necessarily modifying persistent topology.

---

## Affordance

A world condition that enables some possible unfolding for a particular Structural Self.

A GSUI-oriented expression is:

$$
Affordance \subseteq \mathcal{U}(Self,World)
$$

Affordance is therefore self-relative.

The same external structure may provide different affordances to different systems.

---

## Allowed Unfolding Space

The region of the Unfolding Space that satisfies current constraints, permissions, and mandatory policies.

$$
\mathcal{U}_{allowed}
\subseteq
\mathcal{U}_{reachable}
$$

Possible unfolding is broader than allowed unfolding.

---

## Anthropomorphic Perception

A perception model that uses human sensory organization or human perceptual categories as the primary template for machine perception.

GSUI does not reject anthropomorphic perception.

It rejects the assumption that it is the universal form of perception.

See also:

* Structural Perception
* Machine-Native Perception

---

## Authorization

The decision that a candidate action or Delta is permitted to cross into consequential execution.

Authorization is distinct from:

```text
Capability
Evaluation
Preference
Certification
```

A system may be capable of an action yet not authorized to perform it.

---

# B

## Boundary

A structural distinction separating one operational region from another.

Important GSUI boundary types include:

```text
Self / Non-Self Boundary

Allowed / Forbidden Boundary

Internal / Consequential Boundary

Capability / Permission Boundary

Deployment Boundary
```

Boundaries may be physical, computational, logical, policy-based, or organizational.

---

## Branch

An unfolding operator that creates or selects one of multiple structural paths.

Branching may be:

```text
runtime selection,
persistent topology growth,
policy routing,
or structural differentiation.
```

---

# C

## Candidate Delta

A proposed structural modification that has not yet been selected, certified, or applied.

A system may generate:

$$
\Delta_1,\Delta_2,\ldots,\Delta_n
$$

before choosing:

$$
\Delta^*
$$

Candidate Delta is therefore part of the Unfolding Space.

---

## Capability

What a system can physically, computationally, structurally, or operationally do.

GSUI distinguishes:

$$
Capability \neq Permission
$$

A system may possess capability without authorization.

Capability may depend on:

```text
Model
Tools
Interfaces
Embodiment
Runtime State
Resources
Credentials
```

---

## Capability Frontier

The boundary of what a system is currently capable of unfolding.

This may be broader than the Deployment Frontier.

$$
\mathcal{U}_{deployable}
\subseteq
\mathcal{U}_{capable}
$$

---

## Certification

A structured judgment about whether a candidate Delta or action satisfies requirements necessary for consequential execution.

A generic form is:

$$
Cert(S,\Delta,P,I)\rightarrow Decision
$$

Certification may produce:

```text
Accept
Reject
Modify
Escalate
Request Review
```

Certification is stronger than mere evaluation.

---

## CCC

A structural family centered on Condition, Context, and Control.

Within GSUI, CCC may be treated as one family of constrained unfolding mechanisms.

A simplified form is:

```text
Condition
+
Context
↓
Controlled Transition
```

GSUI does not claim that CCC is equivalent to ANN, Tree, CallingGraph, or GSUI itself.

---

## Change

Any transition from one state or structure to another.

Not every Change is necessarily GSUI-relevant Unfolding.

A useful GSUI unfolding analysis generally requires additional structure such as:

```text
persistent reference,
context,
candidate variation,
constraint,
selection,
continuity,
or feedback.
```

---

## Cognitive Self

A system's internal representation of itself as an object of cognition.

This is distinct from Structural Self.

A system may have a Structural Self without possessing an explicit Cognitive Self.

---

## Consequence

The externally or persistently realized result of an unfolding operation.

Consequences may include:

```text
Code modification
Physical movement
Database change
Policy change
External API call
Persistent memory update
```

---

## Consequential Boundary

The boundary at which internal candidate unfolding becomes an external, persistent, privileged, or safety-relevant consequence.

Conceptually:

```text
Internal Unfolding
      ↓
Candidate Delta
      ↓
========================
 CONSEQUENTIAL BOUNDARY
========================
      ↓
Certification
      ↓
Authorized Consequence
```

---

## Consequential Structural Interface

A structural representation exposed between machine-native internal cognition and governed external action.

Examples may include:

```text
CallingGraph Delta
Action Graph
Policy Tree
State-Transition Plan
Capability Manifest
Invariant Set
```

Its purpose is not necessarily to expose every internal computation.

Its purpose is to make consequential change governable.

---

## Constraint

A condition that restricts which unfolding transitions are admissible.

Examples include:

```text
Physical limits
Safety rules
Security boundaries
Type constraints
API contracts
Permissions
Resource limits
```

Constraint answers:

> What may not be violated?

This differs from Policy, which helps choose among admissible options.

---

## Context

The runtime conditions under which unfolding occurs.

Examples include:

```text
Prompt
Task
Environment
Current State
Conversation
Repository State
Sensor Input
History
```

The same Core Structure may unfold differently under different Contexts.

---

## Continuity

The relation that allows a changing structure to remain an acceptable continuation of an earlier structure.

Possible continuity dimensions include:

```text
Invariant continuity
Memory continuity
Goal continuity
Policy continuity
Functional continuity
Runtime lineage
```

Continuity is central to Structural Self.

---

## Control

The organization, restriction, selection, or correction of unfolding.

Control may involve:

```text
Constraint
Policy
Evaluation
Invariant
Certification
Feedback
```

GSUI treats control as part of intelligent unfolding, not merely as an external safety wrapper.

---

## Control Plane

The set of mechanisms that govern consequential unfolding.

A provisional GSUI Control Plane may include:

```text
Triggering
Constraints
Policy
Evaluation
Invariant Checking
Certification
Authorization
Feedback Handling
Growth Promotion
```

The Control Plane may itself be symbolic, learned, probabilistic, hierarchical, or hybrid.

---

## Core Structure

The persistent structure treated as the structural reference for a particular unfolding operation.

Examples:

```text
CallingGraph
Tree
ANN parameters
Policy structure
Memory
Repository structure
Vehicle runtime state
```

Core does not mean immutable.

It means sufficiently persistent to serve as a reference for Delta.

Core Structure is related to, but not identical with, Structural Self.

---

## Core-Preserved Generation

Generation constrained so that specified structural properties remain preserved.

Conceptually:

$$
Generate(S,\Delta)
$$

subject to:

$$
Invariant(S')=true
$$

Possible applications include:

```text
Code
Documents
Architecture
Policy
Design
```

---

# D

## Delta

See **Delta Modification**.

---

## Delta Modification

A candidate or realized modification relative to an existing structural reference.

In simplified form:

$$
S_{t+1}=S_t\pm\Delta_t
$$

Delta may include:

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
Move
Preserve
```

Delta is broader than addition.

---

## Delta Space

The family of candidate structural modifications available from a current structure.

This may be treated as one representation of an Unfolding Space.

$$
\mathcal{D}_{candidate} =
\{
\Delta_1,\Delta_2,\ldots,\Delta_n
\}
$$

---

## Deployment Frontier

The boundary of unfolding that is currently certified and authorized for external deployment.

The Deployment Frontier may intentionally remain inside the Capability Frontier.

---

## Direct Routing

A structural mechanism that moves from trigger or recognized state directly to a relevant branch, operator, or leaf without large intermediate search.

Conceptually:

```text
Trigger
  ↓
Direct Structural Route
  ↓
Relevant Leaf
```

Direct routing is one form of effective Unfolding Space compression.

---

# E

## Evaluation

The process of judging the quality, desirability, usefulness, risk, or suitability of a candidate Delta.

Evaluation may be:

```text
Scalar
Boolean
Ordinal
Multi-objective
Metric-based
Policy-based
Human-reviewed
Probabilistic
```

Evaluation is distinct from Certification.

A high evaluation score does not automatically authorize execution.

---

## Expand

An unfolding operator that increases available structure, state, branch, capability, or reachable possibility.

Expansion is only one form of unfolding.

GSUI does not equate unfolding with expansion.

---

# F

## Feedback

Information returned after an unfolding consequence.

Feedback may include:

```text
Success
Failure
Reward
User correction
World response
Structural mismatch
Performance change
Invariant degradation
```

Feedback is not automatically Structural Growth.

$$
Feedback \neq Growth
$$

unless persistent future structure is changed.

---

## Folding

The broad process by which observations, experience, data, or repeated relations are compressed, learned, organized, or consolidated into persistent structure.

Canonical direction:

```text
Observation
   ↓
Data
   ↓
Compression / Learning
   ↓
Structure
```

Examples include:

```text
Neural training
Graph extraction
Tree construction
Memory consolidation
Representation learning
```

Folding and Unfolding are complementary, not necessarily mathematical inverses.

---

## Folding–Unfolding Cycle

The larger GSUI cycle:

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
Action
  ↓
Feedback
  ↓
Growth / Refolding
```

---

# G

## General Structure Unfolding

The study of structural transitions across different domains using a shared structural language.

It focuses on recurring forms such as:

```text
Persistent Structure
+
Context
+
Delta
→
Resulting Structure / Behavior
```

Generality refers to structural comparability, not algorithmic identity.

---

## General Structure Unfolding Intelligence

The GSUI research paradigm.

A working definition is:

> **General Structure Unfolding Intelligence is the study and construction of intelligent systems in which persistent structure is contextually unfolded through candidate structural modifications that are triggered, constrained, selected, evaluated, certified, and potentially retained as future structure.**

Short form:

> **Intelligence as controlled structural unfolding.**

---

## Generation

The production of a representational artifact or continuation.

Examples:

```text
Text
Image
Code
Audio
Plan
```

Within GSUI:

> **Generation is one form of unfolding.**

Conceptually:

$$
Generation \subset Unfolding
$$

---

## Governance Growth

Growth in the system's ability to remain observable, constrained, certifiable, auditable, reversible, and structurally coherent as capability increases.

Possible components include:

```text
Better invariants
Better policy
Better certification
Better rollback
Better observability
Stronger structural boundaries
```

---

## Growth

See **Structural Growth**.

---

## Growth Operator

A mechanism that promotes selected runtime outcomes into persistent future structure.

A generic form is:

$$
S^{core}_{t+1} =
G(S^{core}_t,\Delta_t,F_t)
$$

where \(G\) is a growth or consolidation operator.

---

# H

## Human-Governable Consequences

The principle that machine-native cognition may remain internally non-anthropomorphic while consequential external actions remain subject to human-defined structural governance.

Canonical phrase:

> **Machine-native cognition; human-governable consequences.**

---

# I

## Inhibition

An unfolding operator that suppresses activation, selection, transition, or structural possibility.

Inhibition can improve intelligence by removing irrelevant or unsafe unfolding.

---

## Internal Interpretability

The extent to which humans can understand the internal computational process of an AI system.

GSUI distinguishes this from:

* Structural Observability
* Action Certifiability

Limited Internal Interpretability does not logically require abandoning structural governance.

---

## Internal Unfolding

Temporary unfolding occurring inside reasoning, simulation, latent computation, planning, or candidate generation.

Internal Unfolding may not directly create external consequences.

---

## Invariant

A property required to remain sufficiently preserved across structural change.

Examples:

```text
API compatibility
Safety
Security
Control stability
Identity continuity
Required architecture
Functional behavior
```

A generic requirement may be written:

$$
I(S_{t+1})=true
$$

or as a range condition.

---

## Invariant-Preserving Unfolding

Structural unfolding constrained so that relevant invariants remain valid across the transition.

Canonical flow:

```text
Core Structure
     ↓
Candidate Delta
     ↓
Candidate Structure
     ↓
Invariant Check
     ↓
Accept / Reject / Repair
```

---

# L

## Learning

Within the GSUI structural vocabulary:

> **Learning is the incorporation of successful unfolding into future structure.**

This is a structural description, not a replacement for existing mathematical theories of learning.

See also:

* Structural Growth
* Retained Unfolding

---

## Local Unfolding

A context- or trigger-conditioned subset of a larger latent Unfolding Space that becomes active during a particular runtime episode.

---

# M

## Machine-Native Cognition

Internal cognition organized around representations, operators, temporal structures, or perceptual categories that need not imitate human cognition.

Examples may include:

```text
Latent structures
ANN activation patterns
CallingGraphs
Machine-specific memory
Metric structures
CCC structures
```

Machine-Native Cognition does not imply unrestricted external autonomy.

---

## Machine-Native Perception

Perception constructed directly from machine-accessible signals and machine-relevant structures rather than requiring translation into human sensory categories.

Examples include perception of:

```text
CallingGraph topology
RF fields
Network latency
Runtime traces
Database contention
Memory pressure
Industrial telemetry
```

---

## Meaning, Operational

A provisional GSUI concept in which a signal or structure is operationally meaningful if it changes self-relative unfolding.

One possible expression is:

$$
Meaning_{operational} =
Effect\ on\ SelfRelativeUnfolding
$$

This is not intended as a complete philosophical theory of meaning.

---

## Merge

An unfolding operator that combines two or more structural paths, branches, representations, or states.

---

## Meta-Unfolding

Unfolding that modifies the mechanisms governing future unfolding.

Examples:

$$
U\rightarrow U'
$$

$$
P\rightarrow P'
$$

$$
I\rightarrow I'
$$

Meta-Unfolding may modify:

```text
Operator
Policy
Evaluator
Invariant
Certifier
Control Plane
```

It represents a deeper autonomy level than ordinary runtime unfolding.

---

## Metric

A mechanism for measuring distance, difference, similarity, risk, or preference inside an Unfolding Space.

Possible forms include:

```text
Structural distance
Risk distance
Policy distance
Invariant distance
Trajectory distance
```

GSUI treats Metric as one possible family of unfolding-space operators.

---

# N

## Narrative Self

Human-level selfhood involving biography, social identity, narrative continuity, subjective interpretation, and related psychological phenomena.

GSUI distinguishes Narrative Self from Structural Self.

Structural Self does not imply Narrative Self.

---

## Non-Anthropomorphic Intelligence

Intelligence whose perception, representation, cognition, or runtime organization need not follow human perceptual or cognitive categories.

GSUI treats this as compatible with strong external governance.

---

# O

## Observation

Signals or measurements obtained from the world, environment, runtime system, or internal state.

Observation may participate in:

```text
Folding
Perception
Triggering
Evaluation
Feedback
```

---

## Operational Self

The currently actionable form of a Structural Self.

A provisional representation includes:

```text
Structure
Capability
Permission
Current State
Interfaces
Constraints
```

Operational Self answers:

> What can this system currently sense, reach, control, modify, or execute?

---

## Operator

See **Unfolding Operator**.

---

# P

## Perception

A general process that converts signals into operational structure.

Within GSUI:

$$
Perception:
WorldSignals
\rightarrow
SelfRelativeOperationalStructure
$$

Perception is not restricted to human-like sensing.

---

## Permission

The authorization state governing whether a capability may be exercised.

GSUI distinguishes:

$$
Capability \neq Permission
$$

Permission is part of the Operational Self and affects the Allowed Unfolding Space.

---

## Policy

A mechanism that helps determine which admissible unfolding alternatives are preferred.

Policy answers:

> Among what is allowed, what should be favored?

This differs from Constraint, which defines what must not be violated.

---

## Possible Unfolding Space

The broad family of transitions that could conceptually emerge from the current structure.

This is generally the largest GSUI unfolding category.

---

## Preferred Unfolding Space

The subset of allowed unfolding considered more desirable under current goals, policy, risk, or evaluation.

$$
\mathcal{U}_{preferred}
\subseteq
\mathcal{U}_{allowed}
$$

---

## Preserve

An unfolding decision in which the current structure remains unchanged or a critical property is deliberately maintained.

Preservation may correspond to a structural zero-Delta:

$$
\Delta = 0
$$

or to an explicit PRESERVE operator.

Intelligent non-modification is therefore part of GSUI.

---

## Primitive Compression

The hypothesis that many human-defined intelligence categories may be expressible through compositions of a smaller family of structural unfolding primitives.

Candidate primitives may include:

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

---

# R

## Reachability

Whether a candidate unfolding can actually be reached from the current structure under available resources, state, time, topology, and capabilities.

$$
\mathcal{U}_{reachable}
\subseteq
\mathcal{U}_{possible}
$$

---

## Reachable Unfolding Space

The subset of possible unfolding that is structurally or operationally reachable from the current state.

---

## Refolding

The consolidation of feedback or successful unfolding back into persistent structure.

Conceptually:

```text
Unfolding
  ↓
Feedback
  ↓
Retention
  ↓
Refolding
  ↓
Updated Structure
```

Refolding is closely related to Structural Growth.

---

## Reference Frame of Unfolding

The structure relative to which Delta, capability, continuity, and operational meaning are defined.

Within GSUI, Structural Self is the principal concept used for this role.

---

## Retained Unfolding

An unfolding result that becomes part of future persistent structure.

Retained Unfolding is a key mechanism of Structural Growth.

---

## Runtime Unfolding

Temporary unfolding used for current inference, generation, reasoning, planning, routing, or action.

Runtime Unfolding does not necessarily modify persistent Core Structure.

---

# S

## Search

The process of exploring or selecting among candidates within a sufficiently defined candidate space.

GSUI distinguishes Search from Unfolding.

Canonical distinction:

> **Search selects within possibility. Structural unfolding can change possibility itself.**

---

## Selected Delta

The candidate Delta chosen for further certification or application.

$$
\Delta^* =
Select(
\Delta_1,\ldots,\Delta_n
)
$$

Selected does not automatically mean Certified.

---

## Selected Unfolding Space

The final candidate or narrow subset chosen from the Preferred Unfolding Space.

$$
\mathcal{U}_{selected}
\subseteq
\mathcal{U}_{preferred}
$$

---

## Self

See **Structural Self**.

GSUI uses the word *Self* cautiously and primarily in an operational structural sense unless otherwise specified.

---

## Self-Relative World Model

A world representation interpreted relative to the acting Structural Self.

A provisional form is:

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

This does not deny objective world structure.

It emphasizes that operational meaning may depend on the acting system.

---

## Self–World–Unfolding Triad

The GSUI relationship among:

```text
Structural Self
World Model
Unfolding Space
```

Conceptually:

```text
           STRUCTURAL SELF
              /       \
             /         \
            ▼           ▼
     WORLD MODEL ←──→ UNFOLDING SPACE
```

The three components mutually constrain operational intelligence.

---

## Structural Certification

Certification based on explicit structural properties rather than only output-level evaluation.

Examples include:

```text
CallingGraph comparison
Invariant checking
Architecture validation
State-transition verification
Policy compliance
```

---

## Structural Continuity

Continuity defined through preserved relations, invariants, lineage, memory, function, or other identity-critical structure across change.

---

## Structural Delta

A Delta expressed in structural terms.

Examples:

```text
ΔCallingGraph
ΔTree
ΔPolicy
ΔTrajectory
ΔMemory
ΔArchitecture
```

---

## Structural Distance

A measure of difference between two structures.

Structural Distance may differ significantly from representation-level distance.

For example:

```text
small code diff
≠
small architectural Delta
```

---

## Structural Growth

The incorporation of selected unfolding outcomes into persistent structure such that future unfolding possibilities are changed.

Working definition:

> **Structural Growth is retained unfolding that changes future unfolding capacity.**

Growth may:

```text
Expand
Contract
Reorganize
Compress
Redirect
Constrain
```

future Unfolding Space.

---

## Structural Observability

The ability to identify and inspect consequential structural changes proposed or executed by a system.

Structural Observability is distinct from Internal Interpretability.

A system may have opaque internal reasoning while still exposing:

```text
Planned Delta
CallingGraph change
Action graph
Policy change
Invariant state
```

---

## Structural Perception

The construction of operational structure from available signals so that unfolding can be triggered, constrained, evaluated, or controlled.

Unlike Anthropomorphic Perception, Structural Perception does not require human-like sensory categories.

---

## Structural Self

A central GSUI concept.

Working definition:

> **Structural Self is the persistent structural reference frame relative to which unfolding, modification, capability, preservation, and continuity are defined.**

Short form:

> **Self is the reference frame of unfolding.**

Structural Self does not imply:

```text
Consciousness
Subjective experience
Personhood
Narrative identity
Moral status
```

---

## Structural Self Continuity

The managed preservation of identity-relevant structure across Self modification.

Possible continuity criteria include:

```text
Invariant continuity
Memory continuity
Policy continuity
Goal continuity
Runtime lineage
Functional continuity
```

---

## Structural Self Growth

Persistent modification of Structural Self that changes capability, memory, policy, structure, permission, or future Unfolding Space.

---

## Structural Transition

A change from one structure or state to another.

Generic form:

$$
S_t\rightarrow S_{t+1}
$$

Not every structural transition is necessarily intelligent unfolding.

---

## Structural Unfolding

The context-conditioned realization, activation, selection, or modification of an existing structure into a new runtime state, behavior, action, or structure.

Structural Unfolding may be:

```text
Temporary
Persistent
Representational
Physical
Topological
Latent
```

---

## Structural Unfolding Intelligence

The capacity of a structured system to produce, select, evaluate, and incorporate context-conditioned structural variations while preserving relevant core invariants.

This is the core intelligence concept inside GSUI.

---

# T

## Trigger

An event or condition that initiates or localizes unfolding.

Examples include:

```text
Prompt
Function call
Threshold crossing
Sensor event
Detected Gap
Goal activation
Human request
```

Context describes current conditions.

Trigger explains why unfolding begins now.

---

## Triggering

The process by which a latent structure or region of Unfolding Space becomes active.

A simplified form is:

```text
Latent Unfolding Space
        ↓
Trigger
        ↓
Activated Region
        ↓
Candidate Delta
```

---

# U

## Unfolding

The context-conditioned realization of possibilities from persistent structure.

Unfolding may produce:

```text
Reasoning
Generation
Routing
Selection
Planning
Action
Structural modification
```

Unfolding is broader than generation and distinct from search.

---

## Unfolding Algebra

A future formal system in which complex unfolding can be constructed by composing primitive operators.

A generic form is:

$$
U =
u_n\circ ... \circ u_2\circ u_1
$$

This remains a future research direction.

---

## Unfolding Boundary

A boundary separating possible unfolding from a narrower permitted region.

Canonical relation:

$$
\mathcal{U}_{allowed}
\subseteq
\mathcal{U}_{possible}
$$

The Unfolding Boundary may be defined by:

```text
Policy
Permission
Physical limits
Invariant
Security
Safety
```

---

## Unfolding Freedom

The breadth of structural possibilities a system can internally or externally explore.

GSUI does not equate greater Unfolding Freedom with greater intelligence.

Greater freedom may increase the need for stronger Control and Certification.

---

## Unfolding Operator

A mechanism that produces or applies a structural transition.

Generic form:

$$
S_{t+1} =
U(S_t,\Delta_t,C_t,P_t)
$$

Possible operator families include:

```text
Activate
Branch
Merge
Select
Reweight
Move
Connect
Suppress
Generate
Preserve
Promote
```

---

## Unfolding Primitive

A candidate minimal operator used to construct more complex intelligent unfolding.

Examples may include:

```text
OBSERVE
COMPARE
TRIGGER
ACTIVATE
INHIBIT
SELECT
BRANCH
MERGE
MOVE
MEMORIZE
EVALUATE
CERTIFY
PRESERVE
```

No final primitive set is yet claimed.

---

## Unfolding Space

The structured family of transitions available from a current structure under current context.

Notation:

$$
\mathcal{U}(S,C)
$$

For acting systems:

$$
\mathcal{U}(Self,World,Context)
$$

The Unfolding Space may contain:

```text
Possible states
Branches
Actions
Plans
Trajectories
Generations
Structural Deltas
```

---

## Unfolding-Space Compression

The reduction of effective unfolding complexity through structural organization.

Examples include:

```text
Direct routing
Branch pruning
Trigger localization
Policy filtering
Memory reuse
Structural recognition
```

The objective is not merely fewer possibilities, but better organized possibilities.

---

## Unfolding-Space Frontier

The current boundary between reachable and currently unreachable unfolding.

Provisionally:

$$
\partial\mathcal{U}
$$

Growth may move, reshape, expand, or contract this frontier.

---

## Unfolding-Space Geometry

A future mathematical research direction studying properties such as:

```text
Distance
Topology
Reachability
Connectivity
Branching
Risk
Density
Invariant deviation
Policy preference
```

inside Unfolding Space.

---

## Unfolding Universality

The working hypothesis that a broad class of intelligent processes may share a useful structural description as constrained unfolding from persistent structure.

It does not claim that all intelligence is one algorithm.

---

# W

## World

The external or operational environment with which an intelligent system interacts.

The World may include:

```text
Physical environment
Software environment
Network environment
Database state
Task environment
Social environment
```

---

## World Model

A structured representation used to predict, organize, or reason about the world and its consequences.

GSUI distinguishes between:

```text
Objective World Structure

Perceived World Structure

Self-Relative Operational World Structure
```

For action-oriented intelligence, a useful form may be:

$$
WM =
WM(World\mid Self,Context,Capability,Goal)
$$

---

# Canonical Distinctions

The following distinctions should remain explicit throughout GSUI.

## Folding vs Unfolding

```text
Folding
→ forms persistent structure

Unfolding
→ realizes or modifies structure at runtime
```

---

## Core Structure vs Structural Self

```text
Core Structure
→ reference structure for a particular unfolding operation

Structural Self
→ broader persistent reference frame across an operational lineage
```

They may overlap, but are not identical.

---

## Delta vs Operator

```text
Delta
→ what changes

Operator
→ how the change is produced or applied
```

---

## Context vs Trigger

```text
Context
→ what conditions currently exist

Trigger
→ why unfolding begins now
```

---

## Constraint vs Policy

```text
Constraint
→ what must not be violated

Policy
→ what should be preferred among admissible options
```

---

## Evaluation vs Certification

```text
Evaluation
→ how good is the candidate?

Certification
→ is the candidate acceptable for consequential execution?
```

---

## Capability vs Permission

```text
Capability
→ what the system can do

Permission
→ what the system is authorized to do
```

---

## Possible vs Reachable

```text
Possible
→ conceptually available

Reachable
→ attainable from the current state
```

---

## Allowed vs Preferred

```text
Allowed
→ admissible

Preferred
→ favored
```

---

## Selected vs Certified

```text
Selected
→ chosen candidate

Certified
→ approved for consequential execution
```

---

## Search vs Unfolding

```text
Search
→ selects within a sufficiently defined space

Unfolding
→ may change the structure that defines future space
```

---

## Feedback vs Growth

```text
Feedback
→ information returned from consequence

Growth
→ persistent change that alters future unfolding
```

---

## Runtime Unfolding vs Structural Growth

```text
Runtime Unfolding
→ temporary current behavior

Structural Growth
→ persistent future capability change
```

---

## Structural Self vs Consciousness

```text
Structural Self
→ operational reference frame

Consciousness
→ separate philosophical / cognitive question
```

No equivalence is claimed.

---

## Internal Interpretability vs Structural Observability

```text
Internal Interpretability
→ understand internal computation

Structural Observability
→ observe consequential structural change
```

---

## Structural Observability vs Action Certifiability

```text
Structural Observability
→ see what is changing

Action Certifiability
→ determine whether it may safely proceed
```

---

## Machine-Native Cognition vs Machine Sovereignty

```text
Machine-Native Cognition
→ non-human internal cognition is possible

Machine Sovereignty
→ unrestricted authority does not follow
```

Canonical principle:

> **Machine-native cognition; human-governable consequences.**

---

# Canonical Equations

## Minimal Structural Transition

$$
S_{t+1} =
S_t\pm\Delta_t
$$

---

## General Runtime Form

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

---

## Unfolding Space

$$
\mathcal{U} =
\mathcal{U}(S,C)
$$

or for acting systems:

$$
\mathcal{U} =
\mathcal{U}(Self,World,Context)
$$

---

## Unfolding-Space Hierarchy

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

---

## Structural Growth

$$
S^{core}_{t+1} =
G(
S^{core}_t,
\Delta_t,
F_t
)
$$

---

## Self-Relative World Model

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

---

## Structural-Self Evolution

$$
Self_t
\rightarrow
\mathcal{U}_t
\rightarrow
\Delta_t
\rightarrow
Self_{t+1}
\rightarrow
\mathcal{U}_{t+1}
$$

---

# Canonical GSUI Cycle

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
Candidate Delta
  ↓
CONTROL PLANE
  ↓
Selected / Certified Delta
  ↓
Action / Generation
  ↓
WORLD
  ↓
Feedback
  ↓
STRUCTURAL GROWTH
  ↓
Updated Core Structure
  ↓
New Unfolding Space
```

Across the cycle:

```text
STRUCTURAL SELF
```

provides the reference frame for:

```text
Delta
Capability
Continuity
World-model meaning
Unfolding Space
Growth
```

---

# Canonical GSUI Statements

> **Intelligence does not begin only with computation over data; it can also be studied as the unfolding of structure.**

> **A broad class of intelligent processes can be represented as `<Core Structure> +/- <Delta Modification>`.**

> **Generation is one form of unfolding; unfolding is broader than generation.**

> **Search selects within possibility; structural unfolding can change possibility itself.**

> **Learning becomes Structural Growth when retained unfolding changes future unfolding capacity.**

> **Control is part of intelligence because intelligence requires organization of possibility.**

> **Invariant defines continuity across unfolding.**

> **Self is the reference frame of unfolding.**

> **Self need not begin with consciousness. It may begin with structural continuity.**

> **Machine-native cognition; human-governable consequences.**

> **Shared structural form does not imply algorithmic equivalence.**

---

# Terminology Discipline

GSUI terminology should be used with care.

Avoid:

> **Everything is unfolding.**

Prefer:

> **A broad class of intelligent processes may be usefully analyzed as constrained structural unfolding.**

Avoid:

> **All structures are equivalent.**

Prefer:

> **Different systems may share a structural form while implementing different algorithms.**

Avoid:

> **Structural Self is AI consciousness.**

Prefer:

> **Structural Self is an operational reference-frame concept independent of consciousness claims.**

Avoid:

> **Opaque cognition makes structural control unnecessary.**

Prefer:

> **Opaque internal cognition increases the importance of observable and certifiable consequential boundaries.**

---

# Final Compact Glossary

```text
Folding
= formation or consolidation of persistent structure

Core Structure
= persistent reference for a specific unfolding operation

Delta
= modification relative to existing structure

Unfolding
= context-conditioned realization or modification of structure

Unfolding Operator
= mechanism that produces structural transition

Unfolding Space
= structured set of possible next transitions

Trigger
= mechanism that activates unfolding now

Constraint
= rule defining what may not be violated

Policy
= mechanism defining preference among admissible options

Evaluation
= judgment of candidate quality

Invariant
= property required to remain preserved

Certification
= decision about consequential admissibility

Feedback
= information returned after consequence

Structural Growth
= retained unfolding that changes future unfolding capacity

Structural Self
= persistent reference frame of unfolding and continuity

Operational Self
= Structural Self plus current capability, permission, and state

World Model
= structured representation of world and possible consequences

Machine-Native Perception
= machine-specific operational perception

Structural Observability
= visibility of consequential structural change

Action Certifiability
= ability to approve or reject consequential change

Meta-Unfolding
= modification of the mechanisms governing future unfolding
```

---

**GSUI — General Structure Unfolding Intelligence**

**Canonical Glossary**

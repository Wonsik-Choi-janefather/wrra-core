# WRRA Core 1.0

**A Domain-Agnostic Execution Architecture for the Wonsik Reality–Renderer Architecture**

Domain-Agnostic Execution Architecture

Core Specification Preserving Minimum Computation, the Common Carrier, and Phenotype

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Freeze Declaration</strong></p>
<p>WRRA Core 1.0 is frozen as a domain-agnostic execution grammar that is not dependent on the equations or objects of any particular field, including physics, biology, artificial intelligence, economics, meteorology, mathematics, or methodology. Later revisions to Domain Profiles such as MCC/WRRA-Physics, WRRA-Bio, WRRA-AI, WRRA-Econ, and WRRA-Met do not automatically change Core 1.0. The Core changes only when one of the constitutional invariants or required execution elements defined below is itself revised.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

**Wonsik Choi**

Version Freeze: 7 September 2026

## 0. WRRA Core 1.0 in One Sentence

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>WRRA Core 1.0</strong></p>
<p>In any system, SOURCE produces the current state through relations and boundaries; effects of the past operate only through RESIDUE/RECORD remaining in the present; multiple channels reuse a common carrier wherever possible; the next present is updated with the minimum computation required; the RENDERER outputs an observable PHENOTYPE; and the outcome remains as an OBSERVABLE/LEDGER/RECORD.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

| SOURCE → RELATION/LAW → STATE/RESIDUE → BOUNDARY → COMMON CARRIER → UPDATE → RENDERER → PHENOTYPE → OBSERVABLE/RECORD/LEDGER | (0.1) |
|------------------------------------------------------------------------------------------------------------------------------|-------|

This sequence generalizes the SOURCE-to-Reality model developed in physics. In some domains, LAW may be specified as a separate layer; in others, it may be incorporated into RELATION/UPDATE rules. OBSERVABLE, RECORD, and LEDGER may likewise be separated or combined in an implementation. Nevertheless, the three constitutional axes—minimum computation, the common carrier, and phenotype—and the fixed-present principle that execution proceeds through the current state are retained in Core 1.0.

## 1. Three Constitutional Invariants

### 1.1 Minimum Computation — Minimum Viable Computation

WRRA does not aim for peak performance, maximum information, maximum memory, or maximum complexity. Its central rule is to compute only as much as is needed to cross the declared boundary of expression, function, survival, or stability, without adding unnecessary states, relations, memory, transport, or reserve beyond that point. Reserve or redundancy required for viability under extreme environments, however, is not waste; it belongs to the minimum cost of survival.

| A\* ∈ ParetoMin { C(A) \| A satisfies declared viability / expression contract } | (1.1) |
|----------------------------------------------------------------------------------|-------|

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Prohibited Misreading</strong></p>
<p>Minimum computation does not mean “compute as little as possible” without qualification. If required distinctions are removed until expression or survival collapses, the result is deficiency, not minimality. Conversely, continuing to add relations, memory, carriers, or resources after the boundary has been crossed is excess.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 1.2 Common Carrier

When different channels do not require separate origins and separate transmission mechanisms, WRRA uses one or a small number of reusable transport/update structures as a common carrier. A common carrier does not erase distinctions among channels. Different cargoes can retain distinct ownership and destinations even when they travel on the same road.

| D_C : ⊕\_i H_i → ⊕\_i H_i, shared transport ≠ erased channel identity | (1.2) |
|-----------------------------------------------------------------------|-------|

The common carrier is not limited to the 15-channel carrier of physics. In biology, it may be a reusable execution scaffold integrating translation, metabolism, membrane transport, and partitioning; in AI, a sensory-state-action transmission network; in economics, a transaction, price, credit, and information network; and in meteorology, a shared update field for atmospheric state and flow. Each Domain Profile must state what is transported and which common structure is reused.

### 1.3 Phenotype

WRRA does not assume that SOURCE or internal STATE is identical to the object of observation. Internal information, states, and relations pass through a RENDERER and a BOUNDARY to become a phenotype that can actually be read. Phenotypes are domain-specific: particles, forces, and vacuum output in physics; proteins, cellular states, and differentiation in biology; actions in AI; prices, transactions, and crisis states in economics; and observable tropical-cyclone tracks in meteorology.

| PHENOTYPE_t = Φ_D(STATE_t, BOUNDARY_t, RENDERER_D) | (1.3) |
|----------------------------------------------------|-------|

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Core Principle</strong></p>
<p>The shortcuts “SOURCE is the outcome,” “internal state is observation,” and “what is possible is what is actually occupied” are prohibited. A Domain Profile must explain the renderer between internal state and phenotype.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 2. Required Execution Elements of Core 1.0

| **Core Element**          | **Audit Question**                                                                    | **Example**                                                      |
|---------------------------|---------------------------------------------------------------------------------------|------------------------------------------------------------------|
| SOURCE                    | What independent information, resources, and boundary inputs enter current execution? | DNA / sensor / market shock / initial field                      |
| RELATION / LAW            | What affects what, and which rules are permitted?                                     | coupling / network / physical law / reaction                     |
| STATE                     | What internal state actually exists now?                                              | concentration / activity / field / price state                   |
| RESIDUE / CARRY           | What effect of the past remains in the present?                                       | memory / adaptation / epigenetics / debt / environmental residue |
| BOUNDARY                  | What lies inside or outside the system, and which flows open or close?                | membrane / body / market institution / observation region        |
| COMMON CARRIER            | What transport/update scaffold is shared across channels?                             | transport operator / translation system / network                |
| UPDATE / TAKEOVER / RESET | How does the current present become the next present?                                 | dynamics / division / policy / state transition                  |
| RENDERER                  | By what rule does an internal state become an external expression?                    | measurement channel / protein execution / action policy          |
| PHENOTYPE                 | What output/state is actually instantiated?                                           | particle / cell fate / action / price / cyclone state            |
| OBSERVABLE                | What can actually be measured?                                                        | sensor value / omics / survival / track error                    |
| RECORD / LEDGER           | What is persistently recorded, and which totals/responsibilities are tracked?         | history / resources / energy / generation record                 |

### 2.1 Fixed-Present Principle

WRRA Core does not require a structure that directly rereads the entire sequence of past events at every step. If the past affects the present, its effect must remain physically or informationally instantiated in the current STATE, RESIDUE, or RECORD.

| X\_(t+1) = F_D(X_t, S_t, R_t, B_t, C_t), history enters only through present-instantiated residue/record | (2.1) |
|----------------------------------------------------------------------------------------------------------|-------|

This does not mean that memory is absent. Rather, it fixes the ownership of memory in the present. A model may refer directly to a past log, but it must specify that the log is a RECORD accessible in the present.

### 2.2 Ownership Principle

Even the same number, signal, or state is not the same variable when it belongs to a different owner. WRRA specifies the owner of information, resources, forces, memory, and outputs. This principle makes it possible to distinguish gravitational Tμν from gauge currents in physics, DNA from translation machinery in biology, sensors from memory in AI, and current sentiment from genuine residue in economics.

| Owner(z) must be declared before z is used as state, residue, carrier, or observable | (2.2) |
|--------------------------------------------------------------------------------------|-------|

### 2.3 Fail-Closed Boundary Principle

WRRA does not inflate structural executability into empirical validation by nature. Interpretation, computation, prediction, control, and empirical validation are distinct contracts. When data, time, causality, or comparison baselines are insufficient, the result is frozen as OPEN or PARTIAL.

| **CONTRACT**   | **Core Definition**                                                                                     |
|----------------|---------------------------------------------------------------------------------------------------------|
| INTERPRETATION | Reconstruct a current or already recorded target within tolerance using current/recorded information    |
| COMPUTATION    | Produce the next state from a complete current state under a given update rule                          |
| PREDICTION     | Reduce the loss or uncertainty distribution of a future target using current information                |
| CONTROL        | Select actions that change future viability or objectives                                               |
| OPEN           | The contract is not closed with respect to information, error, time, causality, or computational budget |

## 3. Separation of Core and Domain Profiles

WRRA Core 1.0 contains no domain-specific equations or objects. Each application is managed as a Domain Profile. A Domain Profile maps the actual owners and equations of Core elements, but changes in that profile do not automatically change the Core version.

| WRRA Domain Profile D = Map_D(Core elements → domain states, carriers, renderers, observables, ledgers) | (3.1) |
|---------------------------------------------------------------------------------------------------------|-------|

| **Verdict**             | **Example of Change**                                                                      |
|-------------------------|--------------------------------------------------------------------------------------------|
| Core 1.0 retained       | Domain-specific coefficients, equations, datasets, or carrier implementations change       |
| Core 1.0 retained       | MCC/WRRA-Physics is updated from 2.0 to 2.1 to 2.2                                         |
| Core 1.0 retained       | Experimental results in WRRA-Bio/AI/Econ/Met change from success to failure, or vice versa |
| Review Core major/minor | The definition of minimum computation itself changes                                       |
| Review Core major/minor | The common carrier or phenotype is removed from or redefined within the required axes      |
| Review Core major/minor | The fixed-present, ownership, or fail-closed principle is abandoned                        |

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Version Rule</strong></p>
<p>Future notation is separated as follows: WRRA Core 1.0 / WRRA-Physics (MCC) 2.x / WRRA-Bio 4.x / WRRA-Cell 0.x / WRRA-AI 2.x / WRRA-Worm 0.x–1.x / WRRA-Econ 0.x / WRRA-Met 0.x / WRRA-Method 2.x. Reinforcing physics with string theory or incrementing the cosmology version does not require revisions to documents in biology, AI, economics, or meteorology.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 4. Official Application Lineage — Through 7 September 2026

The following registry reclassifies, from the perspective of Core 1.0, the applications that had been developed as models, papers, or validation programs using the WRRA name and execution grammar by the freeze date. “Application” does not mean that the Core has been proven correct in that field; it means that the Core grammar has been implemented as a particular Domain Profile.

### 4.1 WRRA-Physics / Minimal Computing Cosmology

| **Application / Research Line**                         | **Core Mapping**                                                                                   | **Meaning of the Freeze**                                |
|---------------------------------------------------------|----------------------------------------------------------------------------------------------------|----------------------------------------------------------|
| WRRA Axiomatic / Physical Realization                   | Separates the layers of classical, relativistic, and quantum possibility from physical realization | Upper-level physics architecture                         |
| Minimal Computing Cosmology 2.0                         | LAW→SOURCE→EXECUTION→RENDERER→REALITY→RECORD; minimum dimension, structure, and computation        | Physics/cosmology reference version                      |
| MCC 2.1 string-microphysics repair                      | Retains the MCC skeleton and uses string theory as microphysical repair material                   | Physics Profile reinforced; Core unchanged               |
| Dimensional filter / 3+1 Reality                        | Distinguishes physical spacetime from internal, Hilbert-space, and registry dimensions             | Structural minimality                                    |
| Asymmetric unification of the four forces               | Total gravitational Tμν owner versus selective gauge-current owners                                | Theoretical result                                       |
| Common carrier / 15 chiral channels                     | Common transport operator with selective expression                                                | Central Physics carrier                                  |
| Big Bang / opening                                      | Dormant state, minimum SOURCE η, and a constraint-preserving boundary transition                   | Implementation of cosmic history                         |
| Hot Big Bang closure                                    | Kination/energy transfer Qr → radiation domination                                                 | Final reinforcement of 2.0                               |
| Matter–antimatter / matter-dominant Reality             | Separates lawful sector from occupied Reality; tracks the owner of asymmetry                       | Dynamical/predictive target                              |
| Vacuum                                                  | Zero real-particle-output phenotype in a stationary background                                     | Physical phenotype                                       |
| Pair creation and annihilation                          | Conditional output and conservative transfer of carrier ownership                                  | Repositioning of physical phenomena                      |
| Antimatter-generation scenario                          | Direction-history and pair-plasma validation protocol                                              | Independent deviation OPEN                               |
| Dark matter                                             | Conditions for a gauge-singlet candidate that remains in Tμν                                       | Candidate/owner conditions                               |
| Black holes                                             | Finite boundary information, internal transport/record, and compatibility fiber                    | Boundary/information application                         |
| Temperature and entropy                                 | Accessible state count and multiplicity of histories indistinguishable from the current record     | Coarse-graining application                              |
| Quantum–macro boundary / two-pass outcome               | Lawful support, quantum instrument, record redundancy, and phenotype threshold                     | Method + physics                                         |
| Superconductivity and superfluidity                     | Pairing/phase stiffness and boundary/carry/reset ledger                                            | Structural reinterpretation; new surplus prediction OPEN |
| Nuclear decay / multiple decay clocks                   | Channel-specific barriers and transition rules separated from half-life clocks                     | Physics series                                           |
| Stability of superheavy nuclei                          | Audit against fission/decay baselines with failure preservation                                    | Validation-oriented application                          |
| Pulsars/intermittent pulsars and time correction        | Application through rhythm, state transitions, records, and clocks                                 | Physics extension                                        |
| Macroscopic determinacy and microscopically open events | Boundary between probabilistic events and stable records                                           | Physics methodology                                      |

### 4.2 WRRA-Math / Arithmetic and Proof-Boundary Research Line

| **Application**                                      | **Core Mapping**                                                                           | **Status**                               |
|------------------------------------------------------|--------------------------------------------------------------------------------------------|------------------------------------------|
| WRRA 2.0 prime/composite SOURCE–RELATION registry    | Models independent SOURCE and folded relation addresses arithmetically                     | Historical upstream branch; not the Core |
| WJNS arithmetic stability gate                       | Uses zeta/Mellin/reflection structure as a stability gate                                  | Separated from physical time             |
| Riemann Hypothesis boundary studies                  | Distinguishes finite computation/verification from proof closure over an infinite totality | RH proof OPEN                            |
| RH audit by the Interpretation–Prediction classifier | Classifies a static infinite proposition as a proof-closure problem, not future prediction | Methodological application               |

This arithmetic research line does not justify placing primes, the zeta function, or the Riemann Hypothesis inside WRRA Core. It is a particular Domain Profile or a historical upstream implementation; WRRA applications in other domains are not required to use it.

### 4.3 WRRA-Bio / Life, Genetics, and Cells

| **Model / Application**                             | **Core Mapping**                                                                                                                             | **Current Meaning**                                                                        |
|-----------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Life Model 0 — First Living System                  | Defines the first living lineage when information, catalysis, boundary, energy, and partitioning produce generational closure with R_life\>1 | Executable inference; historical first sequence/path OPEN                                  |
| Life Model I — Minimal Modern Cell                  | Information, translation/execution, metabolism, membrane, and division/generation gate                                                       | Computational closure PASS; fully autonomous experiment OPEN                               |
| Life Model II — DNA→RNA→Protein                     | DNA as SOURCE; polymerase/ribosome as material renderer/executor; coding lower bound and bootstrap                                           | Equations/structure EXACT; autonomy OPEN                                                   |
| Life Model III — Daughter/Lineage Closure           | Finite molecular partitioning, active equalization, and generational reproduction number                                                     | Lineage-closure model                                                                      |
| Life Model IV — Epigenetic Memory & Differentiation | Models current residue as coupled states of methylation, histones, accessibility, RNA, and protein                                           | Prediction/validation program                                                              |
| Life Model V                                        | Multiple memory eigenmodes and cross-layer transfer                                                                                          | Extension of epigenetic memory                                                             |
| Life Model VI                                       | Noncommuting order effects in cell-fate programming                                                                                          | Differential prediction                                                                    |
| Life Model VII                                      | Induced state versus clonal selection                                                                                                        | Separation of alternative explanations                                                     |
| Life Model VIII                                     | Reversible write–erase–rewrite epigenetic editing                                                                                            | Causal rescue experiment                                                                   |
| Life Model IX                                       | Extracellular/niche memory                                                                                                                   | Distributed residue outside the cell                                                       |
| Life Model X                                        | Autonomous closure threshold for memory, execution, repair, boundary, and selection                                                          | Boundary of first life/autonomy                                                            |
| WRRA-Cell 0.1–0.4                                   | Fast program + slow residue + nutrient/substrate/biomass/waste/damage state; Perturb-seq audit                                               | Structure PASS; 0/12 relations confirmed in actual K562 data, overall biology verdict OPEN |
| Integrated Biology 2.1→3.0→4.0/4.1                  | Integrates DNA→protein→minimal cell→lineage→origin of life with epigenetic memory→fate in one ledger                                         | Auditable research contract                                                                |

#### 4.3.1 Proposed Biotechnology Applications

| **Proposed Application**  | **WRRA Perspective**                                                  |
|---------------------------|-----------------------------------------------------------------------|
| iPSC quality control      | Detect donor residue and incomplete resetting                         |
| Precision differentiation | Temporal control that opens and closes fate gates in the proper order |
| Organoids                 | Coupling spatial signals with lineage memory                          |
| Cell therapy              | Maintain therapeutic phenotype and safety after division              |
| Immune-cell engineering   | Reset memory/exhaustion states                                        |
| Cancer                    | Separate induction from selection in drug-tolerant persisters         |
| Regenerative medicine     | Control wound memory and redifferentiation                            |
| Biomanufacturing          | Manage generational stability of high-production phenotypes           |

The items in this table are not separately validated WRRA laws. They are directions for biotechnology applications proposed in Life Model IV and Integrated Biology.

### 4.4 WRRA-AI / Embodied Agents and Survival

| **Model**                                        | **Core Mapping**                                                                      | **Frozen Status**                                          |
|--------------------------------------------------|---------------------------------------------------------------------------------------|------------------------------------------------------------|
| WRRA-Worm 0.1                                    | C. elegans-inspired 23-node/57-relation sensor–neural–motor loop                      | Structural execution                                       |
| WRRA-Worm 0.2–0.4                                | Delayed memory, food seeking, unseen-world benchmark; memoryless/RNN/GRU comparison   | Feasibility supported; general superiority not supported   |
| Ground-Up WRRA 0.5                               | Agent construction from the Core without a worm prior                                 | Expansion of the AI Domain Profile                         |
| Memory-required 0.5–0.7                          | Separates tasks that genuinely require success/failure reward memory                  | Memory ownership test                                      |
| Minimal-Calculation Survival 0.8                 | Prioritizes worst-environment survival and reserve rather than maximum reward         | Direct implementation of the minimum-computation principle |
| Autonomous Reserve, Luck, Inheritance 0.9        | Separates external reserve, autonomous reserve, luck/events, and inheritance          | Extension of survival robustness                           |
| C. elegans-Anchored Minimal Survival Circuit 1.0 | Minimal survival circuit closer to C. elegans biology                                 | Biological validation separate                             |
| Integrated WRRA Artificial Intelligence 2.0      | Integrates minimum computation, memory, reserve, luck, and intergenerational transfer | Integrated AI research lineage                             |

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Frozen Lesson for AI</strong></p>
<p>WRRA does not mean an AI “algorithm that performs better.” Equal-budget tests in 0.4 did not confirm a general predictive advantage. From the Core perspective, the result lies in auditable separation of SOURCE/RELATION/STATE/BOUNDARY/RENDERER/OBSERVABLE and in treating minimum computation as a boundary of survival, safety, and required memory/reserve rather than average performance.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 4.5 WRRA-Econ 0.1–0.5

The economics application tested, in toy models and real macroeconomic data, whether the effects of past shocks can remain as present residue in trust, fear, debt, sentiment, institutional memory, and related variables.

| **Layer**                | **Content**                                                                              | **Frozen Verdict** |
|--------------------------|------------------------------------------------------------------------------------------|--------------------|
| Structure                | Executable toy model with state, residue, resources, boundaries, accounting, and regimes | STRUCTURAL PASS    |
| Synthetic identification | Recovery on fresh seeds when residue is a genuine causal state in the generator          | REPLICATED         |
| Real-data generalization | Universal forecasting gain in post-2015 U.S. macroeconomic data                          | NOT ESTABLISHED    |
| Crisis specificity       | Some directional signal in a crisis-memory window, with deterioration in calm periods    | PARTIAL SIGNAL     |
| Measurement/timing       | Current sentiment does not beat a 36-month-lag temporal placebo                          | OPEN               |

Accordingly, WRRA-Econ is not frozen as a theory that asserts an inevitable hidden residue in every economy. Whether the measured coordinates used to date are the intrinsic owners of residue remains open. Preserving this failure illustrates the fail-closed principle of the Core.

### 4.6 WRRA-Met / Meteorology and Tropical Cyclones

The meteorological application used forward splits to test whether residue compressed into the present state adds independent information for tropical-cyclone track prediction beyond raw finite history or a nonlinear present-state baseline. The frozen study compared multiple residue timescales using JMA best-track data from 1951–2025.

| **Stage**                     | **Essence**                                                                                  | **Verdict**            |
|-------------------------------|----------------------------------------------------------------------------------------------|------------------------|
| 0.1 synthetic / structural    | Checks recoverability when residue is causal truth in a controlled system                    | Structure confirmed    |
| Strict forward real-data test | train≤2014, validation 2015–2019, test 2020–2025                                             | Leakage prevented      |
| Baselines                     | Persistence, present-only Ridge/ExtraTrees, raw history, and residue placebo                 | Fair comparison        |
| Decay sensitivity             | Point estimates for several residue families are mostly positive, but no cell is significant | Weak direction         |
| Final interpretation          | No statistically established independent predictive effect of tropical-cyclone track residue | OPEN / not established |

The central lesson for meteorology is not that adding history automatically makes a model WRRA. A candidate residue must outperform raw history, nonlinear present state, a content-free residue placebo, and a temporal-ownership placebo before it can be called independent residue.

### 4.7 WRRA-Method / Interpretation–Prediction Boundary

| **Method**                              | **Core Role**                                                                                                              | **Scope of Application**                                                      |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| Interpretation–Prediction Boundary v1.0 | Separates targets closed by current records from future/unknown-information targets                                        | General methodology                                                           |
| Full Formal System v2.1                 | Includes Bayes risk, compatible-state diameter, threshold sensitivity, Lyapunov/Jacobian amplification, and record quality | Cross-applied to DNA, cells, neural systems, tropical cyclones, and economics |
| Quantum–Macro classifier                | Distinguishes event law, detector/phenotype threshold, amplification, and distinguishable/persistent/redundant records     | Physics boundary                                                              |
| Proof-closure audit                     | Distinguishes static infinite propositions from future prediction                                                          | Mathematical application                                                      |

### 4.8 Fields Not Yet Frozen as Official WRRA Applications

The author has conducted separate writing and theoretical research in art, aesthetics, and the humanities, but the currently confirmed research lineage contains no independent application frozen as “WRRA-Art,” or under an equivalent name, that implements the Core in an actual model and validation contract. It is therefore excluded from the official Core 1.0 application registry. It may be added after a separate Domain Profile is created.

## 5. Domain-by-Domain Core Mapping

| **Domain**         | **Execution Mapping (SOURCE/RELATION/STATE/BOUNDARY)**                                                                                                       | **COMMON CARRIER**                                            | **PHENOTYPE / RECORD**                                                             |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|------------------------------------------------------------------------------------|
| Physics/cosmology  | Dormant/field SOURCE; laws and interactions; quantum/field state and hidden correlations; spacetime and observational boundary                               | Common transport/carrier                                      | Particles, forces, vacuum, macroscopic Reality / energy, event, and history record |
| Biology            | DNA, molecular stock, environmental input; reaction, regulation, lineage; cellular state and epigenetic residue; membrane, tissue, and generational boundary | Translation, metabolism, membrane transport, and partitioning | Protein, cellular phenotype, fate / molecular ledger and lineage record            |
| AI                 | Sensation, energy, reward; sparse neural/action relations; activation, adaptation, memory, reserve; body/environment/task boundary                           | Sensor–state–action network                                   | Action and survival state / resource and survival history                          |
| Economics          | Shock, policy, flow; credit, price, institutional relations; candidate trust/fear/debt/sentiment residue; market, institutional, regime boundary             | Transaction, price, credit, and information network           | Price, transaction, crisis/calm state / balance and regime record                  |
| Meteorology        | Current atmosphere/cyclone state; physical flows and interactions; candidate compressed history/residue; analysis-region/environment boundary                | Atmospheric-state transport                                   | Track, intensity, structure / best-track and history ledger                        |
| Mathematics/method | Problem, axioms, input; definitions and operations; current computation and proof record; domain, precision, and proof scope                                 | Transformation/inference rule                                 | Computed result and proof state / proof and computation ledger                     |

## 6. Minimum Conformance Conditions for the WRRA Name

> **• Do not identify SOURCE with OBSERVABLE/PHENOTYPE.**
>
> **• When effects of the past are required, declare their owner in the current STATE/RESIDUE/RECORD.**
>
> **• Do not assume that more relations always make a better model. If a null or simpler baseline wins, reduce the WRRA extension.**
>
> **• Where possible, reuse a common carrier across channels without erasing channel identity or ownership.**
>
> **• The objective of minimum computation is not peak performance but the minimally sufficient structure that satisfies the declared viability/expression contract.**
>
> **• Include the BOUNDARY and external inflow/outflow in the ledger. Do not enforce internal-only conservation on an open system.**
>
> **• Do not omit the RENDERER and call an internal variable a phenotype/observable directly.**
>
> **• Separate the contracts of interpretation, computation, prediction, control, and validation; leave insufficiently supported claims OPEN.**
>
> **• Do not elevate domain-specific equations, constants, or data to universal laws of the Core.**

### 6.1 Core Conformance Checklist

| **ID** | **Question**                                                              | **Verdict**                              |
|--------|---------------------------------------------------------------------------|------------------------------------------|
| C1     | Is SOURCE specified?                                                      | No → WRRA Profile not established        |
| C2     | Are the owners of current STATE and past RESIDUE/RECORD distinguished?    | No → memory claim unclear                |
| C3     | Are the BOUNDARY and external inputs specified?                           | No → ledger/causality incomplete         |
| C4     | Does the common carrier specify what is shared and what remains distinct? | No → carrier axis unmet                  |
| C5     | Does UPDATE generate the next present?                                    | No → not an execution model              |
| C6     | Are RENDERER and PHENOTYPE defined?                                       | No → phenotype axis unmet                |
| C7     | Is there a minimum-computation comparator or null/baseline?               | No → minimality claim unavailable        |
| C8     | Are OBSERVABLE/RECORD/LEDGER specified?                                   | No → validation contract not established |
| C9     | Are failure conditions declared in advance?                               | No → violates fail-closed principle      |

## 7. Version Control and Future Extensions

### 7.1 Changes That Do Not Alter Core 1.0

> **• Reinforcing MCC 2.1 with string-theoretic microphysical materials and discussing 3+1/10D implementation**
>
> **• A change in the verdict for a Life Model or WRRA-Cell after new biological data**
>
> **• Adding a new agent, memory architecture, or reserve mechanism in WRRA-AI**
>
> **• Using improved residue measurements or null baselines in WRRA-Econ/Met**
>
> **• Mapping the Core to a new domain such as art, society, law, or language**

### 7.2 Changes That Require Review of Core 1.x or 2.0

> **• Replacing “minimum sufficiency” with another highest-level objective in the definition of minimum computation**
>
> **• Removing the common carrier from the required axes or replacing it with independent channel-by-channel generation**
>
> **• Removing the phenotype/renderer distinction and redefining internal state as observable**
>
> **• Abandoning the fixed-present principle and adopting a past event list as direct ontology**
>
> **• Ceasing to use ownership, ledger, or fail-closed principles as Core rules**

### 7.3 Standard Template for a New Domain Profile

| **Field**             | **Required Entry**                                           |
|-----------------------|--------------------------------------------------------------|
| Domain name / version | Example: WRRA-Art 0.1                                        |
| Target contract       | Which of interpretation/computation/prediction/control/OPEN? |
| SOURCE                | Current independent inputs and resources                     |
| RELATION / LAW        | Interactions and rules                                       |
| STATE / RESIDUE       | Current state and effects of the past                        |
| BOUNDARY              | Inside/outside and inflow/outflow                            |
| COMMON CARRIER        | Shared transport/update scaffold                             |
| UPDATE                | Equation generating the next present                         |
| RENDERER / PHENOTYPE  | Internal-to-external expression                              |
| OBSERVABLE / LEDGER   | Measurements, conservation/accounting, and records           |
| Minimality baseline   | Simpler null/reference model                                 |
| Failure conditions    | Results that would discard or reduce the WRRA extension      |

## 8. Final Freeze Declaration

WRRA Core 1.0 began in cosmology, but it is not cosmology itself. It does not declare any particular physical law, prime number, string, DNA sequence, neural network, price, or tropical cyclone to be the Core. What it preserves is a common grammar for auditing how reality or a complex system executes the present, what it transports, what it expresses, and what it records.

Within this common grammar, minimum computation locates the minimally sufficient boundary between deficiency and excess. The common carrier reuses transport across different channels without flattening away ownership. Phenotype separates internal possibility or SOURCE from observed reality. The fixed-present principle converts the past into residue/record remaining in the present; ownership and ledger fix who owns what; and the fail-closed principle blocks claims that cross the boundary among explanation, prediction, and validation.

| WRRA Core 1.0 = {Minimum Viable Computation, Common Carrier, Phenotype, Fixed Present, Ownership, Boundary, Renderer, Record/Ledger, Fail-Closed Claims} | (8.1) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Freeze Statement</strong></p>
<p>As of 7 September 2026, WRRA Core 1.0 is frozen under the definitions in this document. All subsequent WRRA applications are treated as Domain Profiles of Core 1.0; the success, failure, or version change of a domain implementation does not automatically require a change to the Core. The Core changes only when one of the three constitutional invariants or the required execution grammar itself changes.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## Appendix A. Application Registry Summary

| **Registry**       | **Scope**                                                                                    | **Representative Version**          | **Current Status**                       |
|--------------------|----------------------------------------------------------------------------------------------|-------------------------------------|------------------------------------------|
| WRRA-Physics / MCC | Cosmos, forces, matter, quantum phenomena, vacuum, black holes, condensed matter, and nuclei | MCC 2.0/2.1 and Physics series      | Active                                   |
| WRRA-Math / WJNS   | Arithmetic SOURCE/RELATION and RH/proof boundary                                             | WRRA 2.0 upstream branch            | Research line                            |
| WRRA-Bio           | DNA→protein→cell→lineage→first life; epigenetic memory/fate                                  | Life 0, I–X; Integrated Biology 4.x | Active                                   |
| WRRA-Cell          | Cellular present residue / gene perturbation                                                 | 0.1–0.4                             | OPEN / falsification-oriented            |
| WRRA-AI            | Minimum computation, memory, reserve, survival, luck, and inheritance                        | Integrated AI 2.0                   | Active                                   |
| WRRA-Worm          | C. elegans-inspired embodied agent                                                           | 0.1–1.0 lineage                     | Feasibility; superiority not established |
| WRRA-Econ          | Animal spirits / economic residue                                                            | 0.1–0.5                             | Partial signal / measurement OPEN        |
| WRRA-Met           | Tropical-cyclone residue / track prediction                                                  | 0.1–0.5 research line               | Effect not established                   |
| WRRA-Method        | Interpretation–prediction–computation boundary                                               | v1.0 / v2.1                         | General methodology                      |
| WRRA-Art           | —                                                                                            | No official Domain Profile          | Not frozen                               |

## Appendix B. Representative Frozen Documents in the Application Lineage

Minimal Computing Cosmology 2.0 / WRRA-Physics final architecture.

WRRA 2.0: Prime-Port Fixed-Present Relational Architecture — upstream redefinition and downstream impact.

WRRA Integrated Biology 4.0/4.1 — DNA, protein execution, minimal cells, lineage, origin of life, epigenetic memory and cell differentiation.

WRRA Life Model 0 — The First Living System in WRRA.

WRRA-Cell 0.1–0.4 Integrated Research Paper.

WRRA Artificial Intelligence 2.0 — Minimal Computation, Memory, and Survival; WRRA-Worm 0.1–1.0 lineage.

WRRA-Econ 0.1–0.5 Freeze Report.

WRRA-Met Typhoon Track Residue Hypothesis frozen research note.

WRRA Interpretation–Prediction Boundary v1.0 / Full Formal System v2.1.

WRRA Physics notes on antimatter, vacuum/pair processes, superfluidity, nuclear stability/decay and related physicalization studies.

# Entropy for Automaton

### Entropy for Automaton Driven by Energy Gradient Driving Rule

This work presents an automaton model where energy flows from higher to lower neighboring nodes in discrete quanta. A multiplicative entropy S = ∏ mᵢ provides a high-resolution, non-statistical entropy coordinate that updates with every single energy transfer, driven by an explicit local gradient rule.

Keywords: Multiplicative entropy, automaton, energy gradient, discrete entropy, thermodynamic arrow of time, least action principle, maximum entropy path.

Model link:

latest version :Zou, Z. K. (2026). Demystifying Time, Entropy, Causality, Gravity, and Space in Energy-Gradient-Driven Computational Universe. Zenodo. https://doi.org/10.5281/zenodo.20678065

Previous versions: Zou, Z. K. (2025). The Thermodynamic Arrow of Time in a Double-Layer Topology-Invariant Chiral Space with Geometric (GR) and Gauge (QFT) Degrees of Freedom :Time-Entropy Mapping; Mass-Gravity Duality; Metric-Frequency Mirroring. Preprints. https://doi.org/10.20944/preprints202505.0270.v12

### Advantages of Energy-Gradient Entropy in  Automata

This entropy formulation aligns perfectly with the energy-gradient driving rule—energy flows strictly from higher to lower neighbors in Planck quanta, with explicit local update rules and clear physical intuition. The multiplicative entropy S = ∏ mᵢ is non-statistical and high-resolution, assigning a unique entropy coordinate to every single transfer step, precisely tracing irreversible evolutionary trajectories. Its logarithmic equivalence to Boltzmann entropy ensures macroscopic thermodynamics emerges naturally. Energy conservation is automatic, the Second Law holds exactly.

Crucially, the automaton's node degrees of freedom are well-defined: resonance, spin, axial rotation, and inter-node spacing–tensor modulation. By defining spacing and tensor configurations between SEQ nodes, gravitational dynamics can be simulated in a manner analogous to numerical relativity. Moreover, since mass is understood as local spatial compression curvature, both mass and gravity are represented purely as geometric deformations of the graph. The geometry–frequency mapping proposed by the model further establishes a direct correspondence between geometric deformation and node degrees of freedom, enabling a unified, computable bottom-up framework for modeling the universe.

### 1. The Automaton Framework

1.1 System Definition
Consider a closed system consisting of N nodes (Space Elementary Quanta, SEQ) arranged in a topologically fixed 3D network. The network's adjacency relations never change—no links are broken or created. Each node i carries an energy value:

mᵢ ∈ ℕ, mᵢ ≥ 1

where each unit represents one quantum of Planck's constant h. The total energy of the system is conserved:

Eₜₒₜₐₗ = Σᵢ₌₁ᴺ mᵢ = constant

1.2 Update Rule
Energy transfer occurs between adjacent nodes i and j if and only if:

mᵢ > mⱼ + 1

When this condition holds, one quantum of energy transfers:

mᵢ → mᵢ − 1, mⱼ → mⱼ + 1

Key properties of the update rule:

Energy conservation — The total sum Σ mᵢ remains invariant.

Irreversibility — Energy never flows from lower to higher values.

Locality — Transfers occur only between adjacent nodes.

Quantization — Transfers occur in discrete units of h.

When multiple transfer paths exist, the system preferentially selects the path with the maximum energy gradient—i.e., the largest difference mᵢ − mⱼ. This corresponds to the maximum local entropy increase rule.

### 2. Multiplicative Entropy

2.1 Definition
For a system state defined by the energy distribution {m₁, m₂, ..., m_N}, the multiplicative entropy is:

S = ∏ᵢ₌₁ᴺ mᵢ

This is the product of all node energies.

2.2 Properties
Property	Expression
Energy conservation	Σ mᵢ = constant
Entropy maximum	Achieved when all mᵢ are equal
Monotonic increase	ΔS > 0 for every allowed transfer
Logarithmic relation	ln S aligns with Boltzmann entropy
2.3 Proof of Entropy Increase
Consider an energy transfer from node a to node b, where:

mₐ = A, m_b = B, A > B + 1

Before transfer:

S₁ = A · B · ∏ᵢ₌₁,ᵢ≠ₐ,ᵇᴺ mᵢ

After transfer:

S₂ = (A − 1)(B + 1) · ∏ᵢ₌₁,ᵢ≠ₐ,ᵇᴺ mᵢ

The entropy ratio is:

S₂/S₁ = (A−1)(B+1) / (A·B) = 1 + (A − B − 1) / (A·B) > 1

Since A > B + 1, we have A − B − 1 > 0, hence:

S₂ > S₁

Therefore, every allowed energy transfer strictly increases the multiplicative entropy.

### 3. Entropy as Time

3.1 The Mapping
In this automaton, each system update corresponds to:

One network transformation → One entropy value → One moment in time

Global time is defined as the counting of these discrete entropy-increasing steps.

3.2 Local Time
For a localized region of the network, local time is defined by the number of transformations occurring within that region. When a region is compressed or stretched (via gravitational effects), its transformation frequency is modulated—this gives rise to time dilation phenomena.

3.3 Entropy Ceiling
The maximum possible entropy occurs when energy is uniformly distributed:

mᵢ = Eₜₒₜₐₗ / N for all i

At this state:

Sₘₐₓ = (Eₜₒₜₐₗ / N)ᴺ

No further energy transfers are possible, and the system has reached thermodynamic equilibrium.

### 4. Entropy and Action

4.1 Action as Count of Transfers
In this framework, action is defined as the total number of energy transfers required for a physical process:

𝒜 = Σᵢ kᵢ · h

where kᵢ is the number of times the i-th node participates in energy conduction.

4.2 Least Action Principle
The principle of least action corresponds to:

Nature selects the path that requires the fewest energy transfers to reach the final state.

This is equivalent to selecting the path of maximum cumulative entropy increase per update step.

### 5. Maximum Entropy Path Selection

5.1 Local Rule
When a node i has multiple lower-energy neighbors, the system prefers transferring to the neighbor with the lowest energy (largest gradient).

Example: For node i with energy A, and neighbors j (energy B) and k (energy C), where A > B > C:

Path i → k yields greater entropy increase than i → j.

S_{i→k} > S_{i→j} because the gradient is larger.

5.2 Non-Uniqueness
The maximum gradient path is not necessarily unique. Multiple paths may yield the same immediate entropy increase. This non-uniqueness gives rise to:

Quantum probability — the system explores multiple paths in parallel.

Degrees of freedom in the future — evolution is quasi-deterministic, not strictly deterministic.

### 6. Entropy as the Second Law

6.1 Spontaneous Entropy Theorem
For every possible energy transfer process in this automaton:

ΔS ≥ 0

Equality holds only when no transfer is possible (thermal equilibrium).

6.2 Causality
The entropy increase direction defines the arrow of time. The Second Law is not a statistical tendency but an exact mathematical consequence of the local update rule.

#### Quantum State

A quantum state is a mathematical description of a quantum system. It represents all possible information about the system. In a qubit (quantum bit), the state can be represented as:

**|ψ⟩ = α|0⟩ + β|1⟩**

where α and β are complex amplitudes with the normalization condition: |α|² + |β|² = 1

- **|0⟩ and |1⟩**: Basis states (computational basis)
- **|α|²**: Probability of measuring state |0⟩
- **|β|²**: Probability of measuring state |1⟩

#### Measurement Postulate

Measurement is a fundamental operation in quantum mechanics. When we measure a quantum state:

1. The quantum state **collapses** to one of the basis states
2. The outcome is **probabilistic** based on the amplitudes
3. After measurement, the state is in the measured eigenstate
4. **Repeated measurements** on the same prepared state yield the same result (no further collapse)

#### Measurement Basis

A measurement basis is a set of orthogonal quantum states used to measure a quantum system. Common bases include:

- **Computational (Z) Basis**: {|0⟩, |1⟩}
- **Hadamard (X) Basis**: {|+⟩, |-⟩} where |+⟩ = (1/√2)(|0⟩ + |1⟩) and |-⟩ = (1/√2)(|0⟩ - |1⟩)
- **Y Basis**: Related to phase information

#### Superposition

Superposition is a fundamental principle where a quantum system can exist in multiple states simultaneously until it is measured. Unlike classical bits, qubits can be in a linear combination of basis states.

#### Wave Function Collapse

When a measurement is performed:

- The quantum system's wave function "collapses" from a superposition to a definite state
- The outcome depends on the measurement basis chosen
- The result is non-deterministic but follows probabilistic rules given by Born's rule

#### Measurement Statistics

**Key Statistical Concepts:**

##### Probability Distribution

The probability of measuring state |k⟩ is given by the squared amplitude:

**P(k) = |⟨k|ψ⟩|²**

##### Expected Value (Expectation)

For a quantum observable O:

**⟨O⟩ = ⟨ψ|O|ψ⟩**

##### Variance

Measures the spread of measurement outcomes:

**Var(O) = ⟨O²⟩ - ⟨O⟩²**

##### Standard Deviation

**σ = √(Var(O))**

---

#### Key Takeaways

1. **Measurement Collapses Superposition**: A quantum state in superposition collapses to a definite state upon measurement
2. **Probabilistic Nature**: Individual measurements are random, but statistical patterns emerge over many trials
3. **Basis Dependency**: Measurement outcomes depend on the chosen basis
4. **Born Rule**: Probability of outcome is proportional to squared amplitude
5. **Simulation Importance**: Repeated measurements in simulations reveal quantum probability distributions
6. **Statistics from Ensembles**: Understanding quantum mechanics requires analyzing statistical data from many measurement runs

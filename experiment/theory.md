<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

#### Quantum State

A quantum state is a mathematical description of a quantum system. It represents all possible information about the system. In a qubit (quantum bit), the state can be represented as:

$$
|\psi\rangle = \alpha|0\rangle + \beta|1\rangle
$$

where $$\alpha$$ and $$\beta$$ are complex amplitudes with the normalization condition:

$$
|\alpha|^2 + |\beta|^2 = 1
$$

- $$|0\rangle \text{ and } |1\rangle$$: Basis states (computational basis)
- $$|\alpha|^2$$: Probability of measuring state $$|0\rangle$$
- $$|\beta|^2$$: Probability of measuring state $$|1\rangle$$



#### Measurement Postulate

Measurement is a fundamental operation in quantum mechanics. When we measure a quantum state:

1. The quantum state **collapses** to one of the basis states  
2. The outcome is **probabilistic** based on the amplitudes  
3. After measurement, the state is in the measured eigenstate  
4. **Repeated measurements** on the same prepared state yield the same result (no further collapse)  



#### Measurement Basis

A measurement basis is a set of orthogonal quantum states used to measure a quantum system. Common bases include:

- **Computational (Z) Basis**:

$$
\{|0\rangle,\ |1\rangle\}
$$

- **Hadamard (X) Basis**:

$$
\{|+\rangle,\ |-\rangle\}
$$

where

$$
|+\rangle = \frac{1}{\sqrt{2}}(|0\rangle + |1\rangle)
$$

$$
|-\rangle = \frac{1}{\sqrt{2}}(|0\rangle - |1\rangle)
$$

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

The probability of measuring state $$|k\rangle$$ is given by:

$$
P(k) = |\langle k|\psi\rangle|^2
$$



##### Expected Value (Expectation)

For a quantum observable $$O$$:

$$
\langle O \rangle = \langle \psi|O|\psi \rangle
$$



##### Variance

Measures the spread of measurement outcomes:

$$
\text{Var}(O) = \langle O^2 \rangle - \langle O \rangle^2
$$



##### Standard Deviation

$$
\sigma = \sqrt{\text{Var}(O)}
$$





#### Key Takeaways

1. **Measurement Collapses Superposition**: A quantum state in superposition collapses to a definite state upon measurement  
2. **Probabilistic Nature**: Individual measurements are random, but statistical patterns emerge over many trials  
3. **Basis Dependency**: Measurement outcomes depend on the chosen basis  
4. **Born Rule**: Probability of outcome is proportional to squared amplitude  
5. **Simulation Importance**: Repeated measurements in simulations reveal quantum probability distributions  
6. **Statistics from Ensembles**: Understanding quantum mechanics requires analyzing statistical data from many measurement runs  
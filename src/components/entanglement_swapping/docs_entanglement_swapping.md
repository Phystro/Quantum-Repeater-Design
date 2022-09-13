
# Entanglement Swapping

> __[Demonstration of Entanglement Purification and Swapping Protocol to Design Quantum Repeater in IBM Quantum Computer](https://arxiv.org/abs/1712.00854)__

Consider entanglement swapping between two repeater stations. This consideration requires 3 parties; Alice, Bob and Charlie.

Consider the setup as: Alice -> Charlie -> Bob

Charlie is the intermediary repeater station between Alice and Bob. Swapping happens at Charlie.

There are two entangling pairs of qubits: A0 - C0 and B0 - C1; where:

* A0 = Alice
* B0 = Bob
* C0 = Charlie
* C1 = Charlie

Entanglement production: produces pairs; A0 - C0 and B0 - C1.

Each entanglement pair was entangled by the Bell-state $\ket{\psi^+} = \frac{1}{\sqrt{2}} (\ket{00} + \ket{11})$

Initially, A0 and C0 are entagled (Alice and Charlie) ; B0 and C1 are entangled (Charlie and Bob).

After __swapping__, Alice A0, and Bob B0, get entangled. Charlie's C0 and C1 get entangled. Therefore, Alice and Bob get entangled, and Charlie's two initially unrelated qubits also get entangled.

```
Title: Optimized Entanglement Purification
Type: Journal
Source: https://quantum-journal.org/papers/q-2019-02-18-123/
```

[Optimized Entanglement Purification](https://quantum-journal.org/papers/q-2019-02-18-123/)


---

Investigate novel protocols for entanglement purification of qubit Bell pairs, employing genetic algorithms for design of purification circuit - obtaining shorter circuits, achieving higher success rates and better final fidelities.

---


> __Genetic Alogrithms__: method for solving constrained and unconstrained optimization problems that is based on natural selection. An adaptive heuristic algorithm.

Purification of the enetanglement resource will be necessary before successfully employing it for fault-tolerant quantum communication or computation.

__Various purification protocols have been proposed:__
* [Minimally complex ion traps as modules for quantum communication and computing](https://doi.org/10.1088/1367-2630/18/10/103028) - Nigmatullin, 2016
* [Topological quantum computing with a very noisy network and local error rates approaching one percent](https://doi.org/10.1038/ncomms2773) - Nickerson, 2013
* [Quantum repeaters based on entanglement
purification.](https://doi.org/10.1103/physreva.59.169) - Dür,1999
* [Freely scalable quantum technologies using cells of 5-to-50 qubits with very lossy and noisy photonic links.](https://doi.org/10.1103/physrevx.4.041041) - Nickerson, 2014
* [Quantum privacy amplification and the security of quantum cryptography over noisy channels.](https://doi.org/10.1103/physrevlett.77.2818) - Deutsch, 1996
* [Purification of noisy entanglement and faithful teleportation via noisy channels.](https://doi.org/10.1103/physrevlett.76.722) - Bennett, 1996
* [Entanglement purification and quantum error correction.](https://doi.org/10.1088/0034-4885/70/8/r03) - Dü, 2007
* [Entanglement purification with double selection.](https://doi.org/10.1103/physreva.80.042308) - Fujii, 2009


__`Problem`__: There is a lack of systematic comparison and optimization of purification circuits, as the number of possible designs increases exponentially with the size of the circuits.

__`Note`__: pay attention to limitations imposed by working with finite hardware resources.

__`Observation`__: Many highly efficient purification schemes in the literature can reach perfect fidelities at high yield in the asymptotic regime. However, such theories neglect imperfections and size limitations of the purification hardware. The imperfections in the local gates and measurements are the limiting factor in real-world hardware.

### Purification of Bell pairs

In purification protocols, Alice and Bob start by sharing a number of imperfect Bell-pairs which they perform local gates and measurements and communicate classically, they obtain a single pair of higher fidelity.

### Conclusions

Performance aspects considered: `fidelity of purified Bell pair`, `success probability` and `circuit length`.


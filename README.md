# Quantum-Repeater-Design

## __Table of Contents__

__[i. Note](#note)__

__[ii. Objectives](#objectives)__

__[1. Quantum Repeater Components](src/components/README.md)__

* [1.1. Bell States](src/components/bell_states/README.md)
* [1.2. Entanglement Swapping](src/components/entanglement_swapping/README.md)
* [1.3. Quantum Teleportation](src/components/teleportation/README.md)
* [1.4. Entanglement Purification](src/components/entanglement_purification/README.md)

__[2. Quantum Repeater](src/qrepeater/README.md)__

* [2.1. Quantum Repeater Implementation](src/qrepeater/README.md)

__[A. Appendix](appendix/README.md)__

* [A.1. Summary Notes](appendix/summary_notes/README.md)
* [A.2. Summary PDFs](appendix/summary_pdfs/README.md)
* [A.3. Resources/Links](resources/README.md)

----

## Note

With a focus on Heralded Quantum Purification (HEP) protocols

We assume that the repeater network operates on optical fibre communication links, though free-space satellite to ground links also employ the same concepts of a quantum repeater.

## Objectives

### Main Objective

To design and implement a modern quantum repeater infrastructure for future quantum communication technologies and teleportation application.

### Specific Objectives

* [x] To design and implement a complete quantum circuit of a quantum repeater whose executions emulate its expected workings and behaviour in a real world quantum network.
  * [x] Bell states preparation component
  * [x] Bell states measurement (BSM) component
  * [x] Entanglement swapping component
    * [x] Quantum teleportation component
  * [x] Entanglement purification component
    * [x] Bennett's protocol
    * [x] Deutsch's protocol
* [ ] Explore various purification strategies to identify the optimum strategy.
  * [ ] After generation/production of Bell Pairs?
  * [ ] After every swap?
  * [ ] After `N` swaps?
  * [ ] At the ends of the nodes?
  * [ ] A suitable combination of various steps?
* [ ] Perform optimizations on the purification circuits and studying the effects of various purification protocols on the overall purification optimization scheme.
  * [ ] Employ different purification protocols on the optimization scheme being utilized.

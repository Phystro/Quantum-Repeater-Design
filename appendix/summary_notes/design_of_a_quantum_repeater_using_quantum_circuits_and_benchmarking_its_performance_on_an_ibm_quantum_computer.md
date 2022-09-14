```
Title: Design of a Quantum-Repeater using Quantum Circuits and Benchmarking Its Performance on an IBM Quantum Computer
Type: Journal
Source: https://link.springer.com/article/10.1007/s11128-021-03189-8
```

[Design of a Quantum-Repeater using Quantum Circuits and Benchmarking Its Performance on an IBM Quantum Computer](https://link.springer.com/article/10.1007/s11128-021-03189-8)

Design of a Quantum-Repeater using Quantum Circuits and Benchmarking Its Performance on an IBM Quantum Computer

## Introduction 

Nearly impossible to transmit entangled photons over large distances whilst preserving their fidelity.

Idea of quantum repeaters is to divide entire link into small segments - the length of each segment being less than attenuation length of the channel.

Entanglement is established between the smaller links. Entanglement swapping protocol used to establish the large scale link.

At each swapping procedure, there might be loss of fidelity due to noise/imperfections; hence the purification process to increase fidelity of entanglement between the nodes.

IBMQ can be used to emulate conditions of a quantum communication channel; hence gauge performance of current quantum communication protocols.

Quantum entanglement distillation - condensing multiple low-fidelity entangled pairs into onr high fidelity pair

Quantum coommunication protcols can serve as a deep benchmark for quantum computers. Quantum repeaters utilise multiple sub-protocols and stresses every physical aspect of the hardware platform.

## Quantum Communication

## Quantum Repeater

Primary operations:

1. Entanglement distriution - creating entangled links between nodes
2. Entanglement purification - creating high fidelity entangled states from several low fidelity states
3. Entangelement swapping - connecting entangled links of adjacent nodes using BSM


### Quantum purification

We are trying to generate a Bell state with higher fidelity from multiple imperfect copies of it by a process known as Quantum purification.

#### Bennett's protocol

At each node, both parties apply CNOT between the two qubits of Bell pair, keeping the qubits of each pair as control and target.

Target qubits are measured in computational basis, and results transmitted over classical channel between nodes. It is heralded.

Resulting state is kept if measurements agree e.g. (00 or 11). Purification is a success.

Challeges:

* initial state must be of the Werner form
* Takes many rounds of purification to obtain a Werner state with fidelity over 99%

#### Deutsch's protocol

State is represented as a Bloch vector in a BLoch sphere. Before aplying CNOT operation, Alice performs an Rx(PI/2) on her qubits and Bob performs an inverse rotation i.e. Rx(-PI/2).

Then we proceed as is Bennett's protocol after. Theoretical increase in fidelity of 100 times more than Bennett's.

#### Multi-qubit entanglement purification

Running the purification on multiple pairs simultaneously.

### Entanglement Swapping

Consider two Bell pairs in combined state: A_12 and A_34. Performing BSM between qubits 2 and 3 projects qubits 1 and 4  into the staet A_14 up to a Pauli correction operation {I, Z, X, Y} depending on measurement result.

Results are sent to node 4 so that correction operation can be performed. The qubit state neing teleported is entangled with another qubit.

#### Recommendations

* Create robust and condense error correcting codes
* co-design hardware specific error-correcting codes, taking into accoutn device architecture of the quantum system.

### Interesting reads/sources

* https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.76.722 - `Purification of Noisy Entanglement and Faithful Teleportation via Noisy Channels`

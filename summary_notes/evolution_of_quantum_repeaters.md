```
Title: 1G, 2G, 3G: Evolution of Quantum Repeaters
Type: Webpage
Source: https://www.aliroquantum.com/blog/1g-2g-3g-evolution-of-quantum-repeaters
```

[1G, 2G, 3G: Evolution of Quantum Repeaters](https://www.aliroquantum.com/blog/1g-2g-3g-evolution-of-quantum-repeaters)

---

For near-term quantum networks, characterised by _high error rates_ aand _short memory times_, quantum repeaters will rely on _entanglement purification_ and _entanglement swapping_.

---

Main sources of errors in quantum networks:
* __Loss errors__: Qubits are lost when travelling on connections
* __Operation errors__: Noisy operations reduce quality of qubits on repeaters and endpoints


Choice of repeater is contexty dependent: dependent on available hardware and bandwidth requirements. The distinction among the three generations is determined by methods of handling errors.

### First Gen

Based on technique called _`heralding`_ to cope with high errors rates and near-term quantum devices. 

A heralding network works by testing performance in real-time and only proceeds when a protocol succeeds. The network sends a classical signal indicating success and thus the network can proceed. This is heralding.

Heralding is used to correct for both errors.
* __Loss errors__: Heralded Entanglement Generation (HEG) ensures succeessful entanglement by repeating attemps until a classical signal confirms entanglement has succeeded. Success signal is sent to bot endpoints to indicate success.
* __Operation errors__: Heralded Entanglement Purification (HEP) takes in several low fidelity entangled pairs to produce a single high fidelity entangled pair, with a classical signal to each end-point indicating success.

##### Pros of Heralding

maintains entanglement generation at high qualities.

##### Cons of Heralding

Costs the networks' __Bandwidth__. Bandiwdth is determined by thre number of entangled pairs that can be generated in a given amount of time.

The heralding messages slows down quantum networks, because each end-point must wait to receive the classical message. Consequently, endpoints in long distances will have lower bandwidth.

### Second Gen

Introduces quantum error correction (QEC). QEC replaces entanglement purification. QEC produces a single high fidelity pair by encoding it in a large number pairs. 

This has impact on rate but without the round-trip classical signalling needed in heraleded entanglement purification. Hence, bandwidth is increased.

QEC requires high-quality hardware, which isn't available in our NISQ era devices.

### Third Gen

It primarily scales the quantum network. QEC is being used to manage loss errors.

Instead of iteratively building entanglement followed by teleportation, qubits can be encoded directly into clusters and passed across a network, eliminating need for heralding.

Hardware requirements are extremely high, but it unlocks the full scaling capability of quantum internet.

### Conclusions

Researchers focusing on developing First Gen quantum repeaters using heralded entanglement generation and purification. 1st Gen repeaters have applications is secure communication and High-Performance Computing (HPC).

### Interesting reads/sources/references

* https://www.aliroquantum.com/blog/3-quantum-repeater-advances-in-2021 - `3 quantum repeater advances in 2021`
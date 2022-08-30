```
Title: Benchmarking of quantum protocols
Type: Journal
Source: https://www.nature.com/articles/s41598-022-08901-x
```

[Benchmarking of Quantum Protocols](https://www.nature.com/articles/s41598-022-08901-x)

---

Quantum network protocols offer new functionalities. However, they are not yet mature enough to be executed in practical settings. To develop such quantum protocols in the real world, it is important to examine their performance considering their practical implementation using simulation platforms.
---

#### Tools
* NetSquid simulation platform - to evaluate the effect of various sources of noise on the performance of these protocols, considering different figures of merit.
* *IBM Qiskit*

### Intro
#### Benchmarking
A major requirement in the dev of quantum protocols in the real world is the evaluation of their performance in various aspects such as security, required resources and scalability. __Such detailed analysis is requred to include different sources of imperfection in the practical implementation__.

Benchmarking helps us compare different protocols with the same functinality proposed in the literature, e.g. different quantum token protocols.

Benchmark against classical and post-quantum protocols with the same funcionlity.


Quantum networks require classical communication for various purposes such as synchronization and control messages. Some quatum protocols consist of intertwined quantum and classical sub-algorithms. In the design of quantum netorks, is it necessary to determine the impact of classical message/sub-algorithms involved in quantum protocols.


#### Approach to benchmarking quantum protocols (methods)
* Investigate their performance considering fixed values for system parameters and desired figures of merit - Helps evaluate effect of specific protocol/hardware parameters and examine the feasibility of practical implementation considering currently achievable parameter values.
* Consider target values for desired figures or merit and determine minimum requirements at the hardware level to achieve them - Helps optimize system parameters and determine  minimum viable requirements to achieve specific target values for figures of merit. (backward benchmarking)


### Conclusion
Performed an in-depth performance analysis for each protocol by use of NetSquid simulation platform.


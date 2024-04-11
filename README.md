**IBM Quantum QRise Challenge -Quantum Coalition 2024**

# :space_invader: IBM Dynamics Circuit Challenge challenge- Team Feynman Prodigies 

- [Team Introduction](#team-introduction)
- [Problem Statement](#ProblemStatement)
  - [Description](#description)
- [Objectives](#Objectives)
- [Installation](#Installation)
- [Software & Tools Used](#software--tools-used)
- [Results](#Results)
- [Future Plans](#future-plans)
- [License](#license)
- [Acknowledgement](#Acknowledgement)
- [References](#references)

## Team Introduction
**Team Name:** Feynman Prodigies 

**Challenge Name:** IBM Challenge
|   **Member Names**| **Abdullah Kazi**                      | **Owais Ishtiaq Siddiqui** | **Jacob Park** |
|----------------|-----------------------------------|----------------------------|-----------------------|
| **Discord ID** | Abdullah K#8200                   | owaisishtiaqsiddiqui#4549  | jacobpark#3597        |
| **GitHub ID**  | AbdullahKazi500                   | owaisishtiaqsiddiqui       | JacobPark1080         |

----------------------


## Problem Statement
![image](https://github.com/owaisishtiaqsiddiqui/QRISE/assets/108402760/514cee08-6a08-4ccd-aa60-583d541c6a2f)

Dynamic Circuit Challenge: Maximizing Performance and Tayloring Noise

## Challenge Description 
Dynamic circuits are an exciting feature of IBM Quantum hardware that incorporates quantum circuits with real-time classical communication. Different from the static counterpart, dynamic circuits can not only implement a set of basic quantum operations like the Hardmard gate, CNOT gate, or qubit reset but also can implement measurement in the middle of a circuit, store the measurement results to classical bits, evaluate classical expressions on the fly, and determine what quantum operation to do next. This capability has a variety of applications, for example, quantum error correction, quantum simulation, and so on. We encourage you to explore what you can do with dynamic circuits in this challenge! Bonus point if you show improvement of your dynamic circuit implementation over its static counterpart - for example, use dynamic circuit feature to shorten the circuit depth, suppress error rate, and so on! After you create a dynamic circuit of your interest and are ready to run it on the hardware, bear in mind that the current quantum computers are noisy! In practical implementation, the operations in a dynamic circuit can be faulty, so it is important to quantify their fidelities and model the noise mechanism on their own or in the context of a circuit. In the case of dynamic circuits, the types of error and how error propagates will be more complicated due to the hybrid quantum and classical nature of noise! We challenge you to characterize the noise in dynamic circuits. Fortunately, there is a suite of noise characterization and verification tools like tomography and randomized benchmarking, which are fairly well understood on static circuits, and extending them to dynamic circuits is an interesting research question to take on.

## Objectives
1. Find an application using dynamic circuits For example:prepare a large GHZ state, generate long-range entanglement, prepare a repetition code, doing quantum phase estimation.
2. Demonstrate the improvement of implantation using the dynamic circuit feature For example: use dynamic circuit feature to shorten circuit depth or suppress error rate in a real circuit execution
3. Characterize noise and errors in dynamic circuits For example, study how error propagates in dynamic circuits: use a benchmark method to study the fidelities of individual operations and composite operations in dynamic circuits
4. With deeper understanding of how noise affects dynamic circuits, could you think of ways to suppress noise?

## Installation
!pip install qiskit 

!pip install qiskit.visualization

!pip install qiskit-aer

!pip install qiskit.opflow

or follow [qiskit migration guide](https://docs.quantum.ibm.com/api/migration-guides/qiskit-opflow-module)

## Results
`Iters. done: 271 [Current cost: -2.3291976432715256]` 

'Calculated Free Energy: -2.3291976432715256'

## software--tools-used
Qiskit, matplotlib, Sampler, M3, 
## Future Work
Improvement in Fidelity of more than 99.6%
## License

<a href="https://choosealicense.com/licenses/mit/"><img src="https://raw.githubusercontent.com/johnturner4004/readme-generator/master/src/components/assets/images/mit.svg" height=40 />MIT License</a>

## Acknowledgement 
We are sincerely thankful to the IBM Quantum members for creating this exciting challenge and especially to the QRISE mentors for letting us be a part of this challenge.

## References
1. https://arxiv.org/pdf/2005.08797.pdf
2. https://arxiv.org/pdf/2312.14139.pdf

QRise IBM Challenge winning team
**IBM Quantum QRise Challenge -Quantum Coalition 2024**
All the important files can be located here Github Directory path to file [Final error mitigation](https://github.com/owaisishtiaqsiddiqui/QRISE/blob/main/FinalErrorMitigation.ipynb), [PPT/Presentation](https://github.com/owaisishtiaqsiddiqui/QRISE/blob/main/QRise_Final_PPT.pdf), [VQE](https://github.com/owaisishtiaqsiddiqui/QRISE/blob/main/VQE_simulation.ipynb), [VQE Dynamic](https://github.com/owaisishtiaqsiddiqui/QRISE/blob/main/VariationQuatumGibbs.ipynb) [QPRC](https://github.com/owaisishtiaqsiddiqui/QRISE/blob/main/VariationQuatumGibbsWithQPRC.ipynb)
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
1. The Project seeks to demonstrate the behavior of gibbs free energy using dynamic mid-circuit measurements.
2. Develop a framework for estimating the free energy of quantum systems using variational quantum algorithms.
3 Implement ansatz parameterization techniques to construct parameterized quantum circuits capable of preparing quantum states relevant to the free energy calculation.
4 Design efficient algorithms for estimating expectation values of Hamiltonians and computing the free energy based on the obtained results.
5 Evaluate the performance of the developed framework through empirical analysis, including benchmarking, optimization,

## Installation
for running this locally

Create a conda environment with the required dependencies mentioned in the package.txt file

`conda env create -n QRISE environement.yml && conda activate QRISE`
you can install the required dependencies via the package.txt file:

`conda create -yn QRISE python==3.9.11 && conda activate QRISE`

`conda update -yn base -c defaults conda && conda install -yc conda-forge pip==22.1.2`

`python3 -m pip install --user --upgrade pip && python3 -m pip install -r Package.txt`

QISKIT Installation:

`!pip install qiskit`

`!pip install qiskit.visualization`

`!pip install qiskit-aer`

`!pip install qiskit.opflow`

or follow [qiskit migration guide](https://docs.quantum.ibm.com/api/migration-guides/qiskit-opflow-module)

## Results
`Iters. done: 271 [Current cost: -2.3291976432715256]` 

'Calculated Free Energy: -2.3291976432715256'
Calculated Free Energy: 1.0 using QPRC
     
Fidelity between ansatz state and ground state: 0.04181839960097066

## software--tools-used
Qiskit, matplotlib, Sampler, M3, 
## Future Work
Improvement in Fidelity of more than 99.6%
Investigate more sophisticated ansatz designs tailored specifically
for the problem at hand. This could involve exploring different
gate sets, parameterization techniques, or deeper circuit
architectures to potentially capture more complex quantum
states and improve the accuracy of results.
• Error Mitigation Techniques:
Implement error mitigation techniques such as error correction
codes, noise-adaptive algorithms, or post-processing methods to
mitigate the effects of noise and errors inherent in current
quantum devices. This could help improve the reliability and
accuracy of calculations, especially on near-term quantum
hardware.
• Scale up the size of the quantum circuits used in calculations to
tackle larger and more challenging problem instances. This
involves optimizing circuit compilation, resource allocation, and
execution strategies to efficiently utilize available quantum
hardware resources.
## License

<a href="https://choosealicense.com/licenses/mit/"><img src="https://raw.githubusercontent.com/johnturner4004/readme-generator/master/src/components/assets/images/mit.svg" height=40 />MIT License</a>

## Acknowledgement 
This work is done as a project for the QRise researchthon
organized by Quantum coalition for the IBM Challenge ,The
Team members would like to thank the organizers Caden and
Benjamin McDonough for their support all throughout the
challenge ,We would also like to Thank Luke Govia and Brian
from the IBM Team for the insightful workshop on dynamic
circuits..

## References
1. https://arxiv.org/pdf/2005.08797.pdf
2. https://arxiv.org/pdf/2312.14139.pdf
3. Quantum Wednesday talk By Misty wahl QPRC

# The-Quantum-Teleportation-Algorithm
In this repository, I have programmed The Quantum Teleportation Algorithm with the help of Qiskit.


-->Quantum Teleportation Algorithm : 
It is an algorithm used to transfer quantum states from one qubit to another. This means that we are transferring information from one qubit to another and not the qubit itself.

-->Why do we use this algorithm ?
In quantum computers, when we try to copy information the quantum state gets collapsed to a single state as we are indirectly applying a measurement. So, to tackle the coplying issue in a quantum computer. We use quantum teleportation.

-->How will we use it ?
In order to implement this algorithm, we will be using Quantum Entanglement as a resource and build a circuit containing 3 qubits(q0,q1 and q2) and 3 classical bits.

-->Aim : To transfer quantum states from q0 to q2 with q1 as a medium.

-->Role of classical bits : To convey the measurements of the quantum operations in a classical computer.


                                          The Quantum Teleportation Circuit
![circuit](https://user-images.githubusercontent.com/77266161/107117307-8e372700-689f-11eb-97ad-c73a5512b8c9.jpg)

-->How will I run the circuit ?
There are many ways to run the algorithm but in this particular case I have used the QASM Simulator to run my circuit and have shown a histogram to convey the results.

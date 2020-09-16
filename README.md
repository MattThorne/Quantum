# Quantum
This repository stores the code for my masters Dissertation project. The aim of the project was to help determine if Bernstein, Biasse and Msoca's low resource quantum factoring algorithm (https://link.springer.com/chapter/10.1007/978-3-319-59879-6_19 )would use less qubits than Shor's algorithm would to factor a common RSA key size such as 2048-bit. To determine this the main quantum component of the BBM algorithm was implemented. The main component is Shor's algorithm run in superposition. This code therefore implements Shor's algorithm in superposition to determine the number of qubits it uses to factor a superposition of n bit numbers.

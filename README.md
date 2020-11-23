# Programming Language  Parallel Simulation of Quantum Stochastic Walks

The goal of final project of CSCI596 is to perform a parallel simulation of quantum stochastic walks

>### Introduction

QSW MPI is a package designed for the efficient time-series simulation of continuous-time quantum stochastic walks on both workstations and massively parallel computers.

It is a parallel distributed-memory implementation of the matrix exponential via a truncated Taylor series expansion with scaling and squaring.

>### Programming Language  

Python 3 + Fortran 2003

>### Method
QSW MPI addresses these limitations by taking a distributed memory approach to the construction of the QSW superoperator and the calculation of system evolution via matrix exponentiation.
A continuous-time quantum walk (CTQW) is constructed by mapping G to an N-dimensional Hilbert space where the set of its vertices form an orthonormal basis. 



>### Results  
##### Figure 1
<img src="https://docs.google.com/uc?id=1vYpaX1G4GNHPjmqegywgpgi0cIdUsw1N" alt="drawing" width="800"/>
Figure 1 examines the difference between L-QSW simulation results obtained using the QSW MPI step method as compared to those obtained with the QSWalk.m package.
##### Figure 2
<img src="https://docs.google.com/uc?id=1m_u1UqnqiAE3VKcvrXTGufm5P1EefPwI" alt="drawing" width="800"/>

The simulation time of the QSW MPI step method is depicted with comparison to QSWalk.m and QSWalk.jl for L-QSWs in Figure 2.

>### Conclusion
> 

QSW MPI provides a means of quantum stochastic walk simulation on graphs and digraphs with many thousands of vertices through the use of MPI parallelism and memory-e cient of sparse data structures. Key

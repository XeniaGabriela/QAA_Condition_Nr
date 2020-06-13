# Condition Number of the Quantum Algebraic Attack on chosen Cryptosystems

On the condition number of the Qantum Algebraic attack by Chen-Gao for chosen cryptosystems

## Objective

This repository documents the work in progress on the investigation of the condition number of the scientific paper
**Quantum Algorithms for Boolean Equation Solving and Quantum Algebraic Attack on Cryptosystems**
by Y.-A.Chen, X.-S.Gao, https://arxiv.org/abs/1712.06239}, 2018.


## History

* In a first step, we looked at the cassical condition number of the globally used symmetric Advanced Encryption Standard AES. 
* The second phase will consist of the explicit generation of the reduced Macaulay matrix of the polynomial system derived from the S-Box and the actual computation of its condition number.
* With the identified mechanisms we will derive the condition number of eAES and other crypto systems.


## Cross References

* eAES code by John Gregory Underhill: ([CEX Crypto Library](https://github.com/Steppenwolfe65/CEX))
* eAES mathematical analysis wrt. Grover's Search by Xenia Bogomolec: ([eAES_post-quantum_math_analysis](https://github.com/XeniaGabriela/eAES_post-quantum_math_analysis))

Scientific references used for the computation of the condition number see the refrences in the ([Official Paper](
https://github.com/XeniaGabriela/QAA_Condition_Nr/blob/master/official_paper/QAA_on_AES_paper.pdf)) on the Complexity of the Quantum Algebraic Attack on AES.

## Contributers
* [Dr. Peter Nonnenmann](https://www.linkedin.com/in/peter-dr-nonnenmann-737857a0/): Core Analysis, see [his original paper](https://github.com/XeniaGabriela/QAA_Condition_Nr/tree/master/results_nonnenmann_rump)
* [Xenia Bogomolec](https://www.linkedin.com/in/xenia-bogomolec-532981a6/): Context explanation wrt. Applied Cryptography, Industry and Algebraic Geometry

With the friendly essential support of 
* Prof. Dr. Siegfried Rump (Head of the Institute for for Reliable Computing, TU Harburg)
* Christoph Stockhammer, MathWorks
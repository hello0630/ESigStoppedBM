#  Expected Signature of stopped Brownian motion

 This is the code repository of the paper entitled "Expected signature of stopped Brownian motion on <img src="https://render.githubusercontent.com/render/math?math=%24d%24"> -dimensional <img src="https://render.githubusercontent.com/render/math?math=%24C%5E%7B2%2C%20%5Calpha%7D%24">-domains has finite radius of convergence everywhere: <img src="https://render.githubusercontent.com/render/math?math=%242%20%5Cleq%20d%20%5Cleq%208%24">". The codes are implemented in Maple2020.

## Overview
In this paper, we prove that on any bounded <img src="https://render.githubusercontent.com/render/math?math=%24C%5E%7B2%2C%20%5Calpha%7D%24">-domain <img src="https://render.githubusercontent.com/render/math?math=%24%5COmega%20%5Csubset%20%5CR%5Ed%24"> with <img src="https://render.githubusercontent.com/render/math?math=%242%5Cleq%20d%20%5Cleq%208%24">, the expected signature of the stopped Brownian motion has finite radius of convergence everywhere. %This provides a complete solution to the question of finiteness for the radius of convergence in dimension 2. 
A key ingredient of our proof is the introduction of a ``domain-averaging hyperbolic development'', which allows us to symmetrize the PDE system for the hyperbolic development of expected signature by averaging over rotated domains. 

## Directory Layout 
 ### A top-level directory layout
    .
    ├── pdf                     # Pdf files generated by Maple codes in src
    ├── src                     # Maple souce code files 
    └── README.md
### Source files
    .
    ├── ...
    ├── src
        ├── 1_numerator_d=2_domain.mv                     # Section 5: Proof of Theorem 1.1: <img src="https://render.githubusercontent.com/render/math?math=%24d%20%3D%202%24">
        ├── 2_CheckSolutionGeneralDomain.mv               # Section 6: Proof of Theorem 1.1: <img src="https://render.githubusercontent.com/render/math?math=%24%203%20%5Cleq%20d%20%5Cleq%208%24"> 
        ├── 3_denominator_final.mv                        # Section 6: Proof of Theorem 1.1: <img src="https://render.githubusercontent.com/render/math?math=%24%203%20%5Cleq%20d%20%5Cleq%208%24"> 
        ├── 4_numerator_general_d_ball.mv                 # Section 6.1: Proof of Theorem 6.8: a <img src="https://render.githubusercontent.com/render/math?math=%24d%24">-dimensional unit ball  
        ├── 5_numerator_general_d_domain.mv               # Section 6.2: Proof of Theorem 1.1 <img src="https://render.githubusercontent.com/render/math?math=%24%203%20%5Cleq%20d%20%5Cleq%208%24">
        ├── 6_CheckSolutionGeneralDomain_d=9.mv           # Lemma A.3
        └── 7_Example_d=7.mv                              # An example to show the finite ROC of stopped BM up to the first exit time from a general <img src="https://render.githubusercontent.com/render/math?math=%24d%24">-dim regular domain.

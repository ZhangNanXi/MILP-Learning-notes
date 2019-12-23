# MILP-Learning-notes
This is a learning notes of reading materials on MILP books and slides. The reference files will be provided later.
IP problems are usually linked with NP-hard problems, thus the computational complextity of this kind of problem is usually high. On the 
other hand, this is also a powerful tool to build modelings. The following thm provide a result on what kind of problems can be modeled by 
MILP.
**Representability Theorem** A set $F$ is $MILP$ representable iff there exist rational polytopes $P_1,...P_k$ and vectors $r^1,...r^t\in Z^n$ such that $F=\cup_{i=1}^k(P_i+intcone(r^1,...r^t))$. Here intcone stands for integer cone($intcone(X)=\{\lambda_1x_1+...+\lambda_tx_t|t\geq 0,x_1,...,x_n\in X,\lambda_i\in Z_+\}$)

# Definition

The berry phase doesn't depend on time. It is purely geometrical and depends on the geometry of the parameter space. (As long as the adiabatic approximation is valid, it does't depend of the velocity of the path)

Time reversal is anti-linear (It is primarely an anti-unitary opperator)

p.7 : Adiabatic means that the system deos not jump from one energy state to another spontaneously (the time variation of the hamiltonian is solw enough to let the system continuosly adjust to the eigenstates of the instantaneous hamiltonian). 

The berry phase is explored by letting the hamiltonian vary trough time. Usually the continuous parameter(s) on which the hamiltonian depends are stored in a finite dimentionnal matrix representation of the hamiltonian as variables for the entries. Letting an eigen state with a given continuous parameter evolve with time on a path in continuous parameter space will force the systeme to countinuoulsy adjust to the new local eigenstates of the matrix. This adjustment is associated with a dynamical phase factor (change of time) and a Berry phase factor (change of eigen state with time). This is a way to introduce the berry phase but is not the only manifestation of the berry phase. It concerns the time evolution of a system but, in general, it is a goemetrical quantity that does not depend on the way a path in continous parameter space is traversed.  


Perturbation theory approach of the berry phase: Taylor expand the hamiltonian around a given continuous parameter $k_0$ and the apply time independant perturbation theory to obtain the correction on the state if the hamiltonian is varied this way. This will yield (p.12-13) a connection between an eigenstate with $k_0$ and one near it. 


p.18: The time reversal antiunitary operator is the complex conjugation operator when it acts in the position basis without spin. We can see that it transforms a spin $|+\rangle_y$ into a $|-\rangle_y$ with the following spinor notation:
$$
\left(\frac{1}{\sqrt{2}}\left(\begin{array}{l}
1 \\
i
\end{array}\right)\right)^{\star} = \frac{1}{\sqrt{2}}\left(\begin{array}{l}
1 \\
-i
\end{array}\right)
$$
To ensure the $x$ and $z$ components are also reversed with the time inversion operator a $i s_y$ is added to complex conjugation. This addition inverses $x$ and $z$ spin states. The resulting operator doesn't square to $1$, it squares to $-1$ and this is the cornerstone of kramers theorem. 


[Berry](https://arxiv.org/pdf/1804.06471.pdf)


https://www.phys.ens.fr/spip.php?article2799
classifying phases of matter. 

topological deffects 

quantum hall effect first example of topological insulator

conclusion on the usage for quantum computing 
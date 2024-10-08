# Distinguishing-Orthogonal-States

**For 1**

Input: A qubit which is guaranteed to be in either the $\ket {\psi_+}$ or the $\ket{\psi_-}$ state, where $\ket {\psi_+} = 0.6\ket 0 + 0.8 \ket 1$ and $\ket {\psi_-} = -0.8\ket 0 + 0.6 \ket 1$.

Output: true if the qubit was in the $\ket {\psi_+}$ state, or false if it was in the $\ket {\psi_-}$ state. The state of the qubit at the end of the operation does not matter.

**For 2**

Inputs: Angle $\alpha$, in radians, represented as a Double. A qubit which is guaranteed to be in either the $\ket{A}$ or the $\ket{B}$ state, where $\ket{A} = \cos \alpha \ket{0} - i \sin \alpha \ket{1}$ and $\ket{B} = - i \sin \alpha \ket{0} + \cos \alpha \ket{1}$.

**For 3**
 Inputs:

1. Angle $\alpha$, in radians, represented as a Double.

2. A qubit in some unknown state.


Output: Implement a measurement in the $\{\ket A, \ket B\}$ basis. Same as in the previous exercise, $\ket{A} = \cos \alpha \ket{0} - i \sin \alpha \ket{1}$ and $\ket{B} = - i \sin \alpha \ket{0} + \cos \alpha \ket{1}$. Return Zero if the measurement outcome is $A$, and One if the outcome is $B$. The state of the qubit after the measurement should correspond to the measurement result.

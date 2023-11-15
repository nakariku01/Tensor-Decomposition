# Tensor-Decomposition
## Canonical polyadic decomposition
* テンソルをクロネッカー積の和で表現する．
### Kronecker product
* AをM行N列，BをQ行P列とすると，クロネッカー積A⊗Bは
  ```math
  A\otimes B = 
  \begin{pmatrix}
  A_{11}B_{11} & A_{12}B_{12}& \cdots & A_{1N}B_{1P}\\
  A_{21}B_{21} & A_{22}B_{22}& \cdots&A_{2N}B_{2P}\\
  \vdots & \vdots&\ddots&\vdots\\
  A_{M1}B_{Q1}  & A_{M2}B_{Q2}& \cdots & A_{MN}B_{QP}
  \end{pmatrix}
  ```
##

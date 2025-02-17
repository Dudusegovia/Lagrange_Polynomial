# Lagrange_Polynomial
Polinômios de Lagrange

Este projeto implementa a interpolação polinomial de Lagrange, um método numérico para encontrar um polinômio que passe por um conjunto de pontos dados.

A interpolação de Lagrange é usada para encontrar um polinômio interpolador que passe por um conjunto de pontos dados. Esse método é amplamente utilizado em matemática numérica e engenharia para aproximação de funções desconhecidas.

# Teoria

Dado um conjunto de pontos (X0, a0), (X1, a1), ..., (Xn, an), o polinômio interpolador de Lagrange é definido como:

![image](https://github.com/user-attachments/assets/aa676a39-b2e0-4d23-b7d7-cfbdc6a73f45)

## p ( x ) = a 1 L 1 ( x ) + a 2 L 2 ( x ) + ⋯ + a n L n ( x ) = ∑ k = 1 n a k L k ( x ) 

onde  são os polinômios de base de Lagrange dados por:

![image](https://github.com/user-attachments/assets/baa53ada-b9d2-43a9-b0ce-bda7df1ab006)

![image](https://github.com/user-attachments/assets/9e7de260-6239-4632-87a9-037d70d3aeb2)

![image](https://github.com/user-attachments/assets/de5c61c3-e8c1-42f5-bdff-fc21214f8088)



Esse polinômio passa exatamente pelos pontos fornecidos.

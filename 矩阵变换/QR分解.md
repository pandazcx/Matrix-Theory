# 定义
1.实（复）非奇异矩阵A能够分解成正交（酉）矩阵Q与正线上三角矩阵R的乘积，即$A=QR$，称为A的QR分解，且分解是唯一的。[[满秩矩阵]]
2.设A是$m\times n$实（复）矩阵，且其n个列线性无关，则A有分解$A=QR$，其中Q是$m\times n$实（复）矩阵，且满足$Q^TQ=I(Q^HQ=I)$，其中R为n阶的正线上三角。[[三角矩阵]]、[[正交矩阵与酉矩阵]]
# 分解方法

Schmidt正交化法能保证分解出来的R是正线上三角，剩下两种方法分解出来的可能不是。
## 1. Schmidt正交化法
（对于复数向量，下图中的$k_{ij}=\frac{(b_j,a_i)}{(b_j,b_j)}$）
![[Pasted image 20231214204148.png|500]]
![[Pasted image 20231214204202.png|500]]
![[Pasted image 20231214204241.png|500]]




## 2. 初等旋转变换 (Givens) 法
任何n阶实非奇异矩阵都可以通过左乘有限个初等旋转矩阵化为上三角矩阵。
1. 首先介绍如何用Givens变换将任意向量化为单位向量的表示：
![[Pasted image 20231216184941.png|550]]
![[Pasted image 20231216184953.png|550]]
![[Pasted image 20231216185013.png|550]]
2. 然后介绍如何用Givens变换进行LR分解：
![[Pasted image 20231216185054.png|550]]
为什么$det A^{(1)}\ne 0$，由于$T_1$是正交矩阵，满秩、$A$是满秩矩阵，因此$det T_1A=a_{11}^{(1)}det\ A^{(1)}\ne 0$。
![[Pasted image 20231216190804.png|550]]
![[Pasted image 20231216192053.png|550]]
![[Pasted image 20231216192137.png|550]]

## 3. Householder法
任何实非奇异矩阵$A\in R^{n\times n}$，可以通过左乘有限个Householder矩阵化为上三角矩阵。方法跟Givens法类似。
![[Pasted image 20231216201547.png|550]]
![[Pasted image 20231216201558.png|550]]
![[Pasted image 20231216201611.png|550]]
![[Pasted image 20231216201649.png|550]]

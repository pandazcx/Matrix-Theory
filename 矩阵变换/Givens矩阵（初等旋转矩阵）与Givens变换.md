# 定义
Givens矩阵又称初等旋转矩阵，可记作$T_{i,j}=T_{i,j}(c,s)$，由Givens矩阵确定的变换称Givens变换（初等旋转变换)。
![[Pasted image 20231214205330.png|575]]
# 性质
1. Givens矩阵是正交矩阵，且有$[T_{i,j}(c,s)]^{-1}=[T_{i,j}(c,s)]^{T}=[T_{i,j}(c,-s)]$。[[正交矩阵与酉矩阵]]
2. $det\ T_{i,j}(c,s)=1$
3. **设$x=(\xi_1,\xi_2,...,\xi_n)^T\ne 0$，则存在有限个Givens矩阵乘积，记作T，使得：$Tx=\left | x \right | e_1,where\ e_1=(1,0,...,0)^T$.**
4. **设非零列向量$x\in R^n$及单位列向量$z\in R^n$，则存在有限个Givens矩阵的乘积T，使得$Tx=\left | x \right | z$**
5. 任何n阶实非奇异矩阵都可以通过左乘有限个初等旋转矩阵化为上三角矩阵。[[QR分解]]
6. Givens矩阵是两个Householder矩阵的乘积。[[Householder矩阵（初等反射矩阵）与Householder变换]]
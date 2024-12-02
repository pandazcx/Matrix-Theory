# 定义
设单位向量$u\in R^n$，称$H=I-2uu^T$为Householder矩阵，即初等反射矩阵，由Householder矩阵确定的变换成为Householder变换。
![[Pasted image 20231216194605.png|550]]

# 性质
1. Householder矩阵是正交矩阵，且$H^T=H^{-1}=H$，$H^2=I$（对合矩阵）。[[正交矩阵与酉矩阵]]
2. $det \ H = -1$。
3. 任意给定非零列向量$x\in R^n(n>1)$及单位列向量$z\in R^n$，则存在Householder矩阵H，使得$Hx=\left|x\right|z$
![[Pasted image 20231216200906.png|550]]
4. 任何实非奇异矩阵$A\in R^{n\times n}$，可以通过左乘有限个Householder矩阵化为上三角矩阵。[[QR分解]]
5. 对于Householder矩阵$H_i$，
![[Pasted image 20231216201508.png|550]]
6. Givens矩阵是两个Householder矩阵的乘积。[[Givens矩阵（初等旋转矩阵）与Givens变换]]



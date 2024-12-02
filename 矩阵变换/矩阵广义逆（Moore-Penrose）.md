
# 定义
![[Pasted image 20231223203945.png|600]]
能产生15类广义逆。
![[Pasted image 20231223204107.png|600]]

# 存在与唯一性
![[Pasted image 20231223204147.png|600]]
一般来说，其余各类逆矩阵都不唯一。
![[Pasted image 20231223204919.png|600]]
# 求$A^+$广义逆
## 1. 奇异值分解法
设$A\in C_r^{m\times n}, \ (r>0)$，对A进行奇异值分解[[奇异值分解]]：$A=U\begin{pmatrix}S_r & 0\\0  & 0\end{pmatrix}V^H$，其中，U和V分别为m和n阶酉矩阵。
则$A^+=V\begin{pmatrix}S_r^{-1} & 0\\0  & 0\end{pmatrix}U^H$。
（$S_r$是对角矩阵，求逆直接将对角线元素取倒数即可。注意中间矩阵的维度！）

## 2. 满秩分解法
设$A\in C_r^{m\times n}, \ (r>0)$，且有满秩分解，$A=FG$，$F\in C_r^{m\times r}, \ G\in C_r^{r\times n}$，则有：
![[Pasted image 20231225141922.png|600]]

解析：
若对于列满秩矩阵$F\in C_r^{m\times r}$：$F^+=(F^HF)^{-1}F^H$
若对于行满秩矩阵$G\in C_r^{r\times n}$：$G^+=G^H(GG^H)^{-1}$

## 3. 谱分解法
![[Pasted image 20231225142537.png|600]]
## 4. 秩为1矩阵广义逆的快速求解：
![[Pasted image 20240101183130.png|600]]
![[Pasted image 20240101183222.png|600]]

# 求{1}-逆与{1,2}-逆
## 方法1
![[Pasted image 20231225143005.png|600]]

## 方法2
![[Pasted image 20231225144142.png|600]]

# 满秩分解求广义逆其他方法
![[Pasted image 20231225144306.png|600]]

# $A^+$广义逆的性质
![[Pasted image 20231223205718.png|600]]
# 其他广义逆的性质
![[Pasted image 20231223205353.png|600]]
![[Pasted image 20231223205403.png|600]]
![[Pasted image 20231223205454.png|600]]
![[Pasted image 20231223205536.png|600]]

# 由单个广义逆求广义逆的集合
1. 
![[Pasted image 20231225153039.png|600]]
2. 
![[Pasted image 20231225162511.png|600]]
3. 
![[Pasted image 20231225163159.png|600]]
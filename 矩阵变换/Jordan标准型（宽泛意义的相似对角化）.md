# 定义
## Jordan块
![[Pasted image 20231029180553.png|625]]
## Jordan矩阵
![[Pasted image 20231029180729.png|625]]
![[Pasted image 20231029180803.png|625]]


## Jordan标准型
![[Pasted image 20231029181020.png|625]]
### 注意
1. **A的Jordan标准型的主对角线元素就是A的特征值。**
2. 在Jordan标准型中，不同Jordan块的主对角线元素可能相同，因此不能通过Jordan块的阶数来判断此Jordan块对应的特征值的代数重数。

# 化Jordan标准型的方法
有两种方法求jordan标准型，都需要首先求矩阵的不变因子。
## 1. 初等变换法
1. 利用初等变换，求特征矩阵$(\lambda I -A)$的Smith标准型，求不变因子$d_i(\lambda),(i=1,2,...,n)$[[多项式矩阵与矩阵多项式]]
2. ![[Pasted image 20231031111732.png|625]]相同的$\lambda$不要合并。
3. ![[Pasted image 20231031111745.png|625]]
**初等因子的次数对应Jordan块的阶次，$\lambda_{ij}$对应主对角线元素。**
4. ![[Pasted image 20231031111824.png|600]]
## 2. 行列式因子法
### 行列式因子的定义
![[Pasted image 20231205201849.png|675]]
### 行列式因子的性质：
![[Pasted image 20231205202214.png|700]]
### 行列式因子与不变因子间的关系
![[Pasted image 20231205202250.png|700]]
### 行列式因子法求方阵Jordan标准型的步骤
![[Pasted image 20231205202540.png|700]]

# 性质
1. 任何一个方阵都与Jordan标准型矩阵相似。
2. Jordan块的幂：
![[Pasted image 20231205202714.png|600]]
3. Jordan矩阵的幂：
![[Pasted image 20231205202734.png|600]]



# 如何求相似变换矩阵
![[Pasted image 20231205210609.png|600]]
参见：https://zhuanlan.zhihu.com/p/386898488

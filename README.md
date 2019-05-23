# linear-regession

线性回归

通过属性的线性组合进行建立预测模型，目的是找到一条直线，一个平面或者超平面使得真实值和预测值的误差最小化。

y = wT * x + error 其中误差服从独立同分布和高斯分布。 w为权重参数， 建立模型过程就是求得最佳参数使得误差最小化

求解最佳参数方法有两种： 1. 矩阵求解  2. 梯度下降法

矩阵求解时，需要用到极大似然对数定律。

求解得到： w = (xT*x)^-1 * XT * y   需要注意 xT*x 的逆是否存在。

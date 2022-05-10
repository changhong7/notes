# MATLAB 环境

## 变量

- who 显示所有变量
- whos 显示所有变量、类型等
- clear 清除所有变量
- clear+变量名 清除特定变量

## 显示数字格式

- format short 小数点后4位
- format long 小数点后16位
- format bank 小数点后2位
- format short/long e 指数风格显示
- format rat 分数显示

## 杂记

- 较长的表达式可以在行尾加上三点...进行行输入
- 关闭MATLAB可在命令窗口输入 quit

# 向量与矩阵

## 等差元素向量

- linspace(a,b,n)
- logspace(a,b,n)

## 特征化向量

- length
- max
- min
- abs

## 向量的点乘和叉乘

- dot(a,b)
- cross(a,b)
  
## 矩阵运算

- ' 转置并取复共轭
- .' 转置不取复共轭
- .* 数组乘法
- .^2 数组乘方运算
- det 求行列式
- rank 求秩
- inv 求逆矩阵

## 特殊类型矩阵

- eye(n)  
- zeros(n) zeros(m,n)
- ones(n) ones(m,n)

## 引用矩阵元素

- 改变矩阵元素值
- 删除行/列等
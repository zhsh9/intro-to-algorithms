# 算法导论

- [算法导论](#算法导论)
- [知识梳理](#知识梳理)
  - [1. 算法基础知识](#1-算法基础知识)
  - [2. 分治策略](#2-分治策略)
  - [3. 动态规划](#3-动态规划)
  - [4. 贪心算法](#4-贪心算法)
  - [5. 回溯与分支限界](#5-回溯与分支限界)
  - [6. 线性规划](#6-线性规划)
- [各种算法基本思想](#各种算法基本思想)
- [学习资料](#学习资料)

考察题型

- 单选
- 填空
- 简答及计算
- 算法大题

考察内容

- 单选题、填空题：考察概念，小计算（课件课本内容）
- 简答计算、算法：五个章节，一章一个

# 知识梳理

## 1. 算法基础知识

- 算法时间复杂度概念
  - 最坏
  - 平均
- 伪代码，贯穿全课程，大题基础
- 算法数学基础
  - 函数渐近的界相关概念
  - 判断函数的阶：
    - 多项式
    - 对数
    - 幂
    - 指数
    - 阶乘
  - 递推方程求解：
    - 根据递推式or伪代码，求复杂度
    - 根据主定理求复杂度（不考察证明）

## 2. 分治策略

- 算法思想、设计思路
- 改进分治算法的途径（不考察巧妙的改进方法）
- 典型实例
  - 快速排序、二分搜索、选择问题（最大、最小、第n大|小 等等）
  - 重点掌握分治解决上述问题的思路、求复杂度

## 3. 动态规划

- 算法思想、设计思路
- 设计要素
  - 优化原则
  - 子问题划分和递推方程
  - 递归与迭代实现的区别
- 典型应用
  - 投资问题、背包问题、最长公共子序列、最大子段和、最有二分检索树、序列对比等等
  - 掌握整体算法的思路、伪代码、复杂度分析

## 4. 贪心算法

- 设计思想
- 正确性证明
  - 掌握证明贪心法的正确性
- 4.3 得不到最优解的处理不考察
- 典型应用
  - 最优前缀码、最小生成树（Prim和Kruskal）、单源最短路径等
  - 掌握整体算法的思路、正确性证明、伪代码、复杂度分析

## 5. 回溯与分支限界

- 基本思想和使用条件
- 回溯算法设计步骤
- 分支限界
  - 课件中典型问题需要掌握分支限界的思想
  - 使用分支限界方法解决问题

## 6. 线性规划

- 线性规划解的情况
- 标准型
- 单纯形法
- 本章节不考察证明

# 各种算法基本思想

Ref: 高数帮

## 分治

![image-20230619114325404](.README.assets/image-20230619114325404.png)

![image-20230619114727512](.README.assets/image-20230619114727512.png)

## 动态规划

![image-20230619114452542](.README.assets/image-20230619114452542.png)

![image-20230619114527331](.README.assets/image-20230619114527331.png)

## 贪心

![image-20230619114405882](.README.assets/image-20230619114405882.png)

## 回溯

![image-20230619114919230](.README.assets/image-20230619114919230.png)

![image-20230619115003466](.README.assets/image-20230619115003466.png)

![image-20230619115055759](.README.assets/image-20230619115055759.png)

![image-20230619121607152](.README.assets/image-20230619121607152.png)

![image-20230619121627786](.README.assets/image-20230619121627786.png)

## 分支限界

![image-20230619130426581](.README.assets/image-20230619130426581.png)

![image-20230619131207904](.README.assets/image-20230619131207904.png)

## 线性规划



# 学习资料

- 教材
  - 《算法设计与分析》，清华大学出版社，屈婉玲
  - 《算法导论》，Thomas H.Cormen
- 视频
  - [算法设计与分析期末](https://www.bilibili.com/video/BV1X3411u7xW)
  - [【算法设计与分析】期末考试突击课](https://www.bilibili.com/video/BV1hc41137go)
  - [算法设计与分析MOOC-青岛大学-张公敬教授](https://space.bilibili.com/2065111657/channel/collectiondetail?sid=1199193)
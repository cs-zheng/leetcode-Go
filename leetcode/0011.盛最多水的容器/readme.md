![img.png](img.png)

# 题意分析
抽象：在一组横坐标上，有高度不一的柱子，问选取哪两根柱子可以使柱子间围成的面积最大。（高度以木板效应为准）

# 解题思路
设定两个柱子高度分别为 A，B
面积 = min(A,B)*|A-B|

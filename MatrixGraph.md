///****************************************
丁宇飞 2018.2.9
这是一个用邻接矩阵实现的图，适用于稠密图，
实现了用任何类型的数组初始化一个图，还可以添加一个用整型数组初始化权值的功能，
这个图既可以是有向图也可以是无向图，由参数choice的值决定
实现了深度优先和广度优先遍历，缺点是用递归实现所以另外需要一个reset()函数
实现visited[]的重置。此外设置了一个顶点与其所在下标的对照表展示函数VertexShow()
方便输入，注意BFS与DFS参数都是下标，不能用顶点（字符）实现----试过，但失败
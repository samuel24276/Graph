///********************************************
2018.2.9 用于稀疏图效率最高
没想到能今天搞定，主要是邻接矩阵与邻接表有一定相似性
比邻接矩阵实现的那个多了一个不用手动输入参数就可以初始化图的函数
需要注意的就是所需结点种类多，有表头节点，弧结点，顶点结点，所以结构体较多，
另外产生疑问，无向图与有向图创建后的DFS与BFS差别不好弄清楚，需要大量实例，
时间紧张，就不弄了，好好放松一下，累了
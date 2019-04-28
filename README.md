Fortran程序练习题：求最短路径算法及实现（把无向图转换为有向图，并使用Dijkstra算法求解）

一、执行程序的命令行
    find_shortest_path undirected_graph_info.txt

二、描述m个点n条路径无向图的undirected_graph_info.txt文件里面的数据格式如下:
    m n line_max_length
    m个点的名称信息行
    路径1起点 路径1终点 路径1长度
    。
    。
    。
    路径n起点 路径n终点 路径n长度
    求最短路径的起点名称 求最短路径的终点名称

三、关键算法：把无向图转为有向图，采用Dijkstra算法求解最短路径

四、测试案例
1. 2x4的长方形，求对角2个点的最短路线
2. 五一布置的Fortran编程题目的图形，求G点到J点的最短路径
3. 五一布置的Fortran编程题目的图形，求A点到J点的最短路径

五、程序使用的Fortran语言的相关开发语言的知识
1. 派生数据类型
2. 数组/二维数组
3. 判断和循环语句
4. 文件的读取
5. 内部函数的定义和调用
6. 获取命令行参数的内置函数

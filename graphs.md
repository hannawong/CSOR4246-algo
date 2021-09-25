### 1. Definition

- G = (V,E)

  - Vertex: n = |V|

  - Edges: e = |E|

- undirected graphs(无向图) & directed graphs (有向图)

  ![1632598310058.png](https://i.loli.net/2021/09/26/CrOG5Mmofs7q4Ux.png)

- 节点的度(degree): 

  - 对于无向图，deg(v) = number of edges incident to v;

  - 对于有向图，indeg(v) = number of edges entering v; 

    ​			outdeg(v) = number of edges leaving v

- 路径：

  - path: <img src="http://chart.googleapis.com/chart?cht=tx&chl= (x_1,x_2...x_n)" style="border:none;"> such that consecutive vertex are adjacent
  - simple path: all the vertex are distinct
  - simple cycle: a simple path that ends where it starts

![1632598525980](C:\Users\zh-wa\AppData\Roaming\Typora\typora-user-images\1632598525980.png)

- 连通性

  - **connected:** there is a path between **every pair of vertices**
  - 

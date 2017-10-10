
# 加权有向图的数据结构

由于数据是String，但是这不利于邻接表里面的索引查找，所以考虑建立String到Integer的映射，
有向图节点数据转化为int类型，等到需要输出的时候再把Map映射回去就行了
### 需要用到Map结构的地方：
 - Edge构造方法里面，需要把输入String映射成int，
 - 用到输出的地方，把int还原为String

 加入邻接表的过程中，由于这次的可能出现同一条边加多次，所以需要找要加入点的邻接表之前有没有加过当前节点，如果有则将该边的weight+1



// Change something

// c4
# 2019B站校园招聘研发笔试题

## 最短路径逃脱问题(MouseEscape)

精灵鼠从入口到出口的最少减少速度

时间限制：C/C++语言 1000MS；其他语言 3000MS

内存限制：C/C++语言 65536KB；其他语言 589824KB

题目描述：

猛兽侠中精灵鼠在利剑飞船的追逐下逃到一个n*n的建筑群中，精灵鼠从（0,0）的位置进入建筑群，建筑群的出口位置为（n-1,n-1），建筑群的每个位置都有阻碍，每个位置上都会相当于给了精灵鼠一个固定值减速，因为精灵鼠正在逃命所以不能回头只能向前或者向下逃跑，现在问精灵鼠最少在减速多少的情况下逃出迷宫？

输入

第一行迷宫的大小: n >=2 & n <= 10000； 第2到n+1行，每行输入为以','分割的该位置的减速,减速 f >=1 & f < 10。

输出

精灵鼠从入口到出口的最少减少速度？

样例输入

```
3
5,5,7
6,7,8
2,2,4
```

样例输出

```
19
```

## 版本号比较问题(VersionCompare)

比较两个版本字符串version1和version2

时间限制：C/C++语言 1000MS；其他语言 3000MS

内存限制：C/C++语言 65536KB；其他语言 589824KB

题目描述：

如果version1 > version2 返回1，如果 version1 < version2 返回-1，不然返回0.

输入的version字符串非空，只包含数字和字符。.字符不代表通常意义上的小数点，只是用来区分数字序列。
例如字符串2.5并不代表二点五，只是代表版本是第一级版本号是2，第二级版本号是5.

输入

两个字符串，用空格分割。每个字符串为一个version字符串，非空，只包含数字和字符.

输出

只能输出1, -1，或0


样例输入

`0.1 1.1`

样例输出

`-1`

## 附带提前结束条件的顺时针打印数字矩阵(ClockwiselyPrintMatrix)

时间限制：C/C++语言 1000MS；其他语言 3000MS

内存限制：C/C++语言 65536KB；其他语言 589824KB

题目描述：

给定一个数字矩阵，请设计一个算法从左上角开始顺时针打印矩阵元素；

输入

第一行是两个数字，分别代表行数M和列数N；接下来是M行，每行N个数字，表示这个矩阵的所有元素；当读到M=-1，N=-1时，输入终止；

输出

请按逗号分割顺时针打印矩阵元素（注意最后一个元素末尾不要有逗号！例如输出“1，2，3”，而不是“1，2，3，”），每个矩阵输出完成后记得换行；


样例输入
```$xslt
3 3
1 2 3
4 5 6
7 8 9
-1 -1
```
样例输出
```$xslt
1,2,3,6,9,8,7,4,5
```

## 顺序表leetcode

![image-20210331210720938](C:\Users\牛乾\AppData\Roaming\Typora\typora-user-images\image-20210331210720938.png)

解答过程曲折：**调试了将近一个小时**，报错如下：

![image-20210331210927421](C:\Users\牛乾\AppData\Roaming\Typora\typora-user-images\image-20210331210927421.png)



这是一个堆错误，nums数组是由动态规划的。

查看测试用例：![image-20210331211117076](C:\Users\牛乾\AppData\Roaming\Typora\typora-user-images\image-20210331211117076.png)



当输入空数组时，就发生了堆错误。

![image-20210331211251263](C:\Users\牛乾\AppData\Roaming\Typora\typora-user-images\image-20210331211251263.png)

考虑完整。输入空数组时，解引用时便发生错误。
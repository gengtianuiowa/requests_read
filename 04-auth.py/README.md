
1.  ## 代码风格
    
2.  ## 重点剖析
  ![image info](./01.png)
  开头的注释依然很清楚，注明了函数存在的用意。
  
  ![image info](./02.png)
  注意这里`{!r}.format()`的意思是调用__repr__: returns a printable representation of the given object。[__str__和__repr__的异同](https://stackoverflow.com/questions/1436703/what-is-the-difference-between-str-and-repr)
    
  ![image info](./03.png)
  这里写HTTPAuth前写AuthBase作为基类，方便日后扩展和避免重复代码。好评！
  [__call__的含义](https://blog.csdn.net/Yaokai_AssultMaster/article/details/70256621)
  
  
3.  ## 总结
   

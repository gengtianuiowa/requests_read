## 1. 代码风格
本页代码比较简单。但依然存在一些代码风格上的特点。
## 2. 重点剖析
  ![image info](./1.png)
  
  ![image info](./2.png)
  
  注意此处RequestsCookieJar重写了dict，但他并没有直接重写dict，而是继承了MutableMapping。这是为了重写Dict而使用的。[dict的继承关系](https://stackoverflow.com/questions/1436703/what-is-the-difference-between-str-and-repr)
  
  ![image info](./3.png)
    
  这里构造dict的方式很巧妙。dict.update()更新字典，很妙！
  
  ![image info](./4.png)
  
  这里的代码我觉得写的很好。根据多条件判断有没有重复的name。
  上面的注释的方式也写的很不错！告诉了哪里使用了这些代码，以及参数的含义是什么。
  
  ![image info](./5.png)
  
  巧用构造器，很Pythonic！
  
## 3. 总结
继承了代码一贯上的简洁风格。读起来不费力。巧妙利用了继承特性。Exception调用了原生的同时，做了适当扩展延伸。
   

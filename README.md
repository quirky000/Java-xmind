# Java-xmind

JavaSE  
=
## 一、基础
 1.***[继承](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E7%BB%A7%E6%89%BF.xmind)***：Java面向对象最显著的特征。继承是在一个已有的类的基础上派生新的类，并在这个新类上拓展新功能。  
 2.***[多态](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E5%A4%9A%E6%80%81.xmind)***：“一个定义，多种实现”。利用多态可实现代码解耦，提高系统的可拓展性。多态主要体现在方法的重载和方法的覆盖。  
 3.***[static静态](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/static%E9%9D%99%E6%80%81.xmind)***：static是为静态的意思，这个关键字能够用于修饰变量和方法。修饰变量即为静态变量，常用于会被多个对象共享的变量；修饰方法即为静态方法，常用于工具类中。  
 4.***[权限修饰](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%9D%83%E9%99%90%E4%BF%AE%E9%A5%B0.xmind)***：Java中常用的几种用来限制变量或方法的访问权限的修饰词。  
 5.***[接口](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%8E%A5%E5%8F%A3.xmind)***：Java接口主要是对功能进行描述和规范，在JDK8之前接口中全都是抽象方法。  
 6.***[抽象类](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%8A%BD%E8%B1%A1%E7%B1%BB.xmind)***：抽象类用来描述某种类型应该具备的基本特征与功能，由子类通过方法重写来具体完成这些行为。（如：动物都会吃东西，但不同动物吃的食物和方式都不一样，在这里动物即为抽象类，具体的吃饭这一行为则由子类重写方法来进行具体实现）  
 7.***[代码块](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E4%BB%A3%E7%A0%81%E5%9D%97.xmind)***：代码块是类的成分之一，通过{}键逻辑语句封装。无方法名，无返回值，无参数，在加载类或创建对象时隐式调用。代码块可以补充构造器功能，同时提高代码的复用性。  
 8.***[集合](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E9%9B%86%E5%90%88.xmind)***：集合主要负责保存、盛装其他数据，分为List集合、Set集合和Map集合。  
 9.***[内部类](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E5%86%85%E9%83%A8%E7%B1%BB.xmind)***：即在类内部的类，由静态内部类、成员内部类、局部内部类和匿名内部类组成。  
 10.***[单例设计模式](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E5%8D%95%E4%BE%8B%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.xmind)***：在单例设计模式下，一个类只有一个实例且这个类可以自行创建这个实例。其中单例设计模式又分为饿汉式和懒汉式。  
 11.***[工具类](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E5%B7%A5%E5%85%B7%E7%B1%BB.xmind)***：包含了Java开发中常用的Math、System、Object、Objects、BigDecimal、Date、Calendar、SimpleDateFormat等工具类。  
 12.***[异常](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E5%BC%82%E5%B8%B8.xmind)***：在开发过程中常会出现导致项目运行失败的因素，其中分为error和异常。error通常为硬件问题，相对的异常则是能够通过代码优化解决。  
 13.***[正则表达式](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.xmind)***：正则表达式是一种匹配字符串的方法，通过一些特殊符号，实现快速查找、删除、替换某个特定字符串，能借此提高快速提取或处理关键信息，使得运维工作更加简单和方便。    
 14.***[泛型](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%B3%9B%E5%9E%8B.xmind)***：在JDK5中引入的一个新特性, 泛型提供了编译时类型安全检测机制，该机制允许程序员在编译时检测到非法的类型。本质是参数化类型，即所操作的数据类型被指定为一个参数。  
 15.***[数据结构：二叉树](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%EF%BC%9A%E4%BA%8C%E5%8F%89%E6%A0%91.xmind)***：二叉树一种特殊的树型结构，它的特点是每个结点至多只有两棵子树（即二叉树中不存在度大于2的结点），并且，二叉树的子树有左右之分，其次序不能任意颠倒。（树型结构：非线性数据结构，相对于线性结构，树型结构的查找性能与插入性能都比线性结构好一些。）    
 16.***[排序和查找算法](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/%E6%8E%92%E5%BA%8F%E5%92%8C%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95.xmind)***：  
 17.***[Steam流](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/Stream%E6%B5%81.xmind)***：  
 18.***[Lambda表达式](https://github.com/quirky000/Java-xmind/blob/master/JavaSE/Lambda%E8%A1%A8%E8%BE%BE%E5%BC%8F.xmind)***：  
 19.***[多线程](https://github.com/quirky000/Java-xmind/tree/master/JavaSE/%E5%A4%9A%E7%BA%BF%E7%A8%8B)***：  

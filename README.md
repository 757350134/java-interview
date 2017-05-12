# java面试收集 欢迎大家pull requests
                                               
一.java基础方面的  
   1）HashMap底层是怎么实现的，linkedHashMap呢？为什么说concurrentHashMap多线程下比HashTable高效？   
      首先看下hashMap的实现吧，底层是数组加链表实现的，那么为什么这么实现呢？它是结合的两者的优点，数组有下标，查询快，链表的特点是增删快，来看源码  
      
      static final int DEFAULT_INITIAL_CAPACITY = 1 << 4; // aka 16初始容量
      
      
      
      
      
   

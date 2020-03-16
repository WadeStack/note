### Java中垃圾回收有什么目的？什么时候进行垃圾回收？

垃圾回收的目的是识别并且丢弃应用不再使用的对象来释放和重用资源。

  触发主GC（Garbage Collector，垃圾回收）的条件： 

  （1）当应用程序空闲时，即没有应用线程在运行时，GC会被调用。 

  （2）Java堆内存不足时，GC会被调用。

###### 原地址

链接：https://www.nowcoder.com/questionTerminal/669b88c90a7545e6aa556beef815c43f
来源：牛客网


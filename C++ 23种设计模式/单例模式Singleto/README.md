单例模式：保证一个类仅有一个实例，并且提供一个该类的全局访问点

要点总结：

1、实例构造器可以设置为 protected 运行子类派生

2、Singleton 一般不支持拷贝构造，因为有可能导致多个对象

3、实现多线程环境下的安全Singleton,采用双检查锁，需要注意内存对变量的优化

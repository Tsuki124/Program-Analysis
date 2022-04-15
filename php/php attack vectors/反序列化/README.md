魔法函数

```
1. __construct()//创建对象时触发
2. __destruct() //对象被销毁时触发
3. __call() //在对象上下文中调用不可访问的方法时触发
4. __callStatic() //在静态上下文中调用不可访问的方法时触发
5. __get() //用于从不可访问的属性读取数据
6. __set() //用于将数据写入不可访问的属性
7. __isset() //在不可访问的属性上调用isset()或empty()触发
8. __unset() //在不可访问的属性上使用unset()时触发
9. __invoke() //当脚本尝试将对象调用为函数时触发
10. __sleep() //对象被序列化前触发
11. __wakeup() //反序列化前触发
	当序列化字符串中，表示对象属性个数的值大于实际属性个数时，那么就会跳过wakeup方法的执行。
12. __toString() //将对象当做字符串输出会触发

```

https://y4er.com/post/unserialize/
https://paper.seebug.org/1480/

#### Php伪协议

https://www.yingyingguaier.top/others/php-%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB%E4%BC%AA%E5%8D%8F%E8%AE%AE%E5%88%A9%E7%94%A8/

https://www.jianshu.com/p/07b7a9b5e333

##### Phar://

何使用phar://伪协议出发反序列化，利用场景以及前提条件有哪些

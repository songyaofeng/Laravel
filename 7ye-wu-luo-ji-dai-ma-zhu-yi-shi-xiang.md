1.状态，登记，各种方式等诸多实例尽量定义成常亮；

2.大段的验证尽量定义成方法；

3.获取某个字段的值尽量用value；

4.实例化类使用依赖注入

5.接收id参数时，尽量用intval函数，接受不到参数设为0,好判断；

6.判断数据是否存在使用exists\(\)

7.修改表前缀：app\('db'\)-&gt;setTablePrefix\($oldPrefix\);




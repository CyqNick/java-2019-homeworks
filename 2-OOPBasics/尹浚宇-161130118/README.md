此次作业我生产了四个类, 第一个类为葫芦娃类, 第二个类为上帝类, 第三个类为世界类, 第四个类为主函数类.

这里葫芦娃具有的属性为: 二维空间坐标对(X, Y); 名字; 颜色; 排行.
葫芦娃可以报出自己的名字, 报出自己的颜色, 以及通过瞬移的方式从一个坐标移动到另一个坐标.
世界类可理解为一个抽象的有葫芦娃的虚拟世界, 这里只有一个地图属性, 其上可以摆放葫芦娃.
上帝类没有自己的成员变量, 可以理解为一组方法的集合. 上帝创造并凌驾于葫芦娃世界之上, 一切对于葫芦娃的外部操作均由上帝类提供实现.

程序的流程为:
上帝诞生 --> 上帝创造了葫芦娃世界和葫芦娃 --> 上帝将葫芦娃放入葫芦娃世界中 --> 开始进行题目规定的流程.

这里在葫芦娃交换位置时, 我认为葫芦娃是通过瞬移的方式移动的, 并规定使用位置(6, 6)作为两个葫芦娃交换位置的中转位置.
即葫芦娃交换位置的流程可理解为: 
葫芦娃1 -> (6, 6);
葫芦娃2 -> 葫芦娃1原位置;
葫芦娃1从(6, 6) -> 葫芦娃2原位置
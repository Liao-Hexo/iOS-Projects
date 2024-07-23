写一个类：
1）要先为类写属性
2）再声明属性的getter和setter
3）再实现getter和setter

@property

作用：自动生成getter、setter方法的声明，因为是生成方法的声明，所以应该写在@interface类的声明之中

语法：@property 数据类型 名称；`@property int age;`

原理：
![](https://raw.githubusercontent.com/Liao-Hexo/image-repository/Description/image-repository/Objective-C/0081Kckwly1gly3uk8pkvj30c4049764.jpg)

![](https://raw.githubusercontent.com/Liao-Hexo/image-repository/Description/image-repository/Objective-C/0081Kckwly1gly3urj5vpj30gr059juq.jpg)
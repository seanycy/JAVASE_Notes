- Java概述
	- Java与JavaScript：二者没有关系
	- 前端三剑客：HTML CSS JS
- 博客记录的是自己觉得重要的东西
	- 博客不仅可以让自己以后复习重要的知识，也可以给别人带来有意义的帮助
	- 博客也是自己的品牌、
	- 踏踏实实总结好自己的知识
- Java历史
	- Java祖师爷：詹姆斯 · 高斯林
	- 起源于1991年四月，Java前身：Oak
	- 1995年pc互联网开始发展
	- Java名字由来—>爪哇岛的咖啡老爷子最爱
	- Write once,run anywhere
- JDK 
	- JDK8 是目前公司长期开发的版本


# 1.Main方法
1. 第一个Java程序：
```js
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println("Hello World");
	}
}
```
1. 运行
	1. 编译命令：javac XXX.java
		1. 字节码文件：.class文件 二进制文件
	2. 运行命令：java XXX
	3. 程序运行地在JVM上
		1. JDK、JRE、JVM
			1. JDK(Java Development Kit)包含Java运行环境（JRE，Java RunTIme Environment），其内含Java虚拟机（JVM）
	4. public修饰的类和文件名一定是一样的，并且有且只有一个；同时一个Java文件中只有一个类和当前文件名相同
2. 代码解释
	1. class->类，类名命名采用大驼峰的形式。方法必须在类内部声明
	2. public static void main(String[] args)<-方法/函数
		1. public->访问修饰限定符
		2. static->关键字，表示静态
		3. void->返回值
		4. main->方法名
		5. String[] args->形参
	3. Java写法：类->方法->局部变量
3. 注意事项：
	1. 源文件后缀名不是.java
	2. 类名与文件名不同
	3. 方法中语句没有以分号结尾
	4. 

# 2.注释
注释的改变也是对源码的改变，需要重新编译
```js
//ctrl+shift+/->块注释
/*块注释*/

//ctrl+/->h行注释

/**
文档注释
*/
```
强制编码规则转换（记事本utf-8，而cmd是GBK编码）：javac HelloWorld.java -encoding utf-8
由“@”符号开始的称为注解
TODO：带实现
文档注释可以生成一个html文件，方便开发，是对方法和类的说明

# 3.标识符
即在程序中由用户给类名、方法名或者变量所取得名字
- 标识符中可以包含数字、下划线、字母和美元符号
- 类名：每个单词首字母大写
- 方法名：首字母小写，后面每个单词得首字母大写
- 变量名：与方法名命名相同

- 例：下面哪些标识符是合法的？
	- A：class B：HelloWorld C：main D：123abc E：ARRAY_SIZE F: $name G: name:jim
		- 合法标识符：BEF
		- 冒号不是标识符
		- 常量写法和E相同

# 4.关键字
关键字是由Java语言提前定义好的，有特殊含义的标识符，或者保留字
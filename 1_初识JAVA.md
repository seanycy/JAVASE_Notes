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
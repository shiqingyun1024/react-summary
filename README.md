# React-summary
react相关的总结

## 第一章：React入门
### 1.1.1 官网
```
1）英文官网：https://reactjs.org/
2）中文官网：https://react.docschina.org/
```
### 1.1.2 介绍描述
```
React是用于构建用户界面的JavaScript库。
由Facebook开源

页面构建的过程：
1. 发送请求获取数据。
2. 处理数据（过滤、整理格式等）
3. 操作DOM呈现页面 === react主要做这一步

可以理解为：
react是一个将数据渲染为HTML视图的开源JavaScript库。

1. 原生JavaScript操作DOM繁琐、效率低（DOM-API操作UI）
如：document.getElementById('app')
如：document.querySelector('#app')
如：document.getElementByTagName('span')
2. 使用JavaScript直接操作DOM，浏览器会进行大量的重绘重排。
3. 原生JavaScript没有组件化编码方案，代码复用率低。
```
### 1.1.3. react的特点
```
1. 采用组件化模式、声明式编码，提高开发效率及组件复用率。
2. 在React Native中可以使用React语法进行移动端开发。
3. 使用虚拟DOM+优秀的Diffing算法，尽量减少与真实DOM的交互。
```
### 1.1.4. react高效的原因
```
1）使用虚拟（virtual）DOM，不总是直接操作页面真实DOM。
2）DOM Diffing算法，最小化页面重绘。
```
## 1.2 react的基本使用
### 1.2.1. 效果
### 1.2.2. 相关js库
### 1.2.3. 创建虚拟DOM的两种方式
### 1.2.4. 虚拟DOM与真实DOM
```
```
## 1.3 React JSX
### 1.3.1 效果
### 1.3.2 JSX
```
1）全称：JavaScript XML
2）react定义的一种类似于XML的js扩展语法：js+XML
XML早期用于存储和传输数据
<student>
   <name>Tom</name>
   <age>19</age>
</student>
后面改为JSON存储了，因为JSON更方便
"{"name":"Tom","age":19}"
3）本质是React.createElement(component,props,...children)方法的语法糖

```
### 1.3.3 渲染虚拟DOM（元素）
### 1.3.4 JSX练习

## 1.4 模块与组件、模块化与组件化的理解
### 1.4.1 模块
```
1.理解：向外提供特定功能的js程序, 一般就是一个js文件。
2.为什么要拆成模块：随着业务逻辑增加，代码越来越多且复杂。
3.作用：复用js, 简化js的编写, 提高js运行效率。
```
### 1.4.2 组件
```
1.理解：用来实现局部功能效果的代码和资源的集合(html/css/js/image等等)
2.为什么要用组件： 一个界面的功能更复杂
3.作用：复用编码, 简化项目编码, 提高运行效率
```
### 1.4.3 模块化
```
当应用的js都以模块来编写的, 这个应用就是一个模块化的应用
```
### 1.4.4 组件化
```
当应用是以多组件的方式实现, 这个应用就是一个组件化的应用
```

# 第2章：React面向组件编程
## 2.1.基本理解和使用
### 2.1.1基本理解和使用
### 2.1.2 效果
```
函数式组件：适用于【简单组件】的定义

类式组件：适用于【复杂组件】的定义
```
## 2.2. 组件三大核心属性
1.state
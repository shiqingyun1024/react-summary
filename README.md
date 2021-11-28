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
```
```


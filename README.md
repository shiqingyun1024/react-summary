# React-summary
react相关的总结

## React简介
### 1. 是什么？
```
React是用于构建用户界面的JavaScript库。

页面构建的过程：
1. 发送请求获取数据。
2. 处理数据（过滤、整理格式等）
3. 操作DOM呈现页面 === react主要做这一步

可以理解为：
react是一个将数据渲染为HTML视图的开源JavaScript库。
```
### 2. 为什么要学？
```
1. 原生JavaScript操作DOM繁琐、效率低（DOM-API操作UI）
如：document.getElementById('app')
如：document.querySelector('#app')
如：document.getElementByTagName('span')
2. 使用JavaScript直接操作DOM，浏览器会进行大量的重绘重排。
3. 原生JavaScript没有组件化编码方案，代码复用率低。
```
### 3. react的特点
```
1. 采用组件化模式、声明式编码，提高开发效率及组件复用率。
2. 在React Native中可以使用React语法进行移动端开发。
3. 使用虚拟DOM+优秀的Diffing算法，尽量减少与真实DOM的交互。

```

# 类和继承
## 教学目标
学习面向对象编程的类和继承。

## 需求描述
写一个Person类，要有name，age属性，要有一个introduce方法， introduce方法返回一个字符串形如：
`My name is Tom. I am 21 years old.`

再写一个Student类继承Person类，除了name，age属性，还要有class属性。也有一个introduce方法， introduce方法返回一个字符串形如：
`My name is Tom. I am 21 years old. I am a Student. I am at Class 2.`

## 作业要求
1. 根据```spec/main-spec.js```中的测试用例，在```src/main.js```文件中编写实现代码并确保测试通过；
2. 请在保证代码可读性的前提下，尽可能用最少的代码行数完成作业；
3. 将结果输出到控制台。

## 作业提示
1. 使用 `console.log` 输出调试
2. `class` 是一个关键字，可以用 clazz 代替

## 如何使用

首先初次下载完需要安装依赖：
```
  npm install
```

然后才能执行测试：

```
  npm test
```

可以通过测试来检测本地代码是否完成作业要求，测试通过即可提交到github，把git库地址填到答题页面，并提交表单。

## 参考资料
1. [npm 下载安装](https://github.com/npm/npm)
2. [node 下载安装](https://github.com/creationix/nvm)
3. [jasmine用法](http://jasmine.github.io/2.4/introduction.html)
4. [git用法1](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/docs/02%20%E5%9C%A8%20Windows%20%E5%B9%B3%E5%8F%B0%E5%BF%85%E8%A3%9D%E7%9A%84%E4%B8%89%E5%A5%97%20Git%20%E5%B7%A5%E5%85%B7.markdown)
5. [git用法2](https://try.github.io/levels/1/challenges/1)
6. [git简易指南](http://gitref.org/zh/index.html)
7. [github用法](https://guides.github.com/activities/hello-world/)
8. [ECMAScript 6 入门](http://es6.ruanyifeng.com/)
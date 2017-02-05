
# Next Demo

这是一个Next.js Demo, 是从官方提供的example中修改而来，本文档分析了next项目的常见结构以及路由，组建等如何使用。

## Installation

    $ npm install

## Running the app

    $ npm run dev

## 路径分析

1. components：这个路径存放一些通用的组件，一般是多个页面需要通用的组件。
2. pages：这个路径存放所有的页面，每一个jsx文件都会被渲染为一个单独的页面。

## 简单开发

* 由于是基于React的框架，因此，组件的写法和React一样。
* 所谓的page页面，实际上也是一个单独的组件，不过page需要写的比较完整一点。
* 在page中引用组件，可以使用ES6的方式引入。
* 在页面之间的跳转，实际上已经被封装到next框架中，只需要使用a标签加上__href__属性指向另一个页面即可，例如，同路径下的home.js,只需要使用`/home`来赋给__href__即可实现跳转。
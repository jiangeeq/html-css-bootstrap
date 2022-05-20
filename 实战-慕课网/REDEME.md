## 背景说明
项目是仿照 [慕课网](https://www.imooc.com/)所制作的PC端页面，项目中的许多字体、图片等等均采集自慕课网。目前只仿照了主页，后续如有需要可仿照其他相关页面。

## 技术说明
项目采用的技术栈及规范
|技术|版本|介绍|
|--|--|--|
|html| 5| HTML5是构建Web内容的一种语言描述方式。HTML5是互联网的下一代标准  |
|css| 3|  最新的 CSS 标准 |
|node| v14.18.3| 一个基于 Chrome V8 引擎的 JavaScript 运行时服务端  |
|scss| 1.51.0| 一款强化 CSS 的辅助工具，它在 CSS 语法的基础上增加了变量、嵌套、混合 、导入等高级功能，这些拓展令 CSS 更加强大与优雅  |
|BEM |命名约定 | 一个简单又非常有用的命名约定。让你的前端代码更容易阅读和理解，更容易协作，更容易控制，更加健壮和明确，而且更加严密。|

## 如何运行
1. 请确保本机已安装node环境，如无，请自行搜索如何下载与安装nodejs
2. 根目录执行`npm install` 下载项目依赖
3. 根目录执行`npm install live-server -g`，使用`live-server`可以开启轻量级的web服务
4. 根目录执行`npm install sass -g`，需要sass来辅助生成css文件
5. 根目录执行 `npm run compile:sass`，编译sass输出css文件
6. 执行`npm run server`，选用默认浏览器打开页面

## 优化说明

1. <font color="red">index.html 目前为遵守BEM命名规范，建议参考BEM命名约定进行修改</font>
2. <font color="red">scss 代码不够抽象，可以再重新组织，以便更好管理</font>


## 参考资料
[Sass 中文文档](https://www.sass.hk/docs/)

[live-server的使用](https://www.jianshu.com/p/a162131e22d0)

# Sample

> File templates for front-end projects.

## 简介

每次在 GitHub 新建一个前端小项目，都要做一遍繁琐的、重复的 “文案工作”？那不如把常用文件汇总为一个项目模板吧，以后新建项目时直接复制出来填填改改就可以了。

现在可用以下源码文件模板：

* `README.md` （稍复杂的项目可以选用 `README.full.md`）
* `.gitignore`
* `package.json`
* `bower.json`
* `.editorconfig`
* `src/*.*`
* `test/*.*`
* `gulpfile.js`
* `redir.html` （适用于 GitHub Pages 的重定向页面）

以及文档模板：

* `doc/*.md`
* `wiki/*.md`
* `releases/*.md`

## 兼容性

依赖以下类库：

* Underscore
* jQuery

支持以下浏览器：

* Chrome / Firefox / Safari 等现代浏览器
* IE 6+

## 安装

0. 通过 Bower 安装：

	```sh
	$ bower install {sample}
	```

0. 在页面中加载 {Sample} 的脚本文件及必要的依赖：

	```html
	<script src="bower_components/underscore/underscore-min.js"></script>
	<script src="bower_components/jquery/dist/jquery.min.js"></script>
	<script src="bower_components/zepto.js/dist/zepto.min.js"></script>
	<script src="bower_components/{sample}/src/{sample}.js"></script>
	```

## API 文档

所有文档入口在 [Wiki 页面](https://github.com/cssmagic/sample/wiki)，快去看吧！

## 单元测试

0. 把本项目的代码 fork 并 clone 到本地。
0. 在本项目的根目录运行 `bower install`，安装必要的依赖。
0. 在浏览器中打开 `test/test.html` 即可运行单元测试。

## 谁在用？

以下网站采用 {Sample} 作为基础组件：

* [某某网站](https://github.com/cssmagic/sample)

***

## License

[MIT License](http://www.opensource.org/licenses/mit-license.php)

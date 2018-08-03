# VueStudy
学习Vue.js的相关内容，采用Vue2.0版本。

# Vue.js学习资源
* vuejs中文官网 - http://cn.vuejs.org/
* vuejs源码 - https://github.com/vuejs/vue
* vuejs官方工具 - https://github.com/vuejs
* vuejs官方论坛 - http://forum.vuejs.org/

# 兼容性
* Vue不支持IE8及以下版本,因为Vue使用了IE8无法模拟的ECMAScript5特性。但它支持所有兼容ECMAScript的浏览器。

# 修改ES版本的方法
* 把鼠标移至import的波浪线上，出现提示：W119 - ‘import’  is only available in ES6(use 'esversion: 6') .意思是import属于ES6的语法，当前页面不能用。
* 在项目的根目录创建一个 ** .jshintrc ** ，里面添加以下配置 
	`{
		"esversion": 6
	}`
	表示ES用ES6的语法。

# jshint校验忽略文件的方法
* 在项目的根目录下创建一个 ** .jshintignore ** ，将要忽略的文件路径写到该文件中。可以是带路径的文件名、路径名、匹配规则。如 * scr/App.vue * 。

# 项目使用插件更新
* 例如安装vue-router并更新package.json,使用命令：npm install vue-router --save





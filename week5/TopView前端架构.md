# TopView前端架构


###1、依赖环境
> * node 
node官网：https://nodejs.org/en/
> * 使用git（版本管理工具）
git下载：https://git-scm.com/download/
git简明教程：http://www.bootcss.com/p/git-guide/

###2、自动化构建工具
> * webpack 
webpack入门：https://github.com/ruanyf/webpack-demos
> * gulp 
https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md
gulp中文网：http://www.gulpjs.com.cn/

###3、前端框架
> * react
react官网：https://facebook.github.io/react/
react入门：https://github.com/ruanyf/react-demos
http://www.ruanyifeng.com/blog/2015/03/react.html
> * Amaze UI（前端UI库）
http://amazeui.org/
> * sass （css框架）
http://www.w3cplus.com/sassguide/
http://www.ruanyifeng.com/blog/2012/06/sass.html
> * sea.js（模块化开发）
http://seajs.org/docs/
> * es6

###4、调试工具
> * Chrome dev Tool
> * Fiddler
Fiddler官网：http://www.telerik.com/fiddler
http://my.oschina.net/leejun2005/blog/151103

###5、框架开发分类
> * UI层框架开发（封装常用UI）（传玉、晓晖、炳伦）
> * js逻辑层框架开发（封装常用逻辑组件）（啊宝、cc）


使用sea.js搭建一个类似mvc的开发模板的例子如下：

```javascript
/**
* index.js
* @authors  joshtsang (joshtsang@tencent.com)
* @date    2015-10-13 19:58:03
* @version 
*/

	define(function(require, exports, module) {
	    var URL_PARAM = null;
	    var Index = {
	        /**
	         * 请求
	         * @method testRequest
	         * @param
	         */
	        testRequest: function() {
	           
	        },
	        /**
	         * 回调
	         * @method testResult
	         * @param {data} 
	         */
	        testResult: function(data) {
	            
	        },
	
	        /**
	         * 渲染页面
	         * @method initPage
	         * @param 
	         */
	        initPage: function(){
	            
	        },
	
	        /**
	         * 事件绑定
	         * @method bindEvents
	         * @param 
	         */
	        bindEvents: function() {
	
	        },
	
	        /**
	         * 初始化
	         * @method init
	         * @param 
	         */
	        init: function() { 
	            this.testRequest();
	            //绑定事件
	            this.bindEvents();
	            //渲染页面
	            this.initPage();
	        }
	    };
	    return Index;
	});
```





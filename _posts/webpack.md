---
published: false
---
## 准备步骤
1.创建目录，cmd下跳转到该目录路径

2.在该目录下安装webpack至最新版本

	npm install --save-dev  webpack
    npm install webpack@beta（version）
   
3.安装webpack-cli插件

   npm install webpack-cli -D


## 起步
1.在当前目录下初始化npm
	npm init -y
2.构建目录
	+ |- index.html
   + |- src
   +  |- index.js
``` html
	<!doctype html>
<html>
	<head>
	<tittle>Getting Started</tittle>
	<script src="https://unpkg.com/lodash@4.16.6"></script>
	</head>
	<body>
		<script src="./src/index.js"></script>
	</body>
</html>
```
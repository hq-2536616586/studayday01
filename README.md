# studayday01
测试
1.	模块
(1)	ES6：
①	export default ...
②	import ... from ...
(2)	Nodejs
①	exports/ module.exports
②	require(“http”)
(3)	模块加载顺序
①	缓存
②	核心模块
③	文件模块 “./js/xx”
1)	xx.js
2)	xx.json
3)	xx.node
2.	路由
(1)	路径（路由）：url.parse(req.url).pathname
(2)	参数：url.parse(req.url).query
①	querystring.parse(参数)
3.	服务器处理：
(1)	if(req.url != “favicon.ico”){}
(2)	设置字符编码
res.writeHead(200, {"Content-Type": "text/html; charset=utf-8" })
(3)	跨域处理
res.setHeader("Access-Control-Allow-Origin","*");

4.	读取文件
(1)	fs.readFile(“文件路径及名称”, function(result){})
(2)	fs.createReadStream()
5.	拷贝文件
(1)	fs.readFile(“文件路径及名称”, function(result){
Fs.writeFile(“文件路径及名称”, result, function(){})
})
(2)	fs.copyFile()
(3)	fs.createReadStream()/fs.createWriteStream()
(4)	pipe()
6.	

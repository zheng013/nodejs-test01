# nodejs-test01

## 启动应用

`node server.js 8888`

或者

`node server 8888`

## 添加路由

1. 编辑 server.js 文件，添加 if else
2. 重新运行 node server.js 8888



## 后台启动应用

touch log
`node server.js 8888 >log log 2>&1 &`

## 如何重启应用
* 更新完代码之后，git push 到仓库中
* ssh Frank@实例 
* cd nodejs-test
* git pull
* killall node
* sh ./start


### 无法使用ssh，只能通过阿里云网页版的编辑器复制代码到框里操作

持续更新---------

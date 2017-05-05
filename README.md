# nbot
### nodejs devops platform
项目构建自动化管理平台 [Road Map](https://github.com/nodenext/nbot/blob/master/document/roadmap.md "road map")
项目开发保持嵌入式的原则，不依赖任何第三方数据库或者redis等模块
项目使用cluster模式运行: 1 master 1 worker 方式共享内存

## base on
+ nodejs 7.6+
+ koa2 
+ socket.io 
+ react 
+ webpack2
+ nedb

## script
+ `yarn start` 启动服务 后台进程(暂不支持windows) 默认端口 `1357` 
+ `yarn stop`  停止服务 
+ `yarn reload` 重启服务  
+ `yarn dev` 启动react webpack-dev服务
+ `yarn build` react 生成正式环境代码 
+ `yarn watch` 联机调试
+ `yarn log` 显示服务器日志

## eslint 代码规范
```
sudo npm install -g eslint babel-eslint eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-promise@latest eslint-plugin-standard
```

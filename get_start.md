### 1.安装(ubuntu 14.04)

```bash
$ apt-get update
参考https://rtcamp.com/tutorials/nodejs/node-js-npm-install-ubuntu/ 安装node.js v0.10.
$ apt-get install python-software-properties 
$ apt-add-repository ppa:chris-lea/node.js 
$ apt-get update
$ apt-get install nodejs
$ apt-get install npm
$ apt-get install mongodb
$ sudo npm install -g express-generator --registry=https://registry.npm.taobao.org
//使用国内镜像加速npm 或者直接使用cnpm代替默认的npm
```

### 2.新建工程
```bash
$ express -e simpleblog
```
```bash
$ cd simpleblog && cnpm install
```
* app.js：启动文件，或者说入口文件
* package.json：存储着工程的信息及模块依赖，当在dependencies 中添加依赖的模块时，运行 npm install，npm 会检查当前目录下的 package.json，并自动安装所有指定的模块
* node_modules：存放 package.json 中安装的模块，当你在package.json 添加依赖的模块并安装后，存放在这个文件夹下
* public：存放 image、css、js 等文件
* routes：存放路由文件
* views：存放视图文件或者说模版文件
* bin：存放可执行文件




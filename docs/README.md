# npm 

> npm是nodejs的包管理工具

网页版地址

https://www.npmjs.com/

``` bash
node -v
```

``` bash
npm -v
```

## 设置国内淘宝镜像

``` bash
npm config set registry https://registry.npm.taobao.org
```

## 切换镜像的小工具nrm(牛肉面)

``` bash
npm install -g nrm

nrm ls
# 列出一些镜像地址
nrm use taobao
# 使用taobao镜像

nrm add local http://127.0.0.1:9090
# 添加一个镜像地址 可以本地搭建npm私服

```


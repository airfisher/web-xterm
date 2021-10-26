### 安装node
> https://www.runoob.com/nodejs/nodejs-install-setup.html

### 安装node包管理器 - yarn

全局安装yarn
```shell
npm install -g yarn
```

yarn 设置淘宝源
```shell
yarn config set registry https://registry.npm.taobao.org
```

### 安装依赖 && 启动项目
进入到项目根目录

安装依赖
```shell
yarn
```

启动后端服务
```shell
node server/index.js
```

启动前端服务
```shell
yarn start
```
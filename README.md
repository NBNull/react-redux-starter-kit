![react-starter-kit](./logo.png)
---------------------------------------------------------------
[![React](https://img.shields.io/badge/react-^16.2.0-brightgreen.svg?style=flat-square)](https://github.com/facebook/react)
[![Ant Design](https://img.shields.io/badge/ant--design-^3.0.3-yellowgreen.svg?style=flat-square)](https://github.com/ant-design/ant-design)
[![Mobx](https://img.shields.io/badge/redux-^4.0.0-orange.svg?style=flat-square)](https://github.com/reduxjs/redux)

**演示地址：**[https://beverle-y.github.io/react-redux-starter-kit](https://beverle-y.github.io/react-redux-starter-kit/)

**Mobx版：**[react-starter-kit](https://github.com/beverle-y/react-starter-kit)

## Quick Start
#### Down
~~~
git clone https://github.com/bevelery/react-redux-starter-kit.git
~~~

#### Install
~~~
yarn install
~~~

#### Dll
第一次运行需要打包vendor，仅运行一次。当依赖(vendor)改变时需重新打包，更改index.html内引入的路径。
~~~
npm run dll
~~~

#### Run
~~~
npm start
~~~

#### Build
~~~
npm run build
~~~

#### 发布CDN(推荐)

将project.config.js内publicPath改为服务器绝对路径。

#### 发布静态资源

若没有CDN，只能发布静态资源，需修改webpack配置，将所有文件放置在同一目录下。

## Ps
关于 dll 的说明：本项目使用 yarn 下载依赖包，有些同学习惯用 npm、cnpm，这样因为没有 lock 文件会导致依赖包的版本不同，致使 dll 的 hash 不同于本项目，所以有些人会遇到 404 或者资源没找到等情况，这种情况下只要改一下 html 引用的路径即可。

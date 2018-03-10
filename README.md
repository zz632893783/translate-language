# translate-language

 简易的翻译插件，demo地址[点我点我 click me](http://zoone.cc:8080/webproject/components_demo/translateLanguage)

## 安装

```bash
$ cnpm install translate-language
```

## 使用方法

 require引入之后，在js中调用即可 

### 示例

```js
 const translateFunc = require('translate-language');
 translateFunc();
```

 方法可以传入一个元素的id，如
```js
 translateFunc('app');
```
 则只会翻译app中的英文

## demo运行方法
 将项目下载到本地之后，
```js
 $ npm install
```
 安装node模块，在cmd中输入
```bash
 $ webpack-dev-server
```
 之后在浏览器中输入http://localhost:8080

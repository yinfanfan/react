### react-router
react的路由

安装：
```
$ npm install --save react-router
```
注意：本安装包提供React Router的核心功能，你可能不需要直接安装它。如果你写的是浏览器端项目，安装react-router-dom会更好。
同样的，如果你写的是个React Native应用（也就是APP）， react-router-native会比react-router更合适。两者都依赖react-router，
所以两者的安装都会携带react-router。

3种引入方式：
```
//1.es6
import { Router, Route, Switch } from 'react-router'

//2.CommonJS modules
var Router = require('react-router').Router
var Route = require('react-router').Route
var Switch = require('react-router').Switch

//3.script引入:
<script src="https://unpkg.com/react-router/umd/react-router.min.js"></script>
```
这样，你就可以通过window.ReactRouter读取router了

参考链接：
<https://github.com/ReactTraining/react-router/blob/master/packages/react-router/README.md>

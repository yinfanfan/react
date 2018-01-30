### react-router
安装：
```
$ npm install --save react-router
```

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
这样，你就可以通过window.ReactRouter读取router了。

注意：<br/>
本安装包提供React Router的核心功能，你可能不需要直接安装它。因为如果你写的是**浏览器端项目**，安装react-router-dom会更好。
同样的，如果你写的是个**React Native应用**（也就是APP）， react-router-native会比react-router更合适。
两者都依赖react-router，所以两者的package.json都会携带react-router。

## 各路由的功能：
### (1) react-router: 
实现了路由的核心功能

### (2) react-router-dom: 
基于react-router，加入了在浏览器运行环境下的一些功能，例如：Link组件，会渲染一个a标签（在浏览器审查元素可以看见a）; BrowserRouter和HashRouter组件，前者使用pushState和popState事件构建路由，后者使用window.location.hash和hashchange事件构建路由。

### (3) react-router-native: 
基于react-router，类似react-router-dom，加入了react-native运行环境下的一些功能。

### (4) react-navigation：
react-navigation默认提供的比如Header、StackNavigator和TabNavigator都是开发app时必备的，而这些react-router不提供。


参考链接：

<https://github.com/ReactTraining/react-router/blob/master/packages/react-router/README.md>

https://github.com/mrdulin/blog/issues/42

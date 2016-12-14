# react-native-open-projects
collect excellent react native open source components &amp; middleWare and so on
react native 优秀开源库集锦，欢迎协作推荐

## 1 导航 tabbar
### [wix/react-native-navigation](https://github.com/wix/react-native-navigation)
> 这是react native官方文档推荐的第三方导航组件，非常不错

<img src="https://github.com/wix/react-native/blob/master/assets/themes/bootstrap-3/images/demo.gif?raw=true" width="240">


### [react-native-scrollable-tab-view 滚动导航](https://github.com/skv-headless/react-native-scrollable-tab-view)
> 顶部导航条，支持拖拽滚动

<img src="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo.gif" width="240">
<img src="https://raw.githubusercontent.com/brentvatne/react-native-scrollable-tab-view/master/demo_images/demo-fb.gif" width="240">

### [react-native-tabbar 底部导航](https://github.com/alinz/react-native-tabbar)
> 底部导航菜单，下拉时可自动隐藏导航栏，上拉还原导航栏，非常适用于屏幕大小要求较高的app使用

<img src="https://github.com/alinz/react-native-tabbar/blob/master/tabbar-orientation.gif" width="240">



## 2 中间件
### [acdlite/redux-actions](https://github.com/acdlite/redux-actions)
> 自动创建action(actionCreator) 可结合下面几个中间件创建异步action，例如带promiser的异步action

### [acdlite/redux-promise](https://github.com/acdlite/redux-promise)
> 可结合上面的redux-actions 使用， 支持FSA actions，支持带promiser的action，但是缺点是无法同时支持多个action， 例如每次请求网络的action，在请求过程中不会dispatch，只能等待请求成功或失败后，才dispatch。如需支持异步请求action的其他过程action，例如PENDING (正在请求网络)这种action，建议使用下面这个中间件

### [redux-promise-middleware](https://github.com/pburtchaell/redux-promise-middleware)
> 功能与上面的redux-promise差不多，但是该中间件支持在异步请求时dispatch 一个 PENDING action， 这会让你在处理网络请求时更加容易控制UI的体验，推荐使用这个中间件替代redux-promise

### [tomatau/type-to-reducer](https://github.com/tomatau/type-to-reducer)
> 这是一个reducer creator, 可以帮助你快速创建reducer，并且能减少不少代码，推荐使用，结合上述 redux-promise-middleware 中间一起使用

## 3 demo案例
### [一个对redux官方文档中所提的“缩减样板代码”的实践--RNGithub](https://github.com/kaenry/RNGitHub)
> 实现了官方文档中所提到的如何抽象一个api调用的action和一个callApiMiddleware的中间件，[点这里](http://cn.redux.js.org/docs/recipes/ReducingBoilerplate.html)看中文redux文档关于如何缩减样板代码

### [纯React Native CNode论坛客户端](https://github.com/soliury/noder-react-native)
> 使用redux框架，redux-actions + redux-promise 中间件，值得参考，下面是运行效果图：

<img src="https://github.com/jacobcyl/react-native-open-projects/blob/master/screenshot/noder-react-native.gif" width="240">

## 欢迎大家一起维护这个文档，推荐优质的开源react native资源

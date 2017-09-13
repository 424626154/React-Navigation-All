# React-Navigation-All
React Navigation综合案例，讲解如何使用DrawerNavigator进行侧滑，
同时,示例中:

一：侧滑有以下两种实现方式：

1-：所有页面，都可以进行侧滑

2-：只有特定的TAb页面进行侧滑

index.android.js中修改入口文件即可：

//支持所有页面侧滑
import App from './jscode/tabAll/App';

//支持某个页面进行侧滑
import App from './jscode/tabOne/App'

二：动态化修改路由

下载完成后，修改index.ios.js:入口文件如下：

import App from './jscode/changestack/App'

AppRegistry.registerComponent('All', () => App);

即可运行



三：基于React-Native和Mobx的购物车


下载完成后，修改index.ios.js:入口文件如下：

import App from './jscode/shoppingcar/src/App'

AppRegistry.registerComponent('All', () => App);

即可运行

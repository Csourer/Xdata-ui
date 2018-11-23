# xdata-ui

> A Vue.js project
## 特性

- 基于 [Vue](http://vuejs.org/)`>=v2.1.4` 开发的可复用 UI 组件，并且可随产品需要扩展
- 使用Vue官方的工作流，支持 ES6
- 一系列线上产品都在使用中


## 浏览器支持

- 适用于 移动 和 部分PC 端(Chrome,safari,IE9+等)  

## 开发  
> 全局引入 -- 在 webpack 入口文件 main.js 中如下配置：

``` bash
# 安装
npm install xdata-ui --save  

# 引入css
import 'xdata-ui/package/xdata-ui.min.css'  

# 引入xdata-ui.min.js
import Xdata from 'xdata-ui' 

# 注入到vue
Vue.use(Xdata)
```

> 按需引入 -- 在 入口文件 main.js 或 组件内 中如下配置：

``` bash
# 全局组件 main.js引入
import Toast from 'xdata-ui/package/comps/components/toast'
Vue.prototype.$toast = Toast

# 一般组件
import xdataTag from 'xdata-ui/package/comps/components/tag'
...

components: {
    xdataTag
    ...
}
``` 

## 查看示例  

[在线示例](https://monw3c.github.io/xmui/dist/)  


## 组件列表

- [x] 标签


## 贡献

在此不一一感谢所有付出脑力体力的同仁，如有疑问，请与我们联系  
如果你在使用时遇到问题，或者有好的建议，欢迎给我们提 [Issue](https://github.com/monw3c/xmui/issues) 或 [Pull Request](https://github.com/monw3c/xmui/pulls)

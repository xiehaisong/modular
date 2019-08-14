# 规范
1. 要建立一个不做修改的公共CSS文件。base.sass
2. 建一个重置css文件 reset.sass
3. 统一ID名由小驼峰方式编写如isShow，统一class类名由下划线编写,如：header_left
4. 文件夹、文件、图片命名不能出现大写字母，统一下划线
5. 常用功能函数统一写在公用js文件global.js里;

# 目录结构
一个uni-app工程，默认包含如下目录及文件：
    
```
┌─components            uni-app组件目录
│  └─comp-a.vue         可复用的a组件
├─hybrid                存放本地网页的目录，详见
├─platforms             存放各平台专用页面的目录，详见
├─pages                 业务页面文件存放的目录
│  ├─index
│  │  └─index.vue       index页面
│  └─list
│     └─list.vue        list页面
├─static                存放应用引用静态资源（如图片、视频等）的目录，注意：静态资源只能存放于此
│    ├─js               js文件
│    ├─css              css文件
│    ├─images           图片库
│    └─video            视频库
├─common                存放应用公共引用静态资源（如图片、视频等）的目录，注意：静态资源只能存放于此
│    ├─js               js文件
│    ├─css              css文件
│    ├─images           图片库
│    └─video            视频库
├─wxcomponents          存放小程序组件的目录，详见
├─main.js               Vue初始化入口文件
├─App.vue               应用配置，用来配置App全局样式以及监听 应用生命周期
├─manifest.json         配置应用名称、appid、logo、版本等打包信息，详见
└─pages.json            配置页面路由、导航条、选项卡等页面类信息，详见
   ``` 
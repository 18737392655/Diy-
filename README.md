### 小程序页面自由DIY VUE3.0项目源码

## 安装依赖
```
npm install
```

### 运行项目
```
npm run serve
```

### 荐目打包
```
npm run build
```

### 项目说明

- 项目分为页面、模块、组件三个部分组成，可同时保存多个页面，可新建页面，可自由拖动模块至页面，模块可以复制，上下移动，可设置模块字体，背景，文字，图片，连接，样式等属性。
- 所有模块JS初始文件在 src/util/module.js 里面定义
- 页面主框架页面在 views/diy.vue 
- 模块属性设置在 views/attr/ 下面
- 模块上左右组件在 components/ 下面
- 拖入模块组件在 views/module/ 下面

### 后台保存说明

- 将页面控件和模块数据通过JSON形式保存到后台数据库
- 页面回显查询数据库然后转回数组回显到页面上
- 前端显示同样查询数据库将JSON转换为数组然后新建与项目样式相同的模块循环渲染在一个页面上。
- 主要弄明白每个模块里面字段的作用，在module.js里面都有备注说明

![Image text](https://img-blog.csdnimg.cn/20201104111620483.gif)

项目预览地址：[http://diy.hsycms.com/](http://diy.hsycms.com/)

项目交流群：942832552
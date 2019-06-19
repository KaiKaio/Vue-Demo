# Hello_World

- 引入 `Vue.js`
  - `<script src=" https://cdn.bootcss.com/vue/2.6.10/vue.min.js"></script>`
- 创建 `Vue` 对象
  - （`new Vue`）
  - `el`: 指定根element(选择器)
  - `data`: 初始化数据（页面可以访问）
- 双向数据绑定：`v-model`
- 显示数据：`{{xxx}}`
- 理解`vue`的`mvvm`实现

下图展示 `MVVM`

![Vue-MVVM](./Vue.gif)

## MVVM

- model: 模型，数据对象
- view: 视图，模板页面
- viewModel: 视图模型(Vue的实例)

原理：首先有一个`input`监听，一旦改变`input`值就把内存的`data`数据做出相应改变

关键词：`DOM监听`、`数据绑定`

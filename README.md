---
home: true
heroText: bdp-ui-vue组件库文档
tagline: 基于 ant-design-vue 封装的组件库
actionText: 快速入门 →
actionLink: /components/installation
---

## 安装

```shell
yarn add @bdp/ui-vue -S
```

## Usage

```js
import Vue from 'vue';
import { BModal } from '@bdp/ui-vue';
import App from './App';

Vue.component(BModal.name, BModal);

Vue.use(BModal);

new Vue({
    el: '#app',
    components: { App },
    template: '<App/>',
});
```

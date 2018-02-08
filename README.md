# jquery-tool-extend
jquery extend方法

> 无法直接饮用在html页面上，需要使用模块化加载器（如webpack/requirejs）加载后使用;

```bash
npm i jquery-tool-extend --save
```

```javascript
import extend from 'jquery-tool-extend';
extend({
    name:'Tom'
},{
    age:20
});//{name:'Tom',age:20}
```